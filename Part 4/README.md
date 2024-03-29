| Notebook | Description | Colab Link | Video Tutorial |
|----------|-------------|------------|----------------|
| Plansformer Fine-tuning with CodeT5 | Open the fine-tuning notebook in Google Colab for an interactive experience. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishalPallagani/LLMsforPlanningLab-AAAI24/blob/main/Part%204/Plansformer_Finetuning_CodeT5.ipynb) | [![Video Tutorial](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/wR8tVWN0rVc) |
| Plansformer Inference | For inference with the Plansformer model, open this notebook in Google Colab. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VishalPallagani/LLMsforPlanningLab-AAAI24/blob/main/Part%204/Plansformer_Inference.ipynb) | [![Video Tutorial](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/YGSWMSgBG1g) |


# [Part 4] - Plansformer                                                                              

## Overview
The notebooks in this module explain how to fine-tune the CodeT5-base model on planning problems, leading to the creation of Plansformer, and further demonstrate how to use Plansformer for inference. As an additional resource and for better understanding, you can also look at the Plansformer demo tutorial available here 

[![Video Tutorial](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/_1rlctCGsrk)

## Prerequisites
- Basic understanding of Python programming.

## How to Run This Notebook
1. **Open in Google Colab**: Click on the link at the top of the notebook to open it in Google Colab.
2. **Install Dependencies**: Run the first few code cells to install required Python packages and import Plansformer from Dropbox.
3. **Runtime Setup**: Ensure you are using a Python environment with GPU support for better performance. In Google Colab, you can set this via `Runtime > Change runtime type > Hardware accelerator > GPU`.
4. **Run Each Cell**: Execute each cell in sequence by pressing `Shift + Enter`. Read the comments and instructions in each cell to understand the code and outputs.
5. **Experiment**: Feel free to modify the code or experiment with different problems provided in `./data/test_samples`.

## Support
For questions or issues, please raise an issue in the repository or contact the author.

## Acknowledgments
This tutorial was created using resources and tools from Hugging Face, Google Colab, and is part of the paper [Plansformer: Generating symbolic plans using transformers](https://arxiv.org/ftp/arxiv/papers/2212/2212.08681.pdf). To cite this work in your research, please use the following BibTeX entry:

```
@article{pallagani2022plansformer,
title={Plansformer: Generating symbolic plans using transformers},
author={Pallagani, Vishal and Muppasani, Bharath and Murugesan, Keerthiram and Rossi, Francesca and Horesh, Lior and Srivastava, Biplav and Fabiano, Francesco and Loreggia, Andrea},
journal={arXiv preprint arXiv:2212.08681},
year={2022}
}
```



