# The Elephant in the Room: Analyzing the Presence of Big Tech in Natural Language Processing Research
[![arXiv](https://img.shields.io/badge/arXiv-2305.02797-b31b1b.svg)](arxiv.org/abs/2305.02797)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This repository contains the code and data for the ACL 2023 paper [The Elephant in the Room: Analyzing the Presence of Big Tech in Natural Language Processing Research](arxiv.org/abs/2305.02797).


[![teaser](./teaser.png)](./teaser.png)


## Data
If you want to use our preprocessed data, consider `data/processed_data.zip`.

To reproduce the data for later years, you will need to download the `anthology.bib` from the [ACL Anthology](https://aclanthology.org) and place it in the `data` folder.

You can find the list of universities [here](https://www.topuniversities.com/qs-world-university-rankings) and an export of big tech companies [here](https://finviz.com).

To reproduce the dataset, you can use the notebook `notebooks/datasets.ipynb`.

### Analysis
For running parts of the analysis of the paper, you can use the notebook `notebooks/analysis.ipynb`.

## How to Cite

```tex
@inproceedings{abdalla-etal-2023-elephant,
    title = "The Elephant in the Room: Analyzing the Presence of Big Tech in Natural Language Processing Research",
    author = "Abdalla, Mohamed  and
      Wahle, Jan Philip  and
      Lima Ruas, Terry  and
      N{\'e}v{\'e}ol, Aur{\'e}lie  and
      Ducel, Fanny  and
      Mohammad, Saif  and
      Fort, Karen",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.734",
    pages = "13141--13160",
    abstract = "Recent advances in deep learning methods for natural language processing (NLP) have created new business opportunities and made NLP research critical for industry development. As one of the big players in the field of NLP, together with governments and universities, it is important to track the influence of industry on research. In this study, we seek to quantify and characterize industry presence in the NLP community over time. Using a corpus with comprehensive metadata of 78,187 NLP publications and 701 resumes of NLP publication authors, we explore the industry presence in the field since the early 90s. We find that industry presence among NLP authors has been steady before a steep increase over the past five years (180{\%} growth from 2017 to 2022). A few companies account for most of the publications and provide funding to academic researchers through grants and internships. Our study shows that the presence and impact of the industry on natural language processing research are significant and fast-growing. This work calls for increased transparency of industry influence in the field.",
}
```
