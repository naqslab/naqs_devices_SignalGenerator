# naqs_devices_SignalGenerator

## Directory structure

```text

└── naqs_devices_SignalGenerator/
    ├── .gitignore
    ├── pyproject.toml
    ├── README.md
    ├── LICENSE.txt
    ├── CITATION.cff
    ├── docs/
    │   ├── conf.py
    │   ├── make.bat
    │   ├── Makefile
    │   └── index.rst
    └── src/naqs_devices/ # note: must be same as in the parent naqs_devices repo to be in the same namespace
        └── SignalGenerator/
            ├── __init__.py
            ├── BLACS/
            │       ├── __init__.py
            │       ├── HP_8642A.py
            │       ├── HP_8643A.py
            │       ├── HP_8648.py
            │       ├── KeysightSigGens.py
            │       ├── RS_SMA100B.py
            │       ├── RS_SMA100A.py
            │       ├── RS_SMHU.py
            │       ├── SRS_SG380.py
            ├── blacs_tabs.py
            ├── blacs_workers.py
            ├── labscript_devices.py
            ├── Models.py
            └── register_classes.py
```

## How to document your device

To work within the labscript paradigm, we enforce that you write all
specification related documentation in the top-level README.md (here). Then,
any API related documentation should go in the `docs/index.rst`.
