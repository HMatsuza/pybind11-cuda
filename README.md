# pybind11-cuda

Compiles out of the box with cmake 

Numpy integration 

C++ Templating for composable kernels with generic data types 

Originally based on https://github.com/torstem/demo-cuda-pybind11

# Prerequisites

Cuda installed in /usr/local/cuda 

Python 3.7 or greater 

Cmake 3.6 or greater 

# To build 

```source install.bash``` 
If you want to use specific Python3 binary, modify line 4 in install.bash:
```cmake .. -DPYTHON_EXECUTABLE=/path/to/executable```


Test it with 
```python3 test_mul.py``` 
 
