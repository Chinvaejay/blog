---
title: test
date: 2019-08-09 17:01:46
tags:
---

## JS小技巧

### 快速debug
> 还在一个一个`console.log`吗，试试封装一个方法
```js
function log(a) {
    console.log(a)
    return a
}
```
### 短路表达式
> 将`if`改为短路表达式，显得更高大上

```js
if (condition) {
    dosomething()
}

// 改为

condition && dosomething()

```

> 设置默认值

```js
a = a || 'default value'
```