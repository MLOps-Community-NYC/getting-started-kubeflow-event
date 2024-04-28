# Style Issues

Checkout the [Issue Spreadsheet](https://docs.google.com/spreadsheets/d/1sYgp_oqdnchSPRbc7lIsoM71J4dvCq66pIDwpeRkyL8).

The **Type** column the following style categories.
* `Style: isort` - isort PRs

Each style category has some tips below.

# isort Issues

> isort is a Python utility / library to sort imports alphabetically, and automatically separated into sections and by type.

[isort Documentation](https://pycqa.github.io/isort/)

Each isort issue has line in this format.

```
<filename> Imports are incorrectly sorted and/or formatted.
```

For example:
```
kubeflow/training-operator/docs/release/release.py Imports are incorrectly sorted and/or formatted.
```

## How to create a PR for an isort issue

1. Follow the [isort Documentation](https://pycqa.github.io/isort/) to find a way to install isort locally.
2. Pick an isort issue from the [Issue Spreadsheet](https://docs.google.com/spreadsheets/d/1sYgp_oqdnchSPRbc7lIsoM71J4dvCq66pIDwpeRkyL8) and **reserve it by putting your name in the Claimed By column**.
3. Use isort to resolve the issue.
4. Create a PR from your fork branch to Training Operator.

