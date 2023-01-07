# python
## 2023-01-07
  - 1
    - 2
      - 3
        -백준 3003번
   cp = [1, 1, 2, 2, 2, 8]
   li = list(map(int, input().split()))
   for i in range(6):
    print(cp[i]-li[i], end=' ')
