# Quick Start

Shoyo can be imported from both npm and CDN

## From npm

```bash
yarn add shoyo 
//or
npm i shoyo
```
Import the stylesheet in your code

#### js
```js
import "shoyo/dist/main.css";
```

#### css

```css
@import url("shoyo/dist/main.css"); 
```
!> If you use webpack or any other bundler you may need to add `~` before the url while imporing in your stylesheet e.g.

```css
@import url("~shoyo/dist/main.css"); 
```

## From CDN

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/soulsam480/shoyo@0.1.1/dist/main.css">
```

Minified version

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/soulsam480/shoyo@0.1.1/dist/main.min.css">
```