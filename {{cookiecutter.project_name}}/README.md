# {{ cookiecutter.project_name }}

[![Build Status](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/workflows/Rust%20CI/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/actions)
[![crates.io](https://img.shields.io/crates/v/{{ cookiecutter.crate_name }}.svg)](https://crates.io/crates/{{ cookiecutter.crate_name }})
[![Documentation](https://docs.rs/{{ cookiecutter.crate_name }}/badge.svg)](https://docs.rs/{{ cookiecutter.crate_name }})
[![{{ cookiecutter.license }} licensed](https://img.shields.io/github/license/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }})](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/blob/master/LICENSE)
[![codecov](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/branch/master/graph/badge.svg)](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }})

## Usage

Add the following to your `Cargo.toml`:

```toml
[dependencies]
{{ cookiecutter.project_name }} = "0.1.0"
```

## License

The project is licensed under the [{{ cookiecutter.license }}](LICENSE).

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the project by you shall be licensed as {{ cookiecutter.license }}, without any
additional terms or conditions.

## Developing

### `pre-commit`

We encourage contributors to use predefined [`pre-commit`](https://pre-commit.com/)
hooks — to install them in your local repo, make sure you have `pre-commit`
installed and run
```shell
pre-commit install
```
