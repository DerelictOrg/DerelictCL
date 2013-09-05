DerelictOpenCL
==============

*Warning: this an unofficial Derelict binding.*

A dynamic binding to [OpenCL](http://www.khronos.org/opencl/) for the D Programming Language.

For information on how to build DerelictCL and link it with your programs, please see the post [Building and Using Packages in DerelictOrg](http://dblog.aldacron.net/forum/index.php?topic=841.0) at the Derelict forums.

For information on how to load the OpenCL library via DerelictCL, see the page [DerelictUtil for Users](https://github.com/DerelictOrg/DerelictUtil/wiki/DerelictUtil-for-Users) at the DerelictUtil Wiki. In the meantime, here's some sample code.

```D
import derelict.opencl.cl;

void main() {
    // Load the OpenCL library.
    DerelictCL.load();
    
    // Now OpenCL functions can be called.
    ...
}
```
