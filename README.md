# Small effects in JS

This project is only to learn from other people and try my own effects (for fun only :) ).

The comments in files are mainly in french.

These effects are not clean code since it's only done for small duration, so it doesn't care of well formed HTML or browser compatibility...

## Performance hint

[Source for performance measuring](https://www.sitepoint.com/measuring-javascript-functions-performance/)

Global time measurment (update and drawing scene) :

- Use of forEach : replace `forEach` by `for` (median time drop from 6s to 5s).