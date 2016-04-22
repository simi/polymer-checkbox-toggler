# Polymer namespaced checkbox toggler test

[![Build Status](https://travis-ci.org/simi/polymer-checkbox-toggler.svg?branch=master)](https://travis-ci.org/simi/polymer-checkbox-toggler)

* Demo: http://simi.github.io/polymer-checkbox-toggler/index.html
* Test: http://simi.github.io/polymer-checkbox-toggler/test/index.html

## Setup

```
npm install -g bower
bower install
```

## Development

Run some local assets server like:
```
ruby -run -e httpd . -p 1234
```

Open http://localhost:1234 and http//localhost:1234/test.

## Testing

```
npm install -g web-components-tester
wct test/input-toggler-tests.html
```
