*This repository is a mirror of the [component](http://component.io) module [andrewrk/diacritics](http://github.com/andrewrk/diacritics). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/andrewrk-diacritics`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# diacritics

  remove diacritics from strings

  useful when implementing some kind of search or filter functionality.

## Node.js Installation

    $ npm install diacritics

## Component Installation

    $ component install andrewrk/diacritics

## API

```js
var removeDiacritics = require('diacritics').remove;
console.log(removeDiacritics("Iлｔèｒｎåｔïｏｎɑｌíƶａｔï߀ԉ"));
// prints "Internationalizati0n"
```

## License

  MIT
