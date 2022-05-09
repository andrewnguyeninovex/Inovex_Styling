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
