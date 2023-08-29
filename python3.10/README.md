This repository contains patched Python standard libraries to be used with Score-P's Python bindings.

To use them clone this repository and prepend it to your `PYTHONPATH`.

```
    export PYTHONPATH=`realpath scorep_python_multiprocessing/python3.10`:$PYTHONPATH
```

Please make sure, to use the multiprocessing branch of the Score-P Python bindings


Please also make sure to set the `spawn` method:
```
multiprocessing.set_start_method("spawn")
