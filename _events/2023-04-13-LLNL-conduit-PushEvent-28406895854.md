---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1194526?"
user: cyrush
date: 2023-04-13
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/commit/55d3a9e465a809dbab0b8a26d304d60fd9ae0909
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/cyrush' target='_blank'>cyrush</a> pushed to <a href='https://github.com/LLNL/conduit' target='_blank'>LLNL/conduit</a>

<small>Python:  ABI3 compatibility changes (#1102)

* cmake: create interface library that holds Py_LIMITED symbol

The new cmake option CONDUIT_PYTHON_USE_LIMITED_API can be used to toggle the use of limited API.
The Python version is set to 3.11 since it is required for the Py_Buffer objects.

* conduit_python: Include missing header for Python 3.11

* BUGFIX: PyUnicode_Decode expects size in bytes

while PyUnicode_FromKindAndData expects size of units of bytes

* Use Limited API: PyList_Size->PyList_GET_SIZE

* Use Limited API: PyTuple_GET_ITEM -> PyTuple_GetItem

* Use Limited API: PyTuple_GET_SIZE -> PyTuple_Size

* Use Limited API: PyList_GET_ITEM -> PyList_GetItem

* Use Limited API: PyFloat_AS_DOUBLE -> PyFloat_AsDouble

* Use Limited API: PyBytesAS_STRING -> PyBytes_AsString

* Provide alternative implementation for PyUnicode_FromKindAndData

* Simplify PyConduit_Node_print_detailed

Just use std::fprintf, no need to construct a python string just to print it to stdout.
Also, PyObject_Print is not part of the Stable API.

* Use PyType_GenericAlloc instead of tp_alloc

In the limited python API the PyTypeObject is considered an opaque pointer
we use PyType_GenericAlloc instead which is part of the Stable ABI.

* Use PyType_GetSlot to access tp_free

needed since PyTypeObject is an opaque struct in the limited api.

* conduit_python: Prepare module for heap allocated types

*_TYPE objects will be saved in module state and initialized in
PyInit_conduit_python method.

* Convert PyConduit_DataType_TYPE to heap allocated type

* Convert PyConduit_Generator_TYPE to heap allocated type

* Convert PyConduit_Schema_TYPE to heap allocated type

* Convert PyConduit_NodeIterator_TYPE to heap allocated type

* Convert PyConduit_Node_TYPE to heap allocated type

* Convert PyConduit_Endianess_TYPE to heap allocated type

* conduit_relay_io_python: Prepare module for heap allocated types

* Convert PyRelay_IOHandle_TYPE to heap allocated type

* conduit_replay_web_python: prepare for heap allocated types

* Convert PyRelay_WebServer_TYPE to heap allocated type

* Convert PyRelay_WebSocket_TYPE to heap allocated type

* conduit_relay_mpi_python: Prepare for heap allocated types

* Convert PyRelay_MPI_Request_TYPE to heap-allocated type</small>

<a href='https://github.com/LLNL/conduit/commit/55d3a9e465a809dbab0b8a26d304d60fd9ae0909' target='_blank'>View Commit</a>