# Micro apps & Web Components

Using web components as a wrapper small, independent components is a practice which ticks many boxes, I am going to demo this example using Angular and React alongside each other in a single application. The components can receive data in and send it out without problems using normal attributes.

Follow the instructions below to build and serve micro frontend components, and the app shell which composes them together and handles communication between them.

Hope you enjoy your time in Oslo and please come and say hi if you saw me 😊.

## Build and serve Angular component

```sh
cd micro-app-ng
npm i
npm start
```

To use this component, include the main script and then use the element.

```html
<body>

<ng-el name="Yaser"></ng-el>

<script src="http://localhost:5001/main.js"></script>

</body>
```

## Build and serve React component

```sh
cd micro-app-react
npm i
npm start
```

To use this component, include the main script and then use the element.

```html
```html
<body>

<react-el name="Yaser"></react-el>

<script src="http://localhost:5002/main.js"></script>

</body>
```

## Build and serve the app shell

```sh
cd micro-app-shell
npm i
npm start
```

Now open a browser and head to [http://localhost:5000](http://localhost:5000).