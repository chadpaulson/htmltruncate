[![Build Status](https://travis-ci.org/chadpaulson/htmltruncate.py.png)](https://travis-ci.org/chadpaulson/htmltruncate.py)

A module to truncate strings containing HTML.

```python
htmltruncate.truncate(str, target_len, ellipsis='')
```
    Returns a copy of str truncated to target_len characters,
    preserving HTML markup (which does not count towards the length).
    Any tags that would be left open by truncation will be closed at
    the end of the returned string.  Optionally append ellipsis if
    the string was truncated.
