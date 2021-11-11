---
title: basicTinerTest
tags: time,test,beginner
firstSeen: 2021-11-11T10:11:58.343Z
---

Basic time bench test for any computation.

- Use `console.time()`to begin a test.
- Between are the codes that you want to take the test with.
- Use `console.timeEnd()`to end the test and automaticly log the result.

```js
console.time("timer");
// some codes
console.timeend("timer");
```

```js
console.time("timer");
for(var i=0;i<10000;i++){}
console.timeEnd("timer");// the console will log the time test result
```
