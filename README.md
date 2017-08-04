# polymer-address-info
polymer-address-info

This component contains basic information of official and residential address.
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
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>polymer-element</title>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="bower_components/paper-input/paper-input.html" />
    <link rel="import" href="bower_components/paper-item/paper-item.html">
<link rel="import" href="bower_components/paper-listbox/paper-listbox.html">
<link rel="import" href="bower_components/paper-dropdown-menu/paper-dropdown-menu.html">

    <link rel="import" href="bower_components/polymer/polymer.html" />
    <link rel="import" href="bower_components/polymer-address/polymer-address.html" />
    <style>
      body {
        margin: 0px;
        padding: 0px;
        line-height: 1;
        font-family: 'Segoe UI', Frutiger, 'Frutiger Linotype', 'Dejavu Sans', 'Helvetica Neue', Arial, sans-serif;
        font-size: 13px;
      }
      body, html {
        height: 100%;
      }
      polymer-address {
        height: 100%;
        width: 100%;
        float: left;
        clear: left;
      }
</style>
  </head>
  <body>
        <polymer-address></polymer-address>

  </body>
</html>

```
### Examples:

```html
add the component in any HTML file
<polymer-address></polymer-address>
```
