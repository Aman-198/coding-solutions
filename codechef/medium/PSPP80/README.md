# PSPP80

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

_Description not available._

## Solution

**Language:** Python  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-07-23T09:57:13.043Z  

```py
def compute_value(a, b):
    # update your code below this line
    c = a*a + 2*a*b + b*b 
    d = a + b 
    print(c)
    print(d)
    
    
    
    

t = 3
for _ in range(t):
    A, B = map(int, input().split())
    compute_value(A, B)

```

---

[View on CodeChef](https://www.codechef.com/problems/PSPP80)