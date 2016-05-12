JNA Bindings for [pigpio](https://github.com/joan2937/pigpio)
---
[![Build Status](https://travis-ci.org/jw3/pigpio-jna.svg?branch=master)](https://travis-ci.org/jw3/pigpio-jna)

Attempt at a Travis based generation of JNA bindings for the great pigpio library.

Using a git submodule to import pigpio and a dockerized JNAerator we generate a JNA bindings jar and push it to Bintray.

This is currently a WIP using the 0.x numbers, when stable the version number will be synced to the supported pigpio version.

Current WIP is based on pigpio [V52](https://github.com/joan2937/pigpio/commit/09adafce0ce22e383a6c3d33f3e81f39201e29a6)

### Artifacts

```"com.github.jw3" % "pigpio-jna" % "0.2"```

### Bugs and Feedback

For bugs, questions and discussions please use the [Github Issues](https://github.com/jw3/pigpio-jna/issues).

### License

This is free and unencumbered software released into the public domain.

For more information, please refer to <http://unlicense.org/>
