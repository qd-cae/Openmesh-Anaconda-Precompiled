
# OpenMesh for Python3

This repo contains precompiled python libraries from OpenMesh. A compiled python C extension has the pattern **.pyd*. I compiled it for:

 - Python 3.5.3 :: Anaconda 4.0.0 (64-bit)
 - Python 3.6.0 :: Anaconda 4.3.0 (64-bit)

 Either place the **.pyd* in the same file as the library script or simply copy it to:

```
your/path/to/Anaconda/Lib/site-packages
```

You can then import the library from any script:

```python
from openmesh import *
```
