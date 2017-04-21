# npmdoc-ascoltatori

#### api documentation for  ascoltatori (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-ascoltatori.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ascoltatori) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ascoltatori.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ascoltatori)

#### The pub/sub library for node backed by Redis, MongoDB, AMQP (RabbitMQ), ZeroMQ, Kafka, MQTT (Mosquitto) or just plain node!

[![NPM](https://nodei.co/npm/ascoltatori.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ascoltatori)

- [https://npmdoc.github.io/node-npmdoc-ascoltatori/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ascoltatori/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ascoltatori/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ascoltatori/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ascoltatori/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ascoltatori/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ascoltatori",
    "version": "4.1.0",
    "description": "The pub/sub library for node backed by Redis, MongoDB, AMQP (RabbitMQ), ZeroMQ, Kafka, MQTT (Mosquitto) or just plain node!",
    "main": "index.js",
    "scripts": {
        "test": "mocha --recursive --bail --reporter spec test --globals Promise",
        "ci": "mocha --recursive --bail --watch test",
        "coverage": "rm -rf coverage; istanbul cover _mocha -- --reporter spec --bail --globals Promise",
        "publish-coverage": "(cat coverage/lcov.info | coveralls)",
        "jshint-lib": "jshint lib/*.js",
        "jshint-test": "jshint test/*.js"
    },
    "pre-commit": [
        "jshint-lib",
        "jshint-test",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/mcollina/ascoltatori.git"
    },
    "bugs": {
        "url": "http://github.com/mcollina/ascoltatori/issues"
    },
    "keywords": [
        "publish",
        "subscribe",
        "pubsub",
        "rabbitmq",
        "zeromq",
        "0mq",
        "mqtt",
        "amqp",
        "mosquitto",
        "mongodb",
        "mongo",
        "kafka",
        "pub",
        "sub"
    ],
    "author": "Matteo Collina <hello@matteocollina.com>",
    "license": "MIT",
    "contributors": [
        "Filippo De Pretto <filnik90@gmail.com>",
        "David Halls <dave@davedoesdev.com>"
    ],
    "devDependencies": {
        "mocha": "^3.0.0",
        "chai": "^3.4.1",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0",
        "optimist": "^0.6.1",
        "dox-foundation": "^0.5.6",
        "mosca": "2.1.0",
        "jshint": "^2.8.0",
        "istanbul": "^0.4.0",
        "coveralls": "^2.11.4",
        "pre-commit": "^1.1.2"
    },
    "dependencies": {
        "debug": "^2.2.0",
        "uuid": "^3.0.0",
        "qlobber": "~0.7.0",
        "steed": "^1.1.3"
    },
    "optionalDependencies": {
        "ioredis": "^2.3.0",
        "msgpack-lite": "^0.1.20",
        "zmq": "^2.14.0",
        "amqp": "~0.2.4",
        "amqplib": "~0.5.1",
        "mqtt": "^2.3.0",
        "mongodb": "^2.1.18",
        "kerberos": "~0.0",
        "eventemitter2": "^2.1.3",
        "qlobber-fsq": "^6.1.0",
        "kafka-node": "~0.5.8"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
