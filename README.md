<div align="center" id="top">
  <img src="./.github/app.gif" alt="Dissertacao" />

  &#xa0;

  <!-- <a href="https://dissertacao.netlify.app">Demo</a> -->
</div>

<h1 align="center">SSSD: Semantic Search Stance Detection</h1>

<p align="center">

  <!-- Badges -->
</p>

## About

SSSD (Semantic Search Stance Detection) is a innovative method based on the Low-shot Learning paradigm for Stance Detection (SD). This technique employs Pre-trained Models (PTMs) to optimize SD in tweets through Semantic Search. SSSD is capable of interpreting context and efficiently classifying tweet content, requiring only a small set of labeled examples. This substantially reduces the manual labeling effort and resources necessary for training SD models. The proposed strategy enhances SD precision by filtering irrelevant content and focusing on the most pertinent posts. SSSD stands out as a pioneer in integrating PTMs and Semantic Search, facilitating the overcoming of challenges related to the scarcity of labeled data and enhancing SD in social media. In experiments referencing the SemEval-2016 competition, SSSD surpassed all established benchmarks, showcasing significant potential in resource savings. A qualitative analysis was also conducted to evaluate the efficacy of SSSD in detecting stances related to the vaccination campaign in Brazil during the COVID-19 pandemic. The results confirm that SSSD achieves good results even with a limited volume of labeled data, distinguishing itself positively compared to other methodologies.

For more detailed information, please refer to the full paper:

- [SSSD](https://aclanthology.org/2023.ranlp-1.30.pdf)

## Technologies Used

- [Python](https://python.org.br/)
- [Sentence Transformers](https://sbert.net/)
- [Pretrained Models](https://www.sbert.net/docs/pretrained_models.html/)
- [Semantic Search](https://www.sbert.net/examples/applications/semantic-search/README.html/)
- [scikt-learn](https://scikit-learn.org/stable/index.html)
- [MLFlow](https://www.mlflow.org/)

## Requirements

Before starting 🏁, ensure you have the following tools installed:

- [Git](https://git-scm.com): Essential for source code management and version control.
- [Python](https://python.org/): Required to run the project. Python 3.6 or higher is recommended.
- [VsCode](https://code.visualstudio.com/): Recommended to run the notebooks files.

## Getting Started

Follow these steps to get your development environment set up:

### 1 - Clone the Repository

```bash
  git clone https://github.com/mediote/sssd.git
  cd sssd
```

### 2 - Create and Activate a Virtual Environment

```bash
  python3 -m venv venv
  source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

### 3 - Install Dependencies

```bash
  pip install -r requirements.txt
```

### 4 - Install the Jupyter extension for VSCode

You can do this from within VSCode by searching for "Jupyter" in the Extensions view or by running the following command in your terminal.

```bash
  code --install-extension ms-toolsai.jupyter
```

## Datasets

To access the datasets used in our analyses, please feel free to reach out for more information at: mediote90@gmail.com


## Citation

```bibtex
@inproceedings{de-sousa-becker-2023-sssd,
    title = "{SSSD}: Leveraging Pre-trained Models and Semantic Search for Semi-supervised Stance Detection",
    author = "de Sousa, Andr{\'e}  and
      Becker, Karin",
    editor = "Mitkov, Ruslan  and
      Angelova, Galia",
    booktitle = "Proceedings of the 14th International Conference on Recent Advances in Natural Language Processing",
    month = sep,
    year = "2023",
    address = "Varna, Bulgaria",
    publisher = "INCOMA Ltd., Shoumen, Bulgaria",
    url = "https://aclanthology.org/2023.ranlp-1.30",
    pages = "264--273",
    abstract = "Pre-trained models (PTMs) based on the Transformers architecture are trained on massive amounts of data and can capture nuances and complexities in linguistic expressions, making them a powerful tool for many natural language processing tasks. In this paper, we present SSSD (Semantic Similarity Stance Detection), a semi-supervised method for stance detection on Twitter that automatically labels a large, domain-related corpus for training a stance classification model. The method assumes as input a domain set of tweets about a given target and a labeled query set of tweets of representative arguments related to the stances. It scales the automatic labeling of a large number of tweets, and improves classification accuracy by leveraging the power of PTMs and semantic search to capture context and meaning. We largely outperformed all baselines in experiments using the Semeval benchmark.",
}
```
