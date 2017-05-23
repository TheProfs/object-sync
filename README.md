[![Build Status](https://travis-ci.org/TheProfs/object-sync.svg?branch=master)](https://travis-ci.org/TheProfs/object-sync)

# \<object-sync\>

Polymer 1.x element for syncing an object to a remote server

You simply specify a URL where the JSON resource resides.

The URL should accept:

-  `GET` requests for fetching the object
- `PUT` requests for saving the object

The payload for saving - `PUT` - would be included in the `body` of the request.

The `value` is saved to the server only if it changes *after* it was initially
fetched successfully from the remote server so you don't have to worry about
timing issues.

## Install the Polymer-CLI

First, make sure you have
the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```bash
$ polymer serve
```

## Running for Dev

```bash
# Runs element with auto browser reload on file changes
$ npm run dev
```

## Running Tests

```bash
$ polymer test
```

Your application is already set up to be tested
via [web-component-tester](https://github.com/Polymer/web-component-tester).
Run `polymer test` to run your application's test suite locally.
