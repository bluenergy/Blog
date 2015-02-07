title: Tips about golang
date: 2015-02-06 15:54:16
tags:
---

## Some tips about using golang for myself

### 1. Cross compile golang app for arm 

```
 $ cd <src dir>
 $ GOOS=linux GOARCH=arm go build
```