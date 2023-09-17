# NGSchool.eu 2023 - Bayesian Statistics & Deep Learning (JupyterLite deployment)

See the project at https://vpetukhov.github.io/ngschool2023-bayesian/.

Requires:
- Firefox 90+
- Chromium 89+

## Lecture content

### Theory

Bayesian:
- Selected parts from [P-value Hell](https://slides.com/vpetukhov/p-value-hell-v2/)
- Probability as a measure of uncertainty
- Conditional probabilities

Deep Learning:
- Data-driven learning: lack of priors, limitation on bio cases.
- [Overview of scVI](https://docs.scvi-tools.org/en/stable/)
- Trends in single-cell multi-omics
  - Fabian Theis' group
    - https://arxiv.org/abs/2307.00558
    - https://www.embopress.org/doi/full/10.15252/msb.202211517
  - [Maria Brbic](https://brbiclab.epfl.ch/projects/stellar/)
- Transition to pre-trained models. [HuggingFace](https://huggingface.co/).

### Practice

Bayesian:

- Visualize different distributions
- Example of one of the single-cell models
  - [Yang, S., Corbett, S.E., Koga, Y. et al. Decontamination of ambient RNA in single-cell RNA-seq with DecontX](https://doi.org/10.1186/s13059-020-1950-6)
  - [Levitin HM, Yuan J, Cheng YL, Ruiz FJ, Bush EC, Bruce JN, Canoll P, Iavarone A, Lasorella A, Blei DM, Sims PA. De novo gene signature identification from single-cell RNA-seq with hierarchical Poisson factorization. Mol Syst Biol. 2019](https://doi.org/10.15252/msb.20188557)
- Naive Bayes classifier

Deep Learning:

- DSLs
- Some probabilistic programming?
  - [Pyro](https://pyro.ai/)
  - [PyMC](https://www.pymc.io/)
- Basics of PyTorch?
- Basics of HuggingFace?