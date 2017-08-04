# polymer-address-info
polymer-address-info

This component contains basic information of official and residentials address.
## Installation

To install this component, follow the procedure:
 ```js 
 Add dependency in bower.json

  "dependencies": {

    "polymer-address": "git+https://github.com/Polymer-Developers-Forums/polymer-address-info.git"
}
```
### Import in index.html of root directory: 
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, minimum-scale=1.0, initial-scale=1.0, user-scalable=yes">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="mobile-web-app-capable" content="yes">
    <title>Polymer Project</title>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
   
     <link rel="import" href="bower_components/polymer-address/polymer-address.html" />    
</head>
<body>
      
</body>
</html>
```
### Examples:

```html
add the component in any HTML file
<polymer-address></polymer-address>
```
### To Test
Copy the login.test.html from bower_components/polymer-login-form and place it in test folder

In test/Index.html, import the component reference and add it to WCT.Load suites
```Shell
 
<!doctype html>
<html>
<head>
    <meta name="viewport" content="width=device-width, minimum-scale=1.0, initial-scale=1.0, user-scalable=yes">
    <title>PD Tests</title>
    <meta charset="UTF-8">

    <script src="../bower_components/webcomponentsjs/webcomponents.min.js"></script>
    <script src="../bower_components/web-component-tester/browser.js"></script>
    <link rel="import" href="../bower_components/polymer-address/polymer-address.html" />   
</head>
<body>

<script>
    WCT.loadSuites(['login.test.html']);
</script>
</body>
</html>

save the changes and in terminal
Type npm start
In browser, type localhost:6080/test
```
