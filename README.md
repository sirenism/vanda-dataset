# Vanda Dataset

This is the official repository of **VANDAlize: Safety Degradation of Large Language Models Through Taglish-Based Inputs**.

## Keywords
`LLM`, `Code-switching`, `Multilinggual`, `Red-teaming`

## Abstract
Large language models have developed immensely across recent years, however such development poses serious AI safety concerns. A notable risk is the exploitation of LLMs to produce harmful and unethical content, specifically through red-teaming efforts. This paper systematically explores the linear decodability, representation alignment, and cross-lingual transferability across English, Filipino, and Taglish-based inputs. To evaluate this, the VANDA dataset, consisting of 350 aligned trilingual red-teaming prompts, was created and assessed through the Llama-2-13b and Llama-SEA-LION-v3-8B models. A difference-of-mean probe was utilized to retrieve activations of the three languages across both models. Then, the activations were used to calculate the cosine similarity and cross-lingual transfer accuracy. Through this, the results indicate that harmfulness is linearly decodable in English, Filipino, and Taglish under the evaluation. Furthermore, it was observed that cross-lingual transferability and direction alignment were language-pair and model-dependent. Together, these findings provide insights on and comparisons between internal representations of harmfulness in English, and low resource language of Filipino and Taglish. 

## Data Sources
The English translations of the harmful prompts subset and their respective harm categories were taken from the [Aya Red-teaming Dataset](https://huggingface.co/datasets/CohereLabs/aya_redteaming?not-for-all-audiences=true). The English and Filipino translations of the benign prompts subset were taken from the [Tagalog-Filipino-English-Translation Dataset](https://huggingface.co/datasets/rhyliieee/tagalog-filipino-english-translation). 
