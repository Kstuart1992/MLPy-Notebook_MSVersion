# Machine Learning with Python

> a repository of personally hosted - supplied examples, can be found at https://github.com/kstuart1992/contrb/

Welcome to Part 2 of the AI Logs:
Azure Machine Learning Python SDK will be our platform for this go-

## Getting started

Recommended for use in an Azure Machine Learning [Compute Instance](https://docs.microsoft.com/azure/machine-learning/concept-compute-instance), where you can run them without any additional set up. I will include concepts for alternitive methods when I have extra time. I'll make sure to include notes on how to do all these experiments on Azure for free* given you don't leave it running and read the doc's lol

For the easiest "non-MS ver" is a local development environment with a few `azureml` packages installed. (you can configure as needed) please be sure to check the ml-flow set-up as well, okay getting started - Easy way first:

Install the `azureml.core` Python package:

```sh
pip install azureml-core
```

Install additional packages* or start off basic:

```sh
pip install azureml-mlflow
pip install azureml-dataset-runtime
pip install azureml-automl-runtime
pip install azureml-pipeline
pip install azureml-pipeline-steps
...
```

Then try out one of the [quickstarts](tutorials/compute-instance-quickstarts).

## Contributing

This repository is a push-only mirror *in most places- I'll touch base on these where appropriate. 

In those cases, pull requests are ignored.

## Code of Conduct

These projects have a few lic. the majority adopt the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). 
Please see the [code of conduct](CODE_OF_CONDUCT.md) for details. All others will be included with the file and include notes.

## Reference

Microsoft has some additional documents found below - mainly on how to get started and if your paying for Azure, what step and concepts to those intergrations are involved.

- [Documentation](https://docs.microsoft.com/azure/machine-learning)

