![This is an image](Inovex-logo.jpg)
# Inovex Best Practice :blush:

## Eslint

Indentation
```js
<-- 4 Spaces -->
value: {
--> actual: 0,
    maxValue: 0,
    minValue: 0,
    low: 0,
    showActual: true,
    value: 0
    }
```

File Extensions
```js
ShoppingCart.tsx // [tsx] for components
ShoppingCartProps.ts // [ts] for interface, utility, stateless functions
GetShoppingCartData.js // [js] for files that don't require typescript
```

Quotations
```js
<-- OK -->
import "./ExampleComponent.scss";
```
```
<-- NOT OK -->
import './ExampleComponent.scss';
```

Arrow Functions

Variable Definition



## CSS Guide

## Component Decision Making
Always create components with **reusability in mind**.
Will the component contain states? Will it handle prop manipulation or just take in data?
Determine if it's going to be a static component that has nothing but the bare minimum. Pizza dough without the topping.

Treat components like lego blocks :bricks:

## Debugging Tips

```
<-- The sweet sweet console.log -->
console.log("Hello World")
console.log("%cHello World", "color: red")
```
Output: ![image](https://user-images.githubusercontent.com/102827542/168629196-e6c77727-2c5f-4b59-b77a-b948bbd2c8c5.png)


```
<-- console.dir is great to show the print in object form -->
let objectA = {name: "Inovex", location: "Oakville"};
console.dir(objectA)
console.log(objectA)
```
Output: ![image](https://user-images.githubusercontent.com/102827542/168629597-f1b391e4-cdd6-4482-9423-9792c46f7f29.png)


## Folder Structure

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js
 ```
### Help

https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

https://google.github.io/styleguide/htmlcssguide.html

https://github.com/airbnb/javascript
