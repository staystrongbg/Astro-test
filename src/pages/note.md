---
layout: ../layouts/BaseMdLayout.astro
title: JS Podsetnik
date: 22. 09. 2022
author: Devox
---

## JS podsetnik

- function declarations are hoisted and function expressions not.

- arrow fn when in single line doesn't require `return`

- error throwing

```
if (!land) {
throw new Error("A lord must have a land");
}
```

### es6 way of creating arr of n ele

`const createArr = (length) => [...Array(length).keys()];`

### fn return value pri pozivu fn treba upisati u varijablu ako zelimo da stampamo povratnu vrednost, ovako:

```
function val(x,y){
return x+y
}
const sum = val(4,5)
console.log(sum) // 9
```
