# PyO3 Extension Template

Template for starting PyO3 module projects with `cargo-generate`. It works much like `maturin new` and `maturin generate-ci`, 
but aims to provide additional options and flexibility and work with the `cargo-generate` toolset (which, for me, is how I prefer to start projects in Rust Rover).

Includes basic project setup and GitHub Actions workflow that:

- Builds wheels for Python 3.8-3.12 and PyPy for multiple platforms and architectures
- Repairs wheels for proper packaging of linked dependencies (e.g., using `delocate`, `auditwheel`, or `delvewheel`)
- Tests your rust code using `cargo test` and tests your generated extension module using `tox`
- Uploads wheels and sdist to GitHub release and PyPI on tagged builds

To publish to PyPI, be sure to setup your [trusted publisher](https://docs.pypi.org/trusted-publishers/) configuration 
first.

This project is usable, but still in the early stages of development. Check the [issues](https://github.com/spyoungtech/pyo3-extension-template/issues) for 
details of known bugs and planned features or to request a new feature or report a bug.
