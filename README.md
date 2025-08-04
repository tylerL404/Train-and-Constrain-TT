# Train and Constrain: Phonologically Informed Tongue Twister Generation from Topics and Paraphrases (Computational Linguistics, 2025)
This repository contains the code and resources for the paper titled "Train and Constrain: Phonologically Informed Tongue Twister Generation from Topics and Paraphrases," published in Computational Linguistics by MIT Press.

# 📄 Paper and Citation
## Abstract
Previous work in phonologically and phonetically grounded language generation has mainly focused on domains such as puns and poetry. In this article, we present new work on the generation of English tongue twisters—a form of language that is required to be conditioned on a phoneme level to maximize sound overlap, while maintaining semantic consistency with an input topic or phrase and still being grammatically correct. We present TwisterLister, a pipeline for generating phonologically informed tongue twisters from large language models (LLMs) that we use to generate TwistList 2.0, the largest annotated dataset of tongue twisters to date, consisting of 17k+ examples from a combination of human and LLM authors. Our generation pipeline involves the use of a phonologically constrained vocabulary alongside LLM prompting to generate novel, non-derivative tongue twister examples. We additionally present the results of automatic and human evaluation of smaller models trained on our generated dataset to demonstrate the extent to which phonologically motivated language types can be generated without explicit injection of phonological knowledge. Additionally, we introduce a phoneme-aware constrained decoding module (PACD) that can be integrated into an autoregressive language model and demonstrate that this method generates good quality tongue twisters both with and without fine-tuning the underlying language model. We also design and implement a range of automatic metrics for the task of tongue twister generation that is phonologically motivated and captures the unique essence of tongue twisters, primarily based on phonemic edit distance (PED).

Full paper available **[here](⌛)**.

## Citation
If you use this work, please cite our paper:

```bibtex@article{10.1162/coli_a_00544,
    author = {Loakman, Tyler and Tang, Chen and Lin, Chenghua},
    title = {Train and Constrain: Phonologically Informed Tongue Twister Generation from Topics and Paraphrases},
    journal = {Computational Linguistics},
    volume = {51},
    number = {2},
    pages = {415-466},
    year = {2025},
    month = {06},
    abstract = {Previous work in phonologically and phonetically grounded language generation has mainly focused on domains such as puns and poetry. In this article, we present new work on the generation of English tongue twisters—a form of language that is required to be conditioned on a phoneme level to maximize sound overlap, while maintaining semantic consistency with an input topic or phrase and still being grammatically correct. We present TwisterLister, a pipeline for generating phonologically informed tongue twisters from large language models (LLMs) that we use to generate TwistList 2.0, the largest annotated dataset of tongue twisters to date, consisting of 17k+ examples from a combination of human and LLM authors. Our generation pipeline involves the use of a phonologically constrained vocabulary alongside LLM prompting to generate novel, non-derivative tongue twister examples. We additionally present the results of automatic and human evaluation of smaller models trained on our generated dataset to demonstrate the extent to which phonologically motivated language types can be generated without explicit injection of phonological knowledge. Additionally, we introduce a phoneme-aware constrained decoding module (PACD) that can be integrated into an autoregressive language model and demonstrate that this method generates good quality tongue twisters both with and without fine-tuning the underlying language model. We also design and implement a range of automatic metrics for the task of tongue twister generation that is phonologically motivated and captures the unique essence of tongue twisters, primarily based on phonemic edit distance (PED).1},
    issn = {0891-2017},
    doi = {10.1162/coli_a_00544},
    url = {https://doi.org/10.1162/coli\_a\_00544},
    eprint = {https://direct.mit.edu/coli/article-pdf/51/2/415/2477508/coli\_a\_00544.pdf},
}
```

# Repo Progress 🚧
- Dataset (TwistList 2.0) ✅
- Dataset Pipeline Code (TwisterLister) ⌛
- Phoneme-based Metrics (iPED/oPED/IPO/PO) ⌛
- Phoneme Aware Constrained Decoding (PACD) ⌛
