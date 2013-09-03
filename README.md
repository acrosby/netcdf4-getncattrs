netcdf4-getncattrs
==================

```python
from getncattrs import __call__ as getncattrs
from netCDF4 import Dataset

nc = Dataset(file)
attribute_dict = getncattrs(nc)
```