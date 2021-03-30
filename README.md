### Protocol Files for PyMAPDL Interface
This repository includes gRPC protocol files to interface with Mapdl's
gRPC interface.

### Build
To build the `ansys-mapdl-core` package locally, clone this
repository, install build requirements, and build the mapdl protos
package with

```
git clone https://github.com/pyansys/protos-mapdl
cd protos-mapdl
pip install -r requirements_build.txt
python package_grpc.py mapdl
```

These protobuf interface files can be used to develop a custom python
module to interface to MAPDL via gRPC.  Packages like `ansys-mapdl-core`
require the gRPC source and stub files to be pre-packaged as a Python
package for distribution.


### CI/CD

Packages are automatically generated from GitHub Actions for each commit and PR.  To download the automatically generated package, visit the actions tab at [Actions](https://github.com/pyansys/protos-mapdl/actions).
