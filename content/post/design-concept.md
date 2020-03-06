---
title: "Design Concept"
date: 2020-03-02T18:28:25+09:00
sec: 2
---

- Minimal syntax
- Statically typed
- Lightweight runtime
- Compile to native code

```go
func main() {
  print(fib(41))
}

func fib(n: int): int {
  return if n <= 1 {
    n
  } else {
    fib(n - 1) + fib(n - 2)
  }
}
```
