### Task
- The provided code stub reads two integers,  and , from STDIN.

    - Add logic to print two lines. The first line should contain the result of integer division, a // b. 
    - The second line should contain the result of float division, a / a.

    No rounding or formatting is necessary.

```python
if __name__ == '__main__':
    a = int(input())
    b = int(input())
    integer_division = a // b
    float_divsion = a / b
    print(integer_division)
    print(float_divsion)
```