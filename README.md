# Notebooks Template

> [!IMPORTANT]
> Adapt the headline and description text to your needs.

This repo is a template for repositories that contain merely jupyter notebooks.
Please create a new repository for each topic using this template to keep things small and simple (avoiding dependency conflicts).

## Usage

We use [`uv`](https://docs.astral.sh/uv) to manage the dependencies (because it is faster and simpler than `pipenv` or `hatch`).

To create the local Python environment use 

```sh
uv sync
```

Then to run JupyterLab within the environement use

```sh
uv run jupyter lab
```

To add a dependency use (the `"` are important)

```sh
uv add "package-name~=min-version"
```

## Contents

> [!IMPORTANT]
> List and explain here the purpose of each notebook.

### `Example.ipynb`

This notebook contains just a stupid example.

## License

This repository is licensed under the terms of the [MIT License](LICENSE).

> [!IMPORTANT]
> Adapt the metadata in `pyproject.toml` to your needs.
