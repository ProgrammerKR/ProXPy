# ProXPy v1.0.0

**ProXPy** is a lightweight Python-based language derived from Python 2.7.16 — but with a cleaner, more structured syntax inspired by C/C++, JavaScript, and modern programming principles.

## Why ProXPy?

Python is powerful, but its strict indentation rules can be inconvenient, especially in larger projects.  
**ProXPy** removes the dependency on indentation for code blocks and introduces familiar braces and semicolons to make the code more readable, consistent, and beginner-friendly.

---

## Key Differences from Python

| Feature | Python | ProXPy |
|--------|--------|--------|
| Code blocks | Indentation-based | `{}` braces |
| Statement end | Newline | Semicolon `;` |
| `None`, `True`, `False` | `None`, `True`, `False` | `nil`, `true`, `false` |
| Function keyword | `def` | `function` |
| `self` keyword | Explicit in methods | Implicit, replaced by `this` |
| Class reference | `self`, `cls` | `this`, `cls` |
| `try-except` | `except:` (optional expression) | `except Exception {}` (expression required) |

---

## Syntax Comparison

### Python

```python
try:
  if True:
    print "If True"
except:
  print "except could with none parameter"

class Base(object):
  def __init__(self):
    print "Class Base"
    self.value = None

  def show(self):
    print self.value
```

### ProXPy:

```
    try 
    {
      if true
      {
        print "If true";
      }
    } 
    except Exception 
    {
      print "except must have one expression...";
    }
    
    class Base(object)
    {
      function __init__()
      {
        print "Class Base";
        this.value = nil;
      }
      
      function show()
      {
        print this.value;
      }
    }
```
