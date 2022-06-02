# MLOps-OSS-Analytics
## The Repository
This repository share the PowerBI dashboard that analyzing opensource in [MLOps](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/ai-machine-learning-mlops). You can get the following insights:
- Top 100 Contributors 
- Traffic 
- Contributor Commits 
- Pull Requests 
- Punch Card 
- Issues 

## Training Orchestration
Name | Overview | DashBoard | Others
-- | -- | -- | --
[Determined](https://github.com/determined-ai/determined) | Determined is an open-source deep learning training platform that makes building models fast and easy. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjc2ZWZmNzYtNjcxYi00NmQ5LTljODUtMTIwYzMxOTBhNjkyIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9&pageName=ReportSection5) | N/A
[Flyte](https://github.com/flyteorg/flyte) | Flyte is a structured programming and distributed processing platform that enables highly concurrent, scalable, and maintainable workflows for and . It is a fabric that connects disparate computation backends using a type-safe data dependency graph. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGU2N2RmYTUtNjQ0NS00MGY3LWFhODUtZjdkMjkyZTllNjkxIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | N/A
[Kubeflow](https://github.com/kubeflow/kubeflow) | Kubeflow the cloud-native platform for machine learning operations - pipelines, training and deployment. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGVkOGIzZmMtY2U3OC00ZDBjLTllYWYtNTk5OGRmNjhhMzgyIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) |  official docs at [kubeflow.org](http://kubeflow.org), [slack commnunity](https://www.kubeflow.org/docs/about/community/)
[OpenPAI](https://github.com/Microsoft/pai) | OpenPAI is an open-source platform that provides complete AI model training and resource management capabilities, it is easy to extend and supports on-premise, cloud, and hybrid environments on various scales. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWFkNzVmYzQtMDQxYi00ZTQ2LTg3ZjItMGY0YjQzNzY3ZDU0IiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) |  official docs at [openPAI Handbook](https://openpai.readthedocs.io/en/latest/index.html)
[Orchest](https://github.com/orchest/orchest) | Build data pipelines, the easy way! No framework. No YAML. Just write Python and R code in Notebooks. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTczYTlmMWUtZjkwNy00ZDcyLWExNWQtMDI0ZmVjZmMxMTZkIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) |  official docs at [Orchest](https://docs.orchest.io/en/stable/getting_started/when_to_use_orchest.html)
[Ploomber](https://github.com/ploomber/ploomber) | Ploomber is the fastest way to build data pipelines ⚡️. Use your favorite editor (Jupyter, VSCode, PyCharm) to develop interactively and deploy ☁️ without code changes (Kubernetes, Airflow, AWS Batch, and SLURM). | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjk2NDA4NTUtMWY1Ni00MGQ4LWE1YmMtYThlYWQ1ZDFkNmQ3IiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [Ploomber](https://docs.ploomber.io/en/latest/get-started/quick-start.html), [slack community](https://docs.ploomber.io/en/latest/community/index.html)
[Spock](https://github.com/fidelity/spock) | spock is a framework that helps users easily define, manage, and use complex parameter configurations within Python applications. It lets you focus on the code you need to write instead of re-implementing boilerplate code such as creating ArgParsers, reading configuration files, handling dependencies, implementing type validation, maintaining traceability, etc. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjhkM2UyYWUtNmE4OS00NmRlLThiYjYtMmIwNTNjNWM4Y2I1IiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [spock](https://fidelity.github.io/spock/) 
[Stoke](https://github.com/fidelity/stoke) | stoke is a lightweight wrapper for PyTorch that provides a simple declarative API for context switching between devices (e.g. CPU, GPU), distributed modes, mixed-precision, and PyTorch extensions. It places no restrictions on code structure for model architecture, training/inference loops, loss functions, optimizer algorithm, etc. Stoke simply 'wraps' your existing PyTorch code to automatically handle the necessary underlying wiring for all of the supported backends.This allows you to switch from local full-precision CPU to mixed-precision distributed multi-GPU with extensions (like optimizer state sharding) by simply changing a few declarative flags. Additionally, exposes configuration settings for every underlying backend for those that want configurability and raw access to the underlying libraries. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMmRhZmZjNjctZjI0My00NjAxLTg2OTAtNDBiYzM2ZjkwYTY3IiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9&pageName=ReportSection5) | official docs at [stoke](https://fidelity.github.io/stoke/docs/Home/)

## Model Monitoring
Name | Overview | DashBoard | Others
-- | -- | -- | --
[deepchecks](https://github.com/deepchecks/deepchecks) | Deepchecks is the leading tool for testing and for validating your machine learning models and data, and it enables doing so with minimal effort. Deepchecks accompanies you through various validation and testing needs such as verifying your data’s integrity, inspecting its distributions, validating data splits, evaluating your model and comparing between different models. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjk5Njc0MGEtODYzNS00NzczLTgxNWYtOTAzMTUxMTBjODAyIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [deepchecks](https://docs.deepchecks.com/stable/getting-started/welcome.html), [slack community](https://join.slack.com/t/deepcheckscommunity/shared_invite/zt-y28sjt1v-PBT50S3uoyWui_Deg5L_jg)
[Evidently AI](https://github.com/evidentlyai/evidently) | Evidently helps analyze and track data and ML model quality throughout the model lifecycle. You can think of it as an evaluation layer that fits into the existing ML stack.Evidently has a modular approach with 3 interfaces on top of the shared functionality. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTliNjY0NDMtODc4ZC00MjY1LWE5YmItMjZmOGU1YjdkMGUzIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [Evidently AI](https://docs.evidentlyai.com/), [discord community](https://discord.com/invite/xZjKRaNp8b)
[MLRun](https://github.com/mlrun/mlrun) | MLRun enables production pipeline design using a modular strategy, where the different parts contribute to a continuous, automated, and far simpler path from research and development to scalable production pipelines, without refactoring code, adding glue logic, or spending significant efforts on data and ML engineering. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTliNjY0NDMtODc4ZC00MjY1LWE5YmItMjZmOGU1YjdkMGUzIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [MLRun](https://docs.mlrun.org/en/latest/quick-start/quick-start.html), Feature Store is [exist](https://docs.mlrun.org/en/latest/feature-store/feature-store.html).
[whylogs](https://github.com/whylabs/whylogs) |whylogs is an open source library for logging any kind of data. With whylogs, users are able to generate summaries of their datasets (called whylogs profiles) which they can use to: 1. Track changes in their dataset. 2. Create data constraints to know whether their data looks the way it should. 3. Quickly visualize key summary statistics about their datasets. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjhjNWYzZmYtMzY5Zi00MDc3LWI5NDktMjVlZmViMDVmYzk0IiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9&pageName=ReportSection5) | official docs at [whylogs](https://docs.whylabs.ai/docs/), [slack community](https://communityinviter.com/apps/whylabs-community/rsqrd-ai-community)

## Model Testing
- (Comming Soon...)

## Model Serving
Name | Overview | DashBoard | Others
-- | -- | -- | --
[BentoML](https://github.com/bentoml/BentoML) | BentoML simplifies ML model deployment and serves your models at production scale. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjk5Njc0MGEtODYzNS00NzczLTgxNWYtOTAzMTUxMTBjODAyIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [BentoML](https://docs.bentoml.org/), [slack community](https://l.linklyhq.com/l/ktOh)
[Bodywork](https://github.com/bodywork-ml/bodywork-core) | Bodywork is a command line tool that deploys machine learning pipelines to Kubernetes. It takes care of everything to do with containers and orchestration, so that you don't have to. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjk5Njc0MGEtODYzNS00NzczLTgxNWYtOTAzMTUxMTBjODAyIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [Bodywork](https://bodywork.readthedocs.io)
[Cortex](https://github.com/cortexlabs/cortex) | Cortex makes it simple to deploy machine learning models in production. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTk1MThjYzUtYTAyYS00ZWM4LThmYjQtMjg1ZmFiYWZjZDFmIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [Cortex](https://docs.cortex.dev/), [slack community](https://cortex-dot-dev.slack.com/join/shared_invite/zt-n06vayo6-XNn~QpC_B3wHir8Au8CCLA#/shared-invite/email)
[KFServing](https://github.com/kserve/kserve) | KServe provides a Kubernetes Custom Resource Definition for serving machine learning (ML) models on arbitrary frameworks. It aims to solve production model serving use cases by providing performant, high abstraction interfaces for common ML frameworks like Tensorflow, XGBoost, ScikitLearn, PyTorch, and ONNX. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGZhODEwNzktZGJmOS00NmNlLTlhNDctODI5ZGNmMGZmZmE3IiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [KFServing](https://kserve.github.io/website/)
[OpenVINO™ Model Server](https://github.com/openvinotoolkit/model_server) | OpenVINO™ Model Server (OVMS) is a high-performance system for serving machine learning models. It is based on C++ for high scalability and optimized for Intel solutions, so that you can take advantage of all the power of the Intel® Xeon® processor or Intel’s AI accelerators and expose it over a network interface. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNWMxYTdjNWUtODMwNi00YWQ1LWExM2EtZWU0MzM2OTE4OWRlIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [OpenVINO™ Model Server](https://docs.openvino.ai/latest/ovms_what_is_openvino_model_server.html)
[Seldon Core](https://github.com/SeldonIO/seldon-core) | Seldon core converts your ML models (Tensorflow, Pytorch, H2o, etc.) or language wrappers (Python, Java, etc.) into production REST/GRPC microservices. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNWMxYTdjNWUtODMwNi00YWQ1LWExM2EtZWU0MzM2OTE4OWRlIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [Seldon Core](https://docs.seldon.io/projects/seldon-core/en/latest/index.html), [slack community](https://join.slack.com/t/seldondev/shared_invite/zt-vejg6ttd-ksZiQs3O_HOtPQsen_labg)
[Tensorflow Serving](https://github.com/tensorflow/serving) | TensorFlow Serving is a flexible, high-performance serving system for machine learning models, designed for production environments. It deals with the inference aspect of machine learning, taking models after training and managing their lifetimes, providing clients with versioned access via a high-performance, reference-counted lookup table. TensorFlow Serving provides out-of-the-box integration with TensorFlow models, but can be easily extended to serve other types of models and data. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjNkMjE2NDMtZGRlNS00YWMyLWI3YzgtZDBkOWI2MDE3NDJjIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [TensorFlow.org](https://www.tensorflow.org/), [slack community](https://tensor-flow-talk-invite.herokuapp.com/)
[TorchServe](https://github.com/pytorch/serve) | TorchServe is a flexible and easy to use tool for serving and scaling PyTorch models in production. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjNkMjE2NDMtZGRlNS00YWMyLWI3YzgtZDBkOWI2MDE3NDJjIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [TorchServe](https://pytorch.org/serve/)
[Triton Inference Server](https://github.com/pytorch/serve) | Triton Inference Server is an open source inference serving software that streamlines AI inferencing. Triton enables teams to deploy any AI model from multiple deep learning and machine learning frameworks, including TensorRT, TensorFlow, PyTorch, ONNX, OpenVINO, Python, RAPIDS FIL, and more. Triton supports inference across cloud, data center,edge and embedded devices on NVIDIA GPUs, x86 and ARM CPU, or AWS Inferentia. Triton delivers optimized performance for many query types, including real time, batched, ensembles and audio/video streaming. | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTJlNWMyNTMtMjNiOC00NTAxLWJhM2QtODAwYmU4OGJkNGZmIiwidCI6ImY3ZGFmMTViLTEzZjEtNGVlNC1iMWRmLTdlZDBhMjBhMGM5MCJ9) | official docs at [Triton Inference Server](https://developer.nvidia.com/nvidia-triton-inference-server)


- [BentoML](https://github.com/bentoml/BentoML)
- [Bodywork](https://github.com/bodywork-ml/bodywork-core)
- [Cortex](https://github.com/cortexlabs/cortex)
- [KFServing](https://github.com/kserve/kserve)
- [OpenVINO™ Model Server](https://github.com/openvinotoolkit/model_server)
- [Seldon Core](https://github.com/SeldonIO/seldon-core)
- [Tensorflow Serving](https://github.com/tensorflow/serving)
- [TorchServe](https://github.com/pytorch/serve)
- [Triton Inference Server](https://github.com/triton-inference-server/server)
## Data Versioning
- [DVC](https://github.com/iterative/dvc)
- [Pachyderm](https://github.com/pachyderm/pachyderm)
- [lakeFS](https://github.com/treeverse/lakeFS)
## Feature Store
- [Feast](https://github.com/feast-dev/feast)
- [Hopsworks](https://github.com/logicalclocks/hopsworks)
- [Feathr](https://github.com/linkedin/feathr)
## Experiment Tracking
- [Aim](https://github.com/aimhubio/aim)
- [CML](https://github.com/iterative/cml)
- [ClearML](https://github.com/allegroai/clearml)
- [MLFlow](https://github.com/mlflow/mlflow)
- [Neptune](https://github.com/neptune-ai/neptune-client)
- [Weights & Biases](https://github.com/wandb/client)

## Explainability
- [ELI5](https://github.com/TeamHG-Memex/eli5)
