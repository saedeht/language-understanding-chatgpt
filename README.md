![GitHub Repo](https://img.shields.io/badge/Research-Paper-blue)

<h1 style="font-size: 24px;">An Adapted Few-Shot Prompting Technique Using ChatGPT to Advance Low-Resource Languages Understanding</h1>

<p align="justify">

## 📝 Overview:

The lack of annotated data in low-resource languages presents a significant challenge in natural language processing, particularly for language understanding tasks such as intent detection and slot filling. To address this, we propose a novel approach that first employs an effective cross-lingual transfer model to generate labeled data for the target language, overcoming the scarcity of labeled data in low-resource settings. The main contribution of our work lies in the second step, where we introduce an adapted few-shot prompting technique to guide ChatGPT as a large language model (LLM). In this step, a subset of the machine-generated examples is selected based on the domain of the input, ensuring that the LLM is provided with more tailored and domain-specific examples. This two-step process leads to enhanced performance in handling low-resource languages. We conduct extensive experiments on Spanish, Thai, and Persian using the Facebook-multilingual and Persian-ATIS datasets. Experimental results demonstrate that our method outperforms existing techniques for non-Latin languages, such as Thai and Persian, and matches state-of-the-art performance for Latin-based languages, such as Spanish.

</p>

## 📌 Citation

If you use this work, please cite our [paper](https://ieeexplore.ieee.org/abstract/document/11016028) as follows:

```bibtex
@article{TaheryAccess2025,
  author    = {Saedeh Tahery and Saeed Farzi},
  title     = {An Adapted Few-Shot Prompting Technique Using ChatGPT to Advance Low-Resource Languages Understanding},
  journal   = {IEEE Access},
  year      = {2025},
  url       = {https://ieeexplore.ieee.org/abstract/document/11016028}
}

