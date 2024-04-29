# [Optional] Pre-Event Setup

Hello Attendee 👋

We are really excited to see you at the "Getting Started with MLOps Open Source" event. 

We're going to be diving into the Kubeflow Training Operator code.

In order to make your experience smoother, you can get a head start by setting up your Kubeflow Training Operator environment.

* [What is Kubeflow](#what-is-kubeflow)
* [What is Kubeflow Training Operator](#what-is-kubeflow-training-operator)
* [Setting up your environment](#setting-up-your-environment)


## What is Kubeflow?

Kubeflow is a cloud-native platform for machine learning operations - pipelines, training and deployment.

[Documentation](https://www.kubeflow.org/) - [Code](https://github.com/kubeflow/kubeflow)

> 📺 IBM created this [awesome 4 minute explainer video](https://www.youtube.com/watch?v=Dbwj-NHnHfw).

Today we will be jumping into the Kubeflow Training Operator!

## What is Kubeflow Training Operator?

[Kubeflow Training Operator](https://github.com/kubeflow/training-operator) is a Kubernetes-native project for fine-tuning and scalable distributed training of machine learning (ML) models created with various ML frameworks such as PyTorch, Tensorflow, XGBoost, MPI, Paddle and others.

Training Operator allows you to use Kubernetes workloads to effectively train your large models via Kubernetes Custom Resources APIs or using Training Operator Python SDK.

[Documentation](https://www.kubeflow.org/docs/components/training/
) - [Code](https://github.com/kubeflow/training-operator)

## Setting up your environment

The developer guide for Kubeflow Trianing Operator is [here](https://github.com/kubeflow/training-operator/blob/master/docs/development/developer_guide.md).

We recommend:
1. Creating a [Github Account](https://github.com/) - so that you can create Forks and PRs. 
1. Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
1. [Installing the prerequisites.](https://github.com/kubeflow/training-operator/blob/master/docs/development/developer_guide.md)
1. [Building an Operator](https://github.com/kubeflow/training-operator/blob/master/docs/development/developer_guide.md#building-the-operator)
2. [Running the example operator locally.](https://github.com/kubeflow/training-operator/blob/master/docs/development/developer_guide.md)