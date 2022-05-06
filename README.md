![This is an image](Inovex-logo.jpg)
# Inovex Best Practice

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
```

Quotations
```js
ShoppingCart.tsx // [tsx] for components
ShoppingCartProps.ts // [ts] for interface, utility, stateless functions
```
```js
ShoppingCart.tsx // [tsx] for components
ShoppingCartProps.ts // [ts] for interface, utility, stateless functions
```
## CSS Guide

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

```js
const [activeItem, setActiveItem] = useState(0); 
const [eventProperties, setEventProperties] = useState<ISafetyMetricsDataPoint[]>([]);
const [maxValue, setMaxValue] = useState<number>(0);
const {selectedSafetyMetric, setSelectedEventItems} = props;
```

