# SORAD Framework (Meta) Package

## Purpose

This package will install all of the packages needed for utilizing "Domain Driven Development" patterns on top of the Laravel framework.

## Features

* [```payload```](https://github.com/priskz/payload) - A simple way to encapsulate data and flag its state.

* [```paylorm```](https://github.com/priskz/paylorm) - A "data mapper" ORM built around simple Payloads (or encapsulated data) to facilitate data persistence.

* [```sorad-api```](https://github.com/priskz/sorad-api) - A service oriented API built around the Responder-Action-Domain pattern.

* [```fyler```](https://github.com/priskz/fyler) - A SORAD service built to streamline file processing and handling.

* [```sorad-entity```](https://github.com/priskz/sorad-entity) - A generic service implemented on top of the SORAD API + Paylorm that provides consistent conventions for facilitating the mapping of entities.

* [```sorad-service-provider```](https://github.com/priskz/sorad-service-provider) - A simple way to bootstrap and provide a service for the SORAD API.

* [```sorad-service```](https://github.com/priskz/sorad-service) - Generic implementation(s) for SORAD's service layer.

* [```sorad-module-core```](https://github.com/priskz/sorad-module-core) - A SORAD module for core application functionality.

* [```pusher```](https://github.com/priskz/pusher) - A small library for helping push socket messages. Note: will require additional packages: ```"cboden/ratchet": "0.3.5"``` && ```"react/zmq": "^0.3.0"``` to utilize.

## Install via Composer

Add the following to your composer.json "require" schema:

```
"require": {
     "priskz/sorad-framework": "~0.1.0"
}
```

Run ```composer install```