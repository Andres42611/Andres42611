<div align="center">
  <a href="https://github.com/Andres42611">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg" />
      <img alt="Andres del Castillo — population genetics, scientific software, machine learning" src="assets/banner-dark.svg" width="100%" />
    </picture>
  </a>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Population_Genetics-0ea5e9?style=flat-square&labelColor=0b1220" alt="Population Genetics" />
  <img src="https://img.shields.io/badge/Statistical_Genomics-14b8a6?style=flat-square&labelColor=0b1220" alt="Statistical Genomics" />
  <img src="https://img.shields.io/badge/Reproducible_Science-6366f1?style=flat-square&labelColor=0b1220" alt="Reproducible Science" />
  <img src="https://img.shields.io/badge/Machine_Learning-a78bfa?style=flat-square&labelColor=0b1220" alt="Machine Learning" />
</p>

<p align="center">
  <em>I build open, reproducible scientific software at the meeting point of <strong>population genetics</strong> and <strong>machine learning</strong> —<br/>tools other researchers can install and run, not just read about.</em>
</p>

---

### The throughline

I started in computational population genetics as an undergraduate researcher in the [Szpiech Lab](http://szpiech.com/), writing statistics that turn raw genomes into evidence about how populations survive isolation and inbreeding — work that has since been used in **published conservation-genomics research**. I'm now repackaging those methods so anyone can `pip install` and use them, and extending into machine learning, carrying the same non-negotiable: results that are **honest, reproducible, and actually runnable**.

---

### Currently building

**[PADZE](https://github.com/Andres42611/PADZE)** &nbsp;·&nbsp; *a classic population-genetics method, one install away*
> `pip install padze` — a modern Python successor to the widely used **ADZE** allelic-diversity tool. It reads VCFs directly, **reproduces the original C++ results exactly** (validated across 82 automated tests), and extends them with higher-order statistics. What used to require specialized setup is now an importable API and a single command any researcher can run.
>
> **[↗ Repository](https://github.com/Andres42611/PADZE)** &nbsp;·&nbsp; **[↗ Live on PyPI](https://pypi.org/project/padze/)**

**[SegViT Audio](https://github.com/Andres42611/SegVit)** &nbsp;·&nbsp; *repurposing Vision Transformers for sound*
> An experiment adapting a Vision Transformer to continue audio waveforms and generate DJ-style bridges between songs. As deliberate as the model is the discipline around it: a published model card, an evidence ledger, honest reporting of what is *not yet* proven, and a hard licensing boundary — machine-learning research done the way research should be.
>
> **[↗ Repository](https://github.com/Andres42611/SegVit)**

---

### Selected work

**[Rab](https://github.com/Andres42611/Rab)** &nbsp;·&nbsp; *a genome statistic that reached published conservation research*
> Computes the **R(X,Y) ratio of deleterious mutational load** between two populations, correcting for relatedness with a BLUE kinship estimator. Built in the Szpiech Lab and used in **peer-reviewed research** on isolation and inbreeding in an **island (K'gari) dingo population** ([Leon-Apodaca et al., 2024, *Genome Biology and Evolution*](https://academic.oup.com/gbe/article/16/7/evae130/7697979)).
>
> **[↗ Repository](https://github.com/Andres42611/Rab)**

**[FiveEquation · ADZE](https://github.com/Andres42611/FiveEquation_ADZE)** &nbsp;·&nbsp; *the groundwork PADZE now generalizes*
> Supporting computation behind allelic-diversity analysis — the earlier research code that motivated a cleaner, packaged, and broadly usable successor.
>
> **[↗ Repository](https://github.com/Andres42611/FiveEquation_ADZE)**

---

### Cite & connect

- **PADZE** — del Castillo A, Shmalo Y. 2026. *PADZE: Pythonic Allelic Diversity Analyzer* (v0.1.0). <https://github.com/Andres42611/PADZE>
- **Research home** — [Szpiech Lab](http://szpiech.com/), statistical & population genomics
- **Collaborator** — Yitzchak Shmalo, Hebrew University of Jerusalem

<p align="center">
  <sub>Correct · reproducible · actually usable — that's the bar for everything here.</sub>
</p>
