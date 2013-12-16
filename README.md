gearman-async [![Coverage Status](https://coveralls.io/repos/bzikarsky/gearman-async/badge.png)](https://coveralls.io/r/bzikarsky/gearman-async) [![Build Status](https://travis-ci.org/bzikarsky/gearman-async.png?branch=master)](https://travis-ci.org/bzikarsky/gearman-async)
=============

A async Gearman implementation for PHP ontop of reactphp

## Current status:
- There is only an implementation for a Gearmn-client
- Code is only (!) unit-tested and adheres to http://gearman.org/protocol/ - There no integation tests with a existing Gearman server implementation yet

## Goals:
- Implement GearmanWorker
- Add integration tests for the official gearmand C implementation
- Implement own async GearmanServer
- Test and provide HHVM compatibility
