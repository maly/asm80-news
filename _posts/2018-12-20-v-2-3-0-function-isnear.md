---
layout: post
title: Version 2.3.0 - Function ISNEAR
---

Useful for some macros, where you need to decide between near and far jump.

```
.macro jeq
 .if isnear(%%1-$)
  beq %%1
 .else
  bne $+5
  jmp %%1
 .endif
.endm
```