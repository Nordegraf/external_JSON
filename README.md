# external_JSON
Third party tools for JSON. Consult individual licenses for details about packages.

To install this software:


1) Install via ughub. This creates ``externals/JSONForUG4``

```
ughub install JSONForUG4
```
2) Before the first execution, we need populate ``externals/JSONForUG4`` with submodules:

```
ughub git submodule init --- JSONForUG4
ughub git submodule update --- JSONForUG4
```

3) Now you have external libraries installed. Configure UG4 with CMakeFlags '-DUSE_JSON' and recompile!

