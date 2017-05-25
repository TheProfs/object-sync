[![Build Status](https://travis-ci.org/TheProfs/object-sync.svg?branch=master)](https://travis-ci.org/TheProfs/object-sync)

# \<object-sync\>

> Polymer 1.x element for syncing an object to a remote server
> **Warning:** This is not yet intended for a production release!

You simply specify a URL where the JSON resource resides.

The URL should accept:

- `GET` requests for fetching the object
- `PUT` requests for saving the object

The payload for saving - `PUT` - would be included in the `body` of the request.

The `value` is saved to the server only if it changes *after* it was initially
fetched successfully from the remote server so you don't have to worry about
timing issues.

## View element & documentation

```bash
$ polymer serve
```

## Contributing?

### Install the Polymer-CLI

Make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.

### Running for Dev

```bash
# Runs element with auto browser reload on file changes
$ npm run dev
```

### Running Tests

```bash
$ npm test
```

## License

> The MIT License

> Copyright (c) 2017 The Profs LTD, <www.theprofs.co.uk>

> Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

> The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
