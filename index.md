FreeOpcUa is a project to implement an open-source (LGPL/GPL) OPC-UA stack and associated tools. 

Currently FreeOpcUa is composed of
* A LGPL C++ library to develop server and client OPC-UA applications: https://github.com/FreeOpcUa/freeopcua
  * Python bindings can be found in the [python](https://github.com/FreeOpcUa/freeopcua/tree/master/python) subdirectory
* A synchronous LGPL Python OPC-UA client and server library (written entirely in Python): https://github.com/FreeOpcUa/python-opcua
  * Install using `pip install opcua`
  * Command line tools can be found in the [tools](https://github.com/FreeOpcUa/python-opcua/tree/master/tools) subdirectory ([doc](https://github.com/FreeOpcUa/python-opcua#documentation))
* An asynchronous LGPL Python OPC-UA client and server library (using [asyncio](https://docs.python.org/3/library/asyncio.html) aka. [PEP 3156](https://www.python.org/dev/peps/pep-3156/)): https://github.com/FreeOpcUa/opcua-asyncio

* A GPL Python GUI client: https://github.com/FreeOpcUa/opcua-client-gui
  * Install using `pip install opcua-client`
* A GPL Python GUI to create OPC-UA nodes and save them to xml: https://github.com/FreeOpcUa/opcua-modeler
  * Install using `pip install opcua-modeler`

* Mailing list: https://groups.google.com/forum/#!forum/freeopcua
* Source code: https://github.com/FreeOpcUa

Screenshot of client GUI:


![Screenshot](/screenshot.png?raw=true "Screenshot")

Screenshot of modeler:


![Screenshot](/screenshot-modeler.png?raw=true "Screenshot")
