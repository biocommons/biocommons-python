This project exists only to ensure that the top-level biocommons
namespace is correctly declared as a namespace package.

This trivial package was pushed to pypi in order to reserve the
biocommons namespace (contributions are welcome!).


Steps:

```
pyvenv venv
source venv/bin/activate
pip install wheel
python setup.py register
python setup.py sdist bdist bdist_egg bdist_wheel upload
```

