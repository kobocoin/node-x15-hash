node-x15-hash
===============

x15 hashing function for node.js. Useful for various cryptocurrencies.

Usage
-----

Install

    ~


Hash your data

    var x15 = require('x15-hash');

    var data = new Buffer("hash me good bro");
    var hashed = x15digest(data); //returns a 32 byte buffer

    console.log(hashed);
    //<SlowBuffer 0b de 16 ef 2d 92 e4 35 65 c6 6c d8 92 d9 66 b4 3d 65 ..... >

Credits
-------

* Uses scrypt.c written by Colin Percival
* [Neisklar](https://github.com/Neisklar/quarkcoin-hash-python) for the python module this is based off of
