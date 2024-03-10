---
title: Abs
description: Returns the absolute value of the given time.Duration value.
categories: []
keywords: []
action:
  related:
    - functions/time/Duration
    - functions/time/ParseDuration
  returnType: time.Duration
  signatures: [DURATIO![Screenshot_20240225_200817_Microsoft 365 (Office)](https://github.com/gohugoio/hugoDocs/assets/126146880/2b732302-81d2-4844-92dc-518f56686203)
![Screenshot_20240305_194135_Gallery](https://github.com/gohugoio/hugoDocs/assets/126146880/cd3e5551-3fdc-472b-8176-9f78ca34e8f3)
N.Abs]
---

```go-html-template
{{ $d = time.ParseDuration "-3h" }}
{{ $d.Abs }} → 3h0m0s
```
