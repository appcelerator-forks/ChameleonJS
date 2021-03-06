# Chameleon.js

Find the right complementary colors, great for automatically selecting text colors based on user supplied color values for background UI elements. For example:

<p align="center">
  <img src="http://i.imgur.com/rTz01Qb.gif" alt="color changing text"/>
</p>

## Installation

Via npm:

	npm install chameleon.js

## Usage
Use in Node.js / Titanium:

```javascript
var C = require("chameleonjs");
console.log( C('black') ); // #ffffff
console.log( C('#000000') ); // #ffffff
console.log( C(0, 0, 0) ); //[255, 255, 255]
console.log( C('red') ); // #00ffff
```
---

## What Chameleon.js does

* Get the complementary value of a Hexadecimal color.
* Get the complementary value of an RGB color.
* Get the complementary value of a css named color.

## What Chameleon.js will do

* Get the contrasting value of a Hexadecimal color.
* Get the contrasting value of an RGB color.
* Get the contrasting value of a css named color.
* Get the contrasting value for a Titanium mobile Status bar.

## What Chameleon.js MIGHT do down the road
* Get the colors from images and return the contrasting / complementary colors

* * *
