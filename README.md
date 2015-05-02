jEngine: $cookie
================
[![Bower version](https://badge.fury.io/bo/jstools-cookie.svg)](http://badge.fury.io/bo/jstools-cookie)

Installation
------------
```.sh
npm install jstools-cookie --save
```
or
```.sh
bower install jstools-cookie --save
```

Quick Usage
-----
```.js
cookie.set(cookieName, cookieValue)
cookie.set('foo', 'var')

cookie.get(cookieName);
cookie.get('foo')
// returns 'bar'

cookie.remove(cookieName);
cookie.remove('foo');
```

Full Usage
----------
```.js
cookie.set(cookieName, cookieValue, 'Fri, 31 Dec 9999 23:59:59 GMT' {UTC Format}, path, domain, secure)
```
