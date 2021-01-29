1. **Implement a Python function that “inverts” a dictionary where keys are string, and values are integers.**

So that dictionary {‘k1’: v1, ‘k2’: v2} would become {v1: ’k1’, v2: ‘k2’}

```python
def invert_dict(d):
    inverted_d = {v: k for k, v in d.items()}
    return inverted_d
```

