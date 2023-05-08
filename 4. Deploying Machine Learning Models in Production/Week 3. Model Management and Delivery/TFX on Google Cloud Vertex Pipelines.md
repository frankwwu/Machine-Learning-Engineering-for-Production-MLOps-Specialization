# TFX on Google Cloud Vertex Pipelines

Tensorflow Extended ([TFX](https://www.tensorflow.org/tfx)) is Google's end-to-end platform for training and deploying TensorFlow models into production. TFX pipelines orchestrate ordered runs of a sequence of components for scalable, high-performance machine learning tasks in a directed graph. It includes pre-built and customizable components for data ingestion and validation, model training and evaluation, as well as model validation and deployment. TFX is the best solution for taking TensorFlow models from prototyping to production with support for on-prem environments and in the cloud such as Google Cloud's Vertex AI Pipelines.

Vertex AI Pipelines helps you to automate, monitor, and govern your ML systems by orchestrating your ML workflow in a serverless manner and storing your workflow's artifacts using Vertex ML Metadata.

In this lab, you will automate the development and deployment of a TensorFlow classification model which predicts the species of penguins. To do this, you will:

1. Create a TFX Pipeline using TFX APIs.

2. Define a pipeline runner that uses Vertex Pipelines together with the Kubeflow V2 DAG runner

3. Deploy and monitor a TFX pipeline on Vertex Pipelines.

Note: FAQs about all assignments are consolidated on [this thread](https://community.deeplearning.ai/t/mlep-c4-assignment-troubleshooting-tips/42580) in our community. If you haven't joined yet, kindly go back to [this item](https://www.coursera.org/learn/deploying-machine-learning-models-in-production/ungradedLti/la9TZ/important-have-questions-issues-or-ideas-join-our-community-on-discourse) for instructions on how to get access.

