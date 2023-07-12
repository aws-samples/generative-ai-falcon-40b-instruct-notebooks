### Generative Artificial Intelligence Engineering Notebooks

The project provides Generative Artificial Intelligence engineering notebook samples. The project demonstrates how to deploy Amazon SageMaker JumpStart SDK and Falcon 40B Instruct language model to apply different levels of cutomizations such as decoding strategies and Retrieval-Augmented Generation (RAG).

The following Amazon SageMaker Studio notebooks are available in this repository:
- `SM-JumpStart-Decoding-Falcon40B-G5.ipynb` demonstrates how to generate text using different decoding strategies with [Amazon SageMaker JumpStart SDK](https://sagemaker.readthedocs.io/en/v2.82.0/overview.html#use-prebuilt-models-with-sagemaker-jumpstart) and [Falcon-40B-Instruct model](https://huggingface.co/tiiuae/falcon-40b-instruct).

- `SM-JumpStart-RAG-Kendra-Falcon40B.ipynb` demonstrates how to use [SageMaker](https://sagemaker.readthedocs.io/en/stable/) and [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) SDKs to generate text using the Retrieval-Augmented Generation (RAG) pattern. The notebook implements semantic search using [Amazon Kendra](https://aws.amazon.com/kendra/) enterprise search service. The language model used for text generation is [Falcon-40B-Instruct](https://huggingface.co/tiiuae/falcon-40b-instruct).

To open a Jupyter Notebook using Amazon SageMaker, consider the two steps below:
1. [Create or Open an Amazon SageMaker Studio Notebook](https://docs.aws.amazon.com/sagemaker/latest/dg/notebooks-create-open.html).
2. [Clone this Git Repository in Amazon SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-tasks-git.html).

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

