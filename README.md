# Equinor Terraform Baseline

[![GitHub contributors](https://img.shields.io/github/contributors/equinor/terraform-baseline)](https://github.com/equinor/terraform-baseline/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues/equinor/terraform-baseline)](https://github.com/equinor/terraform-baseline/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/equinor/terraform-baseline)](https://github.com/equinor/terraform-baseline/pulls)
[![GitHub License](https://img.shields.io/github/license/equinor/terraform-baseline)](LICENSE)

Terraform Baseline is:

- 📝 A set of best practices for creating reusable Terraform modules using the Azure provider.
- 📚 A library of reusable Terraform modules that have been created using these best practices.

Hosted in [GitHub Pages](https://equinor.github.io/terraform-baseline/).

## Development

### Windows

1. Install Python:

    ```console
    winget install --id "Python.Python.3.12" -e
    ```

1. Restart your machine to complete the installation.

1. Create and activate virtual environment:

    ```console
    python -m venv "venv"
    . "venv\Scripts\activate"
    ```

1. Install requirements:

    ```console
    python -m pip install --upgrade pip
    pip install -r "requirements.txt"
    ```

1. Run development server:

    ```console
    mkdocs serve
    ```

### Container

1. Read [this document](https://code.visualstudio.com/docs/devcontainers/containers).

1. Open this repository in the development container.

1. Run the development server:

    ```console
    mkdocs serve
    ```

## Contributing

See [Contributing guidelines](CONTRIBUTING.md).

## License

This project is licensed under the terms of the [MIT license](LICENSE).
