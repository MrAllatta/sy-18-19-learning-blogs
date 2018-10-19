---
layout: post
title: "Flag Project v0"
date: 2018-10-19
---

Students are working toward creating programs that reproduce an intended output. One of their first experiences with this skill is the flag project. Students use the HtDP image library in either Racket or Pyret to create a collage program to accurately display the national flag of a country.

Here is an example of that flag:
![Flag of Japan](/images/JapanFlag.png)

```python
include image 

fun japan(size):
  width = size * 300
  height = size * 200
  bkg = rectangle(width, height, "outline", "black")
  dot = circle((height / 2) * 3/5, "solid", "red")
  overlay(dot, bkg)
end
```
