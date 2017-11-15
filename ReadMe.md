# EJ2 Global Demo

## Installing Package 

`npm install` or `npm i`

## Using EJ2 Global Module 

All modules are registered under the `ej` namespace with the name of `<moduleName>`. You can access through `ej` name space.

The following example is to render the button component using the global file.

```js
var button1 = new ej.buttons.Button({
    isPrimary: true
});
button1.appendTo('#button');
```

## Running Application

`npm start`

