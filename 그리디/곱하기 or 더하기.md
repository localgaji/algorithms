## 곱하기 or 더하기



---

#### 풀이 1. 

```python
def muladd(string):
    answer = 0
    for i in string:
        if answer <= 1 or int(i) <= 1:
            answer += int(i)
        else:
            answer *= int(i)
    return answer
```

#### 알게된 점
  + 

#### 어려웠던 점




