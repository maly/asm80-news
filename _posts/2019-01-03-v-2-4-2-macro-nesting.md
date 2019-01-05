---
layout: post
title: Version 2.4.2 - Macro nesting
---


Now you can nest a macro in another macro:

```
.macro one
 ld c,%%1
.endm

.macro two
 one 1
 add a,c
.endm
```