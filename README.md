```python
from use_dir import use_dir

with use_dir('./bin'):
    # Do stuff here in the bin directory
    pass

# We are now back in our starting directory, even if an exception was thrown
```
