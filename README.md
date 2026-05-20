# An Introduction to Probabilistic Model Building
### or, thinking about models in the era of AI

A short course in probabilistic modelling for biology PhD students and researchers. Three sessions, lecture slides paired with hands-on Jupyter notebooks. No prior ML or Bayesian statistics is assumed; basic Python familiarity is enough.

## What the course covers

Four threads run through the sessions:

1. **Bayesian modelling as generative storytelling**: writing down how data could have been produced.
2. **Inductive bias**: the assumptions that let a model generalise, including smoothness, sparsity, and structural priors.
3. **Latent variable models**: from hierarchical models, through VAEs, to diffusion.
4. **Computer-aided experimental design**: Bayesian optimal experimental design and compressed sensing.

## Sessions

| Session | Topic | Slides |
|---|---|---|
| 1 | Probabilistic modelling foundations | [PDF](Session%201%20-%20Intro%20to%20model%20building.pdf) |
| 2 | Latent variable models (hierarchical, VAE, diffusion) | [PDF](Session%202%20-%20Latent%20variable%20models.pdf) |
| 3 | Computer-aided experimental design | [PDF](Session%203%20-%20CAD.pdf) |

## Notebooks

Click the Colab badge to open a notebook directly in Google Colab. The notebooks below include worked solutions inline.

### Session 1 — Foundations
- [`Session1_Foundations_WithAnswers.ipynb`](Session1_Foundations_WithAnswers.ipynb)  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiasFrazerGroup/Intro-to-probabilistic-modelling-2026/blob/main/Session1_Foundations_WithAnswers.ipynb)

### Session 2 — Latent variable models
- [`Session2a_HierarchicalModels_WithAnswers.ipynb`](Session2a_HierarchicalModels_WithAnswers.ipynb)  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiasFrazerGroup/Intro-to-probabilistic-modelling-2026/blob/main/Session2a_HierarchicalModels_WithAnswers.ipynb)
- [`Session2b_ProteinVAE_WithAnswers.ipynb`](Session2b_ProteinVAE_WithAnswers.ipynb)  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiasFrazerGroup/Intro-to-probabilistic-modelling-2026/blob/main/Session2b_ProteinVAE_WithAnswers.ipynb)

### Session 3 — Experimental design
- [`Session3a_BOED_WithAnswers.ipynb`](Session3a_BOED_WithAnswers.ipynb)  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiasFrazerGroup/Intro-to-probabilistic-modelling-2026/blob/main/Session3a_BOED_WithAnswers.ipynb)
- [`Session3b_CompressedSensing_WithAnswers.ipynb`](Session3b_CompressedSensing_WithAnswers.ipynb)  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DiasFrazerGroup/Intro-to-probabilistic-modelling-2026/blob/main/Session3b_CompressedSensing_WithAnswers.ipynb)

Each notebook starts with a `pip install` cell that sets up its dependencies in a fresh Colab runtime.

## Running locally

If you would rather work outside Colab:

```bash
git clone https://github.com/DiasFrazerGroup/Intro-to-probabilistic-modelling-2026.git
cd Intro-to-probabilistic-modelling-2026
pip install pymc arviz numpy scipy matplotlib jupyter
# The Session 2 protein VAE notebook additionally needs:
pip install torch
jupyter notebook
```

## Authors

Jonathan Frazer and Mafalda Dias  
Centre for Genomic Regulation, Barcelona

## License

The course materials are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are welcome to use, adapt, and redistribute with attribution. If you use this material in teaching or research, we'd love to know.
