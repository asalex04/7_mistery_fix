This is a  example to use testing in Python
   
   * the `quadratic_equation.py` is a script that solves quadratic equations and returns roots
   * the `tests.py` is a test for `quadratic_equation.py`
   
# How to Use

   
  Example usage code
```python    
from quadratic_equation import get_roots

a = int(input('Введите a:'))
b = int(input('Введите b:'))
c = int(input('Введите c:'))

root1, root2 = get_roots(a, b, c)
print(root1, root2)
```

# How to Launch Tests 

The script requires for its operation installed Python interpreter version 3.5

```bash
$ python tests.py

```
# Project Objectives

Code created for training purposes. Training course on web development ― [DEVMAN.org](https://devman.org)
