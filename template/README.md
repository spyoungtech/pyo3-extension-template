# {{project-name}}


## Installation

```python
pip install {{project-name}}
```

### Build

You can build locally using `maturin` or using `python -m build` (which in turn calls maturin)

```python
pip install build
python -m build
```

### Testing

Testing can be done with `tox`

```python
pip install tox
tox -e py
```

Test requirements (installed automatically in tox run) are defined in `tests/test-requirements.txt`
