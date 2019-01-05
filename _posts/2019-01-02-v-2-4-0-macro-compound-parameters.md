---
layout: post
title: Version 2.4.0 - Macro compound parameter
---

Let's imagine a macro:

```
.macro test
 db %%1
 dw %%2
.endm
```

If you use this macro in such form, everything is OK:
```
 test $12, $3456
```

Two parameters is OK. But what if you need the first DB is something like `db $de,$ad,$be,$ef`? You can use the compound parameter:
```
 test {$de,$ad,$be,$ef}, $3456
```
