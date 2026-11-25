## Andres del Castillo

I build statistical and machine learning tools, mostly for population genetics, and release them as software other people can install and check. More recently I've been working on AI agents that keep a long-term memory between sessions.

### Projects

**[DNNaic](https://github.com/yspennstate/DNNaic)** infers which way gene flow went between two populations. Patterson's D can detect gene flow, but it is symmetric, so it can't tell the donor from the recipient. DNNaic works from nine allelic rarefaction statistics that keep that information, with a two-stage network that first decides whether there is appreciable gene flow and then orients it. On coalescent simulations it calls the direction correctly 96.6% of the time at the highest migration rate. On real data it recovers the known *melpomene* to *timareta* direction in *Heliconius* butterflies, and it declines to make a call on the Neanderthal data, where the sampling is too shallow for the method. The repository has the code and the manuscript (del Castillo and Shmalo).

**[PADZE](https://pypi.org/project/padze/)** (`pip install padze`) is a Python successor to ADZE, the C++ program for allelic diversity by rarefaction. It reads VCFs directly, reproduces the original program's output in its classical mode, adds skewness and kurtosis across loci, and needs only NumPy. It computes the features DNNaic uses.

**[SegViT](https://github.com/Andres42611/SegVit)** is a research codebase for generating the transition between two songs from both sides of the gap, over frozen music codec tokens. On held-out tracks, letting the model see the incoming song as well as the outgoing one is worth about 0.14 bits per token, and that gain stays flat for gaps from 1 to 8 seconds. Each claim has a pre-registered gate and a confidence interval in the repo's [report](https://github.com/Andres42611/SegVit/blob/main/REPORT.md).

**[Brain framework](https://github.com/yspennstate/brain-framework-public)** is Yitzchak Shmalo's system for AI agents on one machine that share a long-lived memory: recall over a one-fact-per-file corpus, nightly consolidation, reflexes learned from past mistakes, and coordination so agents don't overwrite each other's work. I'm an early adopter and contributor. I run it every day across Codex and Claude Code, and work with Yitzchak on testing and improving it.

**[Rab](https://github.com/Andres42611/Rab)** computes the ratio of deleterious mutational load between two populations, corrected for relatedness. It was used in a [2024 study of the K'gari island dingoes](https://doi.org/10.1093/gbe/evae130) in *Genome Biology and Evolution*.
