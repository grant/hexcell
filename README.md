# hexcell

A hexagon cell for a hexgrid

```sh
npm install hexcell --save
```

## Example

```js
var Point = require('point2d');
var Hexcell = require('hexcell');

var point = new Point(2, 3);
var cell = new Hexcell(point, { extraData: 3 });
console.log(cell.data.extraData); // 3
```

## Methods

### Hexcell(point2d)
Creates a hexcell at point `point2d`

### Hexcell(point2d, data)
Creates a hexcell at point `point2d` with an object `data` that contains data

### Hexcell.data
The data attached to this cell