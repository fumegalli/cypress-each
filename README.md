# cypress-each ![cypress version](https://img.shields.io/badge/cypress-8.5.0-brightgreen)
> An demo of mocha-each and custom describe.each and it.each implementation for Cypress

Find the implementation in [src/index.js](./src/index.js)

## Specs

- [it-spec.js](./cypress/integration/it-spec.js) uses no shortcuts to define multiple tests that are almost the same. We want to avoid the repetition
- [it-each-spec.js](./cypress/integration/it-each-spec.js) uses the `it.each` helper to generate multiple `it` tests given a data array
- [describe-each-spec.js](./cypress/integration/describe-each-spec.js) uses `describe.each` helper to create `describe` blocks for each item in the given data array
- [mocha-each-spec.js](cypress/integration/mocha-each-spec.js) uses 3rd party [mocha-each](https://github.com/ryym/mocha-each) to generate `it` tests for each data item

## Small print

Author: Gleb Bahmutov &lt;gleb.bahmutov@gmail.com&gt; &copy; 2021

- [@bahmutov](https://twitter.com/bahmutov)
- [glebbahmutov.com](https://glebbahmutov.com)
- [blog](https://glebbahmutov.com/blog)
- [videos](https://www.youtube.com/glebbahmutov)
- [presentations](https://slides.com/bahmutov)
- [cypress.tips](https://cypress.tips)

License: MIT - do anything with the code, but don't blame me if it does not work.

Support: if you find any problems with this module, email / tweet /
[open issue](https://github.com/bahmutov/cypress-each/issues) on Github

## MIT License

Copyright (c) 2021 Gleb Bahmutov &lt;gleb.bahmutov@gmail.com&gt;

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
