# EventDispatcher

[![Build Status](https://travis-ci.org/jpcercal/javascript-event-dispatcher.svg?branch=master)](https://travis-ci.org/jpcercal/javascript-event-dispatcher)
[![Code Climate](https://codeclimate.com/github/jpcercal/javascript-event-dispatcher/badges/gpa.svg)](https://codeclimate.com/github/jpcercal/javascript-event-dispatcher)
[![Bower](https://img.shields.io/bower/v/javascript-event-dispatcher.svg?style=square)](https://github.com/jpcercal/javascript-event-dispatcher)
[![Bower](https://img.shields.io/bower/l/javascript-event-dispatcher.svg?style=square)](https://github.com/jpcercal/javascript-event-dispatcher)

- A cross browser Event Dispatcher written in native Javascript **contribute with this project**!

## Installation

- The package is available on [Bower](http://bower.io/).

```shell
bower install javascript-event-dispatcher --save
```

**If you liked of this library, give me a *star =)*.**

## Documentation

This library was created to fire events on input elements and that is all folks.

```javascript
// ...

var dispatcher = new EventDispatcher(document.getElementById('name'));

dispatcher
    .dispatch('change')
    .dispatch('input')
;
```

Contributing
------------

1. Give me a star **=)**
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Added some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new Pull Request
