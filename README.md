# **Dataset Preparation for Transformers Fine-tuning**


[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lDKJoIBd3ISArIgLU2AtntuLgkC6cZdZ?usp=sharing)


The **Dataset Prep Transformers** package simplifies the process of preparing datasets for fine-tuning or training various large language models available in the Hugging Face Transformers library. Whether you're using a model from the Hugging Face repository or have your own dataset, this package streamlines the data integration for a seamless training experience.

## Features

- Easily integrate your dataset with Hugging Face Transformers models for training or fine-tuning.
- Specify the model repository ID and dataset from the Hugging Face library to automatically fetch and configure the data.
- Seamlessly incorporate your custom dataset by providing it as input to the package.

---

# **Install the yDataprep**
[![PyPI](https://img.shields.io/pypi/v/package-name.svg)](https://pypi.org/project/yDataPrep/)




To leverage the powerful features of the Hugging Face Transformers library for effortless dataset integration and model training using ***yDataPrep***, you can either visit the PyPI page by clicking on the provided link or install the package directly from your command prompt or terminal using the command below.




```
pip install yDataPrep
```

---

# **How to use yDataPrep for 🚂?**



```
data = dp.dataprep(model_name="EleutherAI/pythia-70m",dataset_name="fka/awesome-chatgpt-prompts")
data
```

1. **Modularity**: By utilizing the ***yDataPrep*** package, you're adopting a modular and organized approach to your data preparation tasks. It clearly separates the data preparation step from the rest of your codebase, making it more maintainable and easier to troubleshoot.

2. **Configuration Clarity**: The function call is concise and clear. It specifies the model name and dataset name, which are essential components of data preparation. This clear configuration helps in reproducibility and understanding the data source without diving into complex data loading code.

3. **Efficiency and Automation**: The ***yDataPrep*** package is designed to automate data preparation tasks. In this code snippet, it's fetching data from the "fka/awesome-chatgpt-prompts" dataset and configuring it for use with the "EleutherAI/pythia-70m" model. This automation reduces the potential for human error and saves valuable development time.

4. **Reusability**: The code can be easily reused for different datasets and models by modifying the parameters in the function call. This reusability is essential in professional software development, where code efficiency and flexibility are paramount.

