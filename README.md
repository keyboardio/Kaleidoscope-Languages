# Kaleidoscope-Languages

![status][st:experimental] [![Build Status][travis:image]][travis:status]

 [travis:image]: https://travis-ci.org/keyboardio/Kaleidoscope-Languages.svg?branch=master
 [travis:status]: https://travis-ci.org/keyboardio/Kaleidoscope-Languages

 [st:stable]: https://img.shields.io/badge/stable-✔-black.svg?style=flat&colorA=44cc11&colorB=494e52
 [st:broken]: https://img.shields.io/badge/broken-X-black.svg?style=flat&colorA=e05d44&colorB=494e52
 [st:experimental]: https://img.shields.io/badge/experimental----black.svg?style=flat&colorA=dfb317&colorB=494e52

This library is a collection of key aliases and examples for various languages
and layouts. All of these assume that the computer is set up to use the
respective keyboard layout.

## Using a language / layout

By default, the library does not introduce any new keys, because there may be
conflicts between the languages. Instead, users are encouraged to include the
language support header they need.

```c++
#include "Kaleidoscope-Languages.h"
#include "kaleidoscope/lang/de-qwertz.h"
```

See the list of supported languages below for detailed description about what
symbols they define, and where to find an example layout using them.

## Supported languages & layouts

No language or layout is supported yet, we're just setting up the framework for
now.
