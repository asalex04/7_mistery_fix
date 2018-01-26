This is a  example to use testing in Python
   
   * the `quadratic_equation.py` is a script that solves quadratic equations and returns roots
   * the `tests.py` is a test for `quadratic_equation.py`
   
# How to Use

   * clone this repo
   * launch `tests.py`
   
  Example usage code
```python    
import unittest

from quadratic_equation import get_roots

class QuadraticEquationTestCase(unittest.TestCase):
    def test_solves_real_roots(self):
        root1, root2 = get_roots(1, -2, 1)
        self.assertEqual(root1, 1)
if __name__ == '__main__':
    unittest.main()
```

# How to Launch Tests 

The script requires for its operation installed Python interpreter version 3.5

```bash
$ python tests.py

```
# Project Objectives

Code created for training purposes. Training course on web development ― [DEVMAN.org](https://devman.org)
