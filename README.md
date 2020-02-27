# dottree

"Enhanced defaultdict" 


# install

- Use pip to install 
- tested in Python2


```bash
pip install dottree 
``

# Quick test

```python 
"""
How to use:
- use like a dict
- use like an object 
- go as deep you want
"""

from dottree import dotree as dot

d = dot()
d.M.J = 7
assert  d.M.J  == 7
assert  d['M']['J']  == 7

# downgrade to a dict any time
print dict(d.M) # {'J': 7}

```
