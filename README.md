### Large Language Model Customization Notebooks

This repository provides a collection of Generative AI engineering notebooks that demonstrate how to use Amazon SageMaker JumpStart SDK to customize Large Language Models (LLMs). The notebooks show using the Falcon model variants how to apply basic levels of inference customization such as: decoding strategies, prompting techniques, and Retrieval-Augmented Generation. The notebooks are designed to be easy to deploy and follow, making them a good resource for learning about LLM inference customization.

The following Amazon SageMaker Studio notebooks are available in this repository:
- `LLM-Custom-Decoding-Falcon40B-G5.ipynb` demonstrates how to generate text using different decoding strategies with [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-40B-Instruct model](https://huggingface.co/tiiuae/falcon-40b-instruct).
- `LLM-Custom-Prompting-Falcon40B.ipynb` demonstrates how to generate text using prompting engineering techniques with [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-40B model](https://huggingface.co/tiiuae/falcon-40b).
- `LLM-Custom-RAG-Kendra-Falcon40B.ipynb` demonstrates how to use [SageMaker](https://sagemaker.readthedocs.io/en/stable/) and [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) SDKs to generate text using the Retrieval-Augmented Generation (RAG) pattern. The notebook implements semantic search using [Amazon Kendra](https://aws.amazon.com/kendra/) enterprise search service. The language model used for text generation is [Falcon-40B-Instruct](https://huggingface.co/tiiuae/falcon-40b-instruct).

To open a Jupyter Notebook using Amazon SageMaker, consider the two steps below:
1. [Create or Open an Amazon SageMaker Studio Notebook](https://docs.aws.amazon.com/sagemaker/latest/dg/notebooks-create-open.html).
2. [Clone this Git Repository in Amazon SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-tasks-git.html).

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

