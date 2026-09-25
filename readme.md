#markdown
# Python Week 6 - Error Handling

`safe_tools.py` contains three functions that safely handle division, number conversion, and missing dictionary fields.

`unbreakable.py` contains the error-handling practice program from Question 2.

An `if` check cannot catch `"abc"` on its own because `"abc"` is text that cannot be converted into an integer. The `int()` conversion raises a `ValueError`, so `try` and `except` are needed to handle the error safely.
```
