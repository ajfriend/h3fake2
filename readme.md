# `h3fake2`

https://github.com/ajfriend/h3fake2

Temporary repo for transitioning `h3-py` from v3 to v4.

Idea: We just need a repo that builds the old v3 C library (and Cython bindings)
so we can patch it into the `h3-py` code to make sure everything works
temporarily as we move in the new v4 C library and transition each of the
Cython/Python functions.


Install with:

```
pip install git+https://github.com/ajfriend/h3fake2.git
```
