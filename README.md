# PyO3 Extension Template

Template for starting PyO3 module projects with `cargo-generate`

Includes basic project setup and GitHub Actions workflow that:

- Builds wheels for Python 3.8-3.12 and PyPY for multiple platforms and architectures
- Provides testing with `tox`
- Uploads wheels and sdist to GitHub release and PyPI on tagged builds

To publish to PyPI, be sure to setup your [trusted publisher](https://docs.pypi.org/trusted-publishers/) configuration 
first.

