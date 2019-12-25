---
title: degrees_to_rads
tags: math,beginner
---

Converts an angle from degrees to radians.

Use Julia's built in `pi` irrational data type and the degrees to radians formula to convert the angle from degrees to radians.

```jl
function degrees_to_rads(deg)
  return (deg * pi) / 180.0
end
```

```jl
degrees_to_rads(180) # 3.141592653589793
```
