I wanted to be able to get song data from [NSF files](https://wiki.nesdev.com/w/index.php/).

Seems the only way to do it reliably is to emulate a 6502.

Several great NES emulators exist, including a few I found in Lisp/Clojure(script). However, most of them seem to have limited to nonexistent audio support. This project aims to fill that gap by focusing on implementing [a subset of instructions](http://wiki.nesdev.com/w/index.php/APU_basics) for the most basic features related to producing audio.
