# Unit Tests

There are a number of opportunities to improve the Unit Tests for the Training Operator Python SDK.

## Python Test Setup

1. Visit the [Python SDK README](https://github.com/kubeflow/training-operator/tree/master/sdk/python) for some documentation on setting up your python environment.

    > `pyenv` Users: Use `python setup.py install` to install the dependencies into your `pyenv` environment.

2. Install the Pytest Package

    e.g. `pip install pytest`

3. Run the training_client_test.py tests with the following pytest command.

    `pytest ./sdk/python/kubeflow/training/api/training_client_test.py`

4. You should see the tests pass.

## Contribution Opportunities

The class `TrainingClient` in the file [sdk/python/kubeflow/training/api/training_client.py](https://github.com/kubeflow/training-operator/blob/master/sdk/python/kubeflow/training/api/training_client.py) 
is a High Level API class for running training jobs with PyTorch.

The test file for that file is here: [sdk/python/kubeflow/training/api/training_client_test.py](https://github.com/kubeflow/training-operator/blob/master/sdk/python/kubeflow/training/api/training_client_test.py).

Currently the test file only covers the function `TrainingClient.create_job`.

Meaning the following functions are currently untested:

* `get_job`
* `list_jobs`
* `get_job_conditions`
* `is_job_created`
* `is_job_running`
* `is_job_restarting`
* `is_job_succeeded`
* `is_job_failed`
* `wait_for_job_conditions`
* `get_job_pods`
* `get_job_pod_names`
* `get_job_logs`
* `update_job`
* `delete_job`

**This is your groups chance to contribute a test for one of these functions.**

Head over to the [contribution spreadsheet](https://lite.framacalc.org/dulyrft6pc-a78e) to claim one of the functions to create a test for.
