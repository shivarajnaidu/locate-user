# locate-user
Know Your Client's Location


[![Build Status](https://travis-ci.org/shivarajnaidu/locate-user.svg?branch=master)](https://travis-ci.org/shivarajnaidu/locate-user)

## Install
(This Requires Node 4.x or Later...)

```
npm install locate-user --save
```

### API

locateUser(req)

* `req` - REQUIRED: http/https server request object


## Usage

```js
'use strict';
const http = require('http');
const locateUser = require('locate-user');

http.createServer(function (req, res) {
  const userLocation = locateUser(req);
  res.end(userLocation);
}).listen(3000);
```



### Please Contribute And Improve It..

Thank You!

