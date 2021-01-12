### Protocol Files for PyMAPDL Interface

This repository includes gRPC protocol files to interface with ANSYS
services.

### Build

Clone this repository and install build requirements, and build the
dpf protos package.

```
git clone https://github.com/pyansys/protos-mapdl
cd protos-mapdl
pip install -r requirements_build.txt
python package_grpc.py protos mapdl
```

These protobuf interface files can be used to develop a custom python
module to interface to DPF via gRPC.  Packages like `ansys.mapdl.core`
require the gRPC source and stub files to be pre-packaged as a Python
package for distribution.
