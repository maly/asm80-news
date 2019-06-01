---
layout: post
title: Version 2.5.1 - some fixes
---

This version fixes a bunch of errors, as reported by Keith Howell (thanks!)

- `LABEL EQU 123 ;strips comments from listing` _fixed_
- `FCC "string"` was not implemented. _fixed_
- `DS "something"` was silently done, totally disrupted the code. _fixed_
- `EQU something` without a label now throw an exception.
- M6800 assembler has a problem with an empty comment line. _fixed_