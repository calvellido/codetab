![Built With Stencil](https://img.shields.io/badge/-Built%20With%20Stencil-16161d.svg?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjIuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MTIgNTEyOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI%2BCjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI%2BCgkuc3Qwe2ZpbGw6I0ZGRkZGRjt9Cjwvc3R5bGU%2BCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik00MjQuNywzNzMuOWMwLDM3LjYtNTUuMSw2OC42LTkyLjcsNjguNkgxODAuNGMtMzcuOSwwLTkyLjctMzAuNy05Mi43LTY4LjZ2LTMuNmgzMzYuOVYzNzMuOXoiLz4KPHBhdGggY2xhc3M9InN0MCIgZD0iTTQyNC43LDI5Mi4xSDE4MC40Yy0zNy42LDAtOTIuNy0zMS05Mi43LTY4LjZ2LTMuNkgzMzJjMzcuNiwwLDkyLjcsMzEsOTIuNyw2OC42VjI5Mi4xeiIvPgo8cGF0aCBjbGFzcz0ic3QwIiBkPSJNNDI0LjcsMTQxLjdIODcuN3YtMy42YzAtMzcuNiw1NC44LTY4LjYsOTIuNy02OC42SDMzMmMzNy45LDAsOTIuNywzMC43LDkyLjcsNjguNlYxNDEuN3oiLz4KPC9zdmc%2BCg%3D%3D&colorA=16161d&style=flat-square) [![npm version](http://img.shields.io/npm/v/@47deg/codetab.svg?label=npm%20package&style=flat-square&logo=npm&logoWidth=20)](https://npmjs.com/package/@47deg/codetab "View this project on npm")

# Codetab

Tab selector web component.


## Preview

![Codetab preview](preview.png "Codetab")


## Installation

### Load it from a CDN

- Put a script tag similar to this `<script src='https://unpkg.com/@47deg/codetab/dist/codetab/codetab.js'></script>` in the head of your `index.html`.
- Then you can use the element anywhere in your template, JSX, html etc.

### Host your own instance

- Run `npm install @47deg/codetab --save`.
- Put a script tag similar to this `<script src='node_modules/@47deg/codetab/dist/codetab.js'></script>` in the head of your `index.html`.
- Then you can use the element anywhere in your template, JSX, html etc.

### In JS environment app
- Run `npm install @47deg/codetab --save`.
- Add an import to the npm packages `import @47deg/codetab;`.
- Then you can use the element anywhere in your template, JSX, html etc.


## Usage

Once loaded on your site, you can simply use it like this:

```html
<fortyseven-codetab data-languages='["Scala", "Kotlin", "Swift", "Haskell]'>
  <code>
    Scala code snippet
  </code>
  <code>
    Kotlin code snippet
  </code>
  <code>
    Swift code snippet
  </code>
  <code>
    Haskell code snippet
  </code>
</fortyseven-codetab>
```

Codetab will show one element at a time depending on the tab you have selected. The web component will respect styles associated with those elements, so will happen with any code highlighting, which are responsibility of your website styling.


## Contributing or modifying this web component

Codetab is built with Stencil, a compiler for building fast web apps using Web Components.

Stencil components are just Web Components, so they work in any major framework or with no framework at all. To start playing with it, clone this repo to a new directory:

```bash
git clone https://github.com/47degrees/codetab.git codetab
cd codetab
```

and run:

```bash
npm install
npm start
```

To build the component for production, run:

```bash
npm run build
```

To run the unit tests for the components, run:

```bash
npm test
```

Need help? Check out our docs [here](https://stenciljs.com/docs/my-first-component).
