<img src="demo.gif" width="350px" alt="Demo">

<strong>How to use</strong><br>
```html
this.snackbar.show("Data saved successfully at this point in time because it succeed in its success", 'success', 3000);
```
<strong>Remember to import and register the service in the file</strong><br>
```html
constructor(private snackbar: SnackbarService) {}
````
This snackbar system was cautiously made to not having overlaping timers in the destruction of each instance, so it bahaves like this:
Once a new call is made, the latest instance is destroyed and its timer outputs nothing.<br>
