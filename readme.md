*This repository is a mirror of the [component](http://component.io) module [ramitos/resizable-textarea](http://github.com/ramitos/resizable-textarea). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-resizable-textarea`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# resizable-textarea

make a textarea auto resizable. [demo](http://ramitos.github.com/resizable-textarea/)

## install

```bash
$ component install ramitos/resizable-textarea
```

## api

```js
var rta = require('resizable-textarea');

rta(document.getElementById('some-textarea-id'));
```

## issues

 * the textarea only grows, and doesn't shrink when the text is reduced.

## License

MIT