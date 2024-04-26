# Getting Started with Open Source MLOps
## Kubeflow

Thanks for joining us this evening! Here is a quick one-pager for keeping up to date with this evenings event.

> [opensource.guide](https://opensource.guide/) is a great resource for starting in the world of Open Source Contribution.

_section on Alex's talk?_

## What is Kubeflow?

Kubeflow is a cloud-native platform for machine learning operations - pipelines, training and deployment.

[Documentation](https://www.kubeflow.org/) - [Code](https://github.com/kubeflow/kubeflow)

Today we will be jumping into the Kubeflow Training Operator!

## What is Kubeflow Training Operator?

[Kubeflow Training Operator](https://github.com/kubeflow/training-operator) is a Kubernetes-native project for fine-tuning and scalable distributed training of machine learning (ML) models created with various ML frameworks such as PyTorch, Tensorflow, XGBoost, MPI, Paddle and others.

Training Operator allows you to use Kubernetes workloads to effectively train your large models via Kubernetes Custom Resources APIs or using Training Operator Python SDK.

[Documentation](https://www.kubeflow.org/docs/components/training/
) - [Code](https://github.com/kubeflow/training-operator)

# Setting Up Your Environment

## Pre-requisites

[] A Personal (Github Account)[https://github.com/]
[] [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## 1. Create a fork of Training Operator

1. Go to [github.com/kubeflow/training-operator](https://github.com/kubeflow/training-operator)
2. Create a Fork in your personal Github account.

## 2. Setup your local environment

1. Follow the [Developer Guide](https://github.com/kubeflow/training-operator/blob/master/docs/development/developer_guide.md) to setup your local environment.

## 3. Pick an issue

We have three separate themes of issues available today:
* [Code Style](issues/style.md) (Easier Difficulty)
* [Unit Tests](issues/unit-tests.md) (Medium Difficulty)
* [Other](issues/other.md)

1. Head to [this spreadsheet](https://lite.framacalc.org/dulyrft6pc-a78e) and pick and issue that looks interesting to you - pick one that hasn't been claimed by someone.
2. Reserve the issue by putting your name in the `Claimed By` column. This will prevent another person picking up the same issue.


--

# Live PR Reviews

Steps for signing your PR up for a live review