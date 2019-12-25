---
title: find_range
tags: math,beginner
---

Find the range of an Array

Use `maximum()` and `minimum()` functions to get the maximum and minimum values of a array and subtract them to get the range of the data.

```jl
function find_range(a)
  return maximum(a) - minimum(a)
end
```

```jl
find_range([2,5,6,10]) # 8
```
