# dottree
Enhance defaultdict 

# install
pip install dottree 

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

# downgrade to dict any time
print dict(d.M) # {'J': 7}

```
