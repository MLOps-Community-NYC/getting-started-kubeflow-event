# isort Style Issues


> [isort](https://pycqa.github.io/isort/) is a Python utility / library to sort imports alphabetically, and automatically separated into sections and by type.

We have a number of isort issues in our [Issue Spreadsheet](https://lite.framacalc.org/dulyrft6pc-a78e). They are identified by the `Style: isort` category in the category column.

## Contributing with isort code

Each isort issue in the spreadsheet has the format.

```
isort: directory_path/
```
or
```
isort: path/to/file.py
```

For example:
```
isort: kubeflow/training-operator/sdk/python/kubeflow/training/api/...
```
or
```
isort: kubeflow/training-operator/sdk/python/kubeflow/training/api_client.py 
```

## How to create a PR for an isort issue

1. Pick an isort issue from the [Issue Spreadsheet](https://lite.framacalc.org/dulyrft6pc-a78e) and **reserve it by putting your team name in the Claimed By column**.

1. Follow the [isort Documentation](https://pycqa.github.io/isort/) to find a way to install isort locally.

1. Use isort to resolve the issue for **that path only**.

1. Follow the README.md PR section to create a PR.

> 🔥 Wouldn't it be easier to just do all the python files in one PR? <br><br> Yes, for sure. However we wanted to provide a handful of more accessible opportunities. So please keep your PR to just the directory path in the spreadsheet.

