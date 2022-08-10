The list of non-negative integers that are less than n = 3 is [0,1,2] . Print the square of each number on a separate line.

```python
if __name__ == '__main__':
    n = int(input())
    for i in range(n):
        print(i**2)
```