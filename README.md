# Furtive Item Grid

A CSS module for styling item grids. Used in [furtive.css](http://furtive.co).

See the experiment in action: <http://codepen.io/johno/full/wBWKvw>.

## Installation

It's recommended to use [rework-npm](https://github.com/reworkcss/rework-npm):

```
npm install --save furtive-item-grid
```

```javascript
var rework = require('rework'),
    reworkNPM = require('rework-npm');

var output = rework('@import "furtive-item-grid";', { source: 'my-file.css' })
    .use(reworkNPM());
```

## Usage

Detailed documentation and examples can be found at [furtive.co](http://furtive.co).

## License

MIT

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by [John Otander](http://johnotander.com) ([@4lpine](https://twitter.com/4lpine)).
