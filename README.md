<!-- Banner / Header -->
<p align="center">
  <a href="https://scholar.google.com/citations?user=0N32qusAAAAJ&hl=de">
    <img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square&logo=google-scholar&logoColor=white" alt="Google Scholar">
  </a>
  <a href="https://orcid.org/0000-0002-0481-8104">
    <img src="https://img.shields.io/badge/ORCID-0000--0002--0481--8104-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID">
  </a>
  <a href="https://github.com/N-Nieto/Inner_Speech_Dataset">
    <img src="https://img.shields.io/badge/Featured%20Dataset-Inner%20Speech%20(EEG)-ff6b6b?style=flat-square" alt="Inner Speech Dataset">
  </a>
</p>

<h1 align="center">Nico Nieto</h1>
<p align="center">
  <b>Machine Learning Researcher</b> · <b>PhD in Computer Science</b> · <b>Germany</b><br>
  Building tools that outlive the paper.
</p>

<p align="center">
  <a href="https://github.com/N-Nieto?tab=repositories">
    <img src="https://img.shields.io/badge/Public%20Repos-20+-181717?style=flat-square&logo=github" alt="Public Repos">
  </a>
  <a href="https://github.com/N-Nieto/Inner_Speech_Dataset/stargazers">
    <img src="https://img.shields.io/github/stars/N-Nieto/Inner_Speech_Dataset?style=flat-square&logo=github&label=Inner%20Speech%20Stars&color=ff6b6b" alt="Inner Speech Stars">
  </a>
    <a href="https://github.com/N-Nieto/UniHarmony">
    <img src="https://img.shields.io/github/stars/N-Nieto/UniHarmony?style=flat-square&logo=github&label=UniHarmony%20Stars&color=6366f1" alt="UniHarmony Stars">
  </a>

  <a href="https://neuromatch.io/deep-learning/">
  <img src="https://img.shields.io/badge/Neuromatch%20Academy-Deep%20Learning%20Instructor-6366F1?style=flat-square&logo=neuromatch&logoColor=white" alt="Neuromatch Academy Deep Learning Instructor">
</a>
</p>

---

## I turn messy biomedical data into reproducible insights across sites.

| Modality | Focus
|----------|-------
| **EEG** | EEG-based BCI, inner speech decoding
| **Images** | Brain MRI harmonization, brain age prediction 
| **Tabular** | Multi-site harmonization, clinical outcomes
| **Voice** | Vocal biomarkers, speech-induced suppression
| **Connectivity** | Resting-state fMRI
---

## [Inner Speech Dataset](https://github.com/N-Nieto/Inner_Speech_Dataset)

An open-access EEG dataset for inner speech recognition — one of the largest of its kind.

- **10 subjects** · **3 sessions** · **128-channel EEG** · **5,640 trials** · **20.3 GB**
- **Published in** *Scientific Data* (Nature, 2022)
-  Hosted on [OpenNeuro](https://openneuro.org/datasets/ds003626)
- Includes preprocessing pipelines, download scripts, and a Google Colab tutorial


---

## Data Harmonization

Making models generalize across scanners, sites, and hospitals.

### [UniHarmony](https://github.com/N-Nieto/UniHarmony)

```bash
pip install uniharmony
```

- ComBat, CovBat, and custom methods for MRI and tabular data
- Binder-ready example notebooks

A unified Python API for neuroimaging harmonization.

### [HarmonizationZoo](https://github.com/N-Nieto/HarmonizationZoo) · [Website](https://n-nieto.github.io/HarmonizationZoo/)
An interactive site that aims to provide an easy way to see, seek, and compare harmonization methods.

### [PrettYharmonize](https://github.com/juaml/PrettYharmonize)
Target-free harmonization for when you don't have labels at test time, for example in machine learning scenarios. Predicts harmonization targets without ground truth during inference.

### [Harmonization via Interpolation](https://link.springer.com/article/10.1007/s44248-026-00100-7)
- **Inter-Site SMOTE**: generates synthetic training data by interpolating age- and gender-matched participants across sites
- Evaluated on **N = 2,031** subjects across four datasets

### [Federated Learning Harmonization](https://ieeexplore.ieee.org/abstract/document/11391943/)
- How to integrate data harmonization in Federated learning setups?
- How to harmonize data that we can not access?
---

## Teaching & Education

### [OHBM 2026: Data harmonization for neuroscientific research: Theory, challenges, and applications.](https://github.com/N-Nieto/OHBM-2026-Harmonization-Course)
Theory, challenges, and hands-on Jupyter tutorials for combining data across scanners and sites.

> This educational course was highlighted in [Andy's Brain Tube OHBM Recap](https://www.youtube.com/watch?v=zhyFb0tU4aY).

### [Basics of Applied Machine Learning](https://github.com/juaml/Basics_of_Applied_Machine_Learning)
Introductory ML course for neuroimaging and biomedical data.

### [Basics of Unix Terminal and Programming](https://github.com/juaml/Basics_of_Unix_Terminal_and_Programming)
Unix/Linux fundamentals for researchers working with HPC clusters.

### Neuromatch Academy — Deep Learning Instructor


Teaching assistant and instructor for the [Neuromatch Academy Deep Learning course](https://neuromatch.io/deep-learning/), a global, intensive summer school on computational neuroscience and deep learning.

### ASSC 2025 Tutorial
*Caveats and Guidelines to Safely Apply Machine Learning in Consciousness Research* — Common pitfalls, leakage, overfitting, and interpretability.

### OHBM Online Satellite Meeting 2025
*Enhancing accessibility and sustainability* in neuroimaging tools.
