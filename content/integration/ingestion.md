+++
title = "Ingestion (TFX)"
chapter = true
weight = 1
pre = "<b>1. </b>"
+++

### Chapter 2: Integration

# Tensorflow Extended (TFX)

TFX has [standard built-in components](https://www.tensorflow.org/tfx/guide#tfx_standard_components) for each stage of a typical ML pipeline. In this chapter we'll be working with `ExampleGen`. The primary component at the start of a TFX pipeline design to ingest data, split the data in appropriate datasets, and convert the dataset into [tf.Examples data structures](https://www.tensorflow.org/tutorials/load_data/tfrecord). Which is essentially a {"string": tf.train.Feature} mapping.

- [x] Data Ingestion ([ExampleGen](https://www.tensorflow.org/tfx/guide/examplegen))
- [ ] Data Validation ([StatisticsGen](https://www.tensorflow.org/tfx/guide/statsgen), [SchemaGen](https://www.tensorflow.org/tfx/guide/schemagen), [ExampleValidator](https://www.tensorflow.org/tfx/guide/exampleval))
- [ ] Data Preprocessing ([Transform](https://www.tensorflow.org/tfx/guide/transform))
- [ ] Model Training ([Trainer](https://www.tensorflow.org/tfx/guide/trainer), [Tuner](https://www.tensorflow.org/tfx/guide/tuner))
- [ ] Model Analysis and Validation ([Evaluator](https://www.tensorflow.org/tfx/guide/evaluator))
- [ ] Model Deployment ([Model Server](https://www.tensorflow.org/tfx/serving/serving_advanced))





