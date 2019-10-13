---
layout: post
title: Version 2.5.15 - DD, DF, DFF, DFZXS
---

This version fixes some errors: 

- The .error directive (now it works in a propper way and invoke an error in the 2nd pass)
- Some characters in strings causes errors
- 6502 emulator has an error in the FLAG register bit 5
- .SET and := are fixed to allow redefine value