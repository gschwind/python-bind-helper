
python-bind-helper is a C++11 header library that help to create numpy ufunction. The
idea is to bind function from their signature. Allowed signature are:
* basetype func(basetype, ...)
* tuple<basetype, ...> func(basetype, ...)
where basetype can be int, double, float or long int.

The setup.py is provided to build a dummy python module to test the library.

