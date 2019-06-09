---
layout: post
title: Version 2.5.3 - DD, DF, DFF, DFZXS
---

A new directives for defining numbers, like DB and DW:

- DD for defining double words (4 bytes)
- DF for defining floating point number (IEEE-754), 32bit
- DFF for defining double precision FP number (64bit)
- DFZXS for defining floating point number in the ZX Spectrum style (warning: `0.5` error is fixed, so no `7f 7f ff ff ff`)