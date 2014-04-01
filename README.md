## qPython 1.0 Beta

qPython is a Python library providing support for interprocess communication between Python and kdb+ processes, it offers:
- Synchronous and asynchronous queries
- Convenient asynchronous callbacks mechanism
- Support for kdb+ protocol and types: v3.0, v2.6, v<=2.5
- Uncompression of the IPC data stream
- Internal representation of data via numpy arrays (lists, complex types) and numpy data types (atoms)
- Supported on Python 2.7 and numpy 1.8