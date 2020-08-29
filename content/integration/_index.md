+++
title = "Integration"
chapter = true
weight = 2
pre = "<b>2. </b>"
+++

### Chapter 2: Integration

# Intro

We've got our data in S3 following the collection chapter. The question now is **how do we integrate our data with our machine learning pipeline?** We are going to do this with two primary mechanisms. A pipeline at the lower level using [TensorFlow Extended (TFX)](https://www.tensorflow.org/tfx) and one at the higher level using AWS managed services such as [Sagemaker](https://aws.amazon.com/sagemaker/), [Step Functions for Datascience](https://aws-step-functions-data-science-sdk.readthedocs.io/en/stable/), and [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler).