---
title: typescript 忽略类型检查
date: 2020-08-05
categories:
  - FE
tags:
 - typescript
---

# typescript 忽略类型检查

均为添加注释的方式

## 单行忽略

添加到特定行的行前来忽略这一行的错误

```ts
// @ts-ignore
let a:number = 1
```

## 跳过对某些文件的检查

添加到该文件的首行起作用

```ts
// @ts-nocheck
let a:number = 1
let b:number = 2
```
## 检查某些文件

添加到该文件的首行起作用

```ts
// @ts-check
let a:number = 1
```
