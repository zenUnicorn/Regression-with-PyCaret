# Regression-with-PyCaret
Implementation of regression in PyCaret

> let's install pycaret

```python
!pip install pycaret
```


The first issue I faced was `Referenced from: /Library/Frameworks/Python.framework/Versions/3.9/lib/python3.9/site-packages/lightgbm/lib_lightgbm.so`

Solution: Just install libomp using `brew`

```python
brew install libomp
```

> To install brew:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Full documentation [here](https://pycaret.gitbook.io/docs/get-started/quickstart)


