## Hi, I'm Emma 👋🏽

I'm a PhD candidate in Physics at MIT, where I'm part of the [Binary Star Astrophysics group](https://binaries.mit.edu/) at the MIT Kavli Institute. I work on **machine learning for time-domain astronomy** — specifically, self-supervised representation learning on irregularly-sampled light curves from large surveys like the Zwicky Transient Facility (ZTF).

> 📣 **News (2026):** *Template Matching, Not Time Learning* accepted at the **AI4Physics workshop @ ICML 2026** — [see the poster »](https://emmachickles.github.io/period-diagnostic/poster/poster.pdf)

My research sits at the intersection of:
- 🌌 **Ultracompact white dwarf binaries** — extreme stellar systems with sub-hour orbital periods, important as [LISA](https://en.wikipedia.org/wiki/Laser_Interferometer_Space_Antenna) gravitational-wave sources and Type Ia supernova progenitors
- 🤖 **Representation learning** — transformers, contrastive learning, and interpretability of learned embeddings on real-world scientific time-series
- ⚡ **Scalable ML systems** — distributed multi-GPU training, large-scale data pipelines (TB-scale), and GPU-accelerated periodicity search

### 🔭 Currently building
- [**`period-diagnostic`**](https://github.com/emmachickles/period-diagnostic) — *Template Matching, Not Time Learning* (**accepted at AI4Physics @ ICML 2026**). A drop-in diagnostic that decomposes period-regression R² into between- vs. within-class signal, revealing that self-supervised light-curve encoders recover stellar periods by **class-template matching, not genuine time learning** — across eight encoders from a 4.4M BiGRU to the 110M MOMENT foundation model. [📄 paper](https://emmachickles.github.io/period-diagnostic/paper/template-matching-not-time-learning.pdf) · [🪧 poster](https://emmachickles.github.io/period-diagnostic/poster/poster.pdf) · [🔭 interactive demo](https://emmachickles.github.io/ztf-embedding-demo/period-aliasing/)
- [**`ztf-pocket`**](https://emmachickles.github.io/ztf-pocket/) — 📱 four phone-first companions to the ICML poster: an embedding explorer (colour by class / period / periodic strictness / amplitude, with the 6.9-min binary ZTF J1539 as a tappable gold ★), a 26k-star "ZTF in the wild" map with injected ultracompacts, an interactive HR diagram, and playable Lomb–Scargle periodograms — all pure-canvas, no dependencies.
- [**`ztf-embedding-demo`**](https://emmachickles.github.io/ztf-embedding-demo/) — interactive demo for exploring learned ZTF light-curve embeddings; clickable sources, comparison across representation spaces, focus on whether embeddings capture physical structure vs. survey systematics
- **Self-supervised transformer for ZTF** — dual-head architecture trained with contrastive learning on 1.4B+ irregularly-sampled light curves; scaling to multi-GPU DDP on 16 A100 GPUs on MIT's Engaging cluster (MGHPCC, Holyoke).
- [**`blender_binaries`**](https://github.com/emmachickles/blender_binaries) — physically faithful Blender visualizations of interacting compact binaries, where the rendered mesh *is* the surface that produces the model light curve. Built from `lcurve` fits; showcase: the eclipsing 8.56-minute binary ATLAS J1013−4516.

### 🎤 Recent talks
- [**LISA's rich, guaranteed science: Galactic ultracompact binaries**](https://github.com/emmachickles/talks/blob/main/lisa-galactic-binaries-2026.pdf) — binary evolution, Type Ia progenitors, and the physics of accretion (June 2026) · [animated deck](https://github.com/emmachickles/talks/releases/download/lisa-2026/5-GalacticBinaries-EmmaChickles.pptx) · more in [`talks`](https://github.com/emmachickles/talks)

### 📄 Selected publications
- **Chickles, E.** & Burdge, K. *"Template Matching, Not Time Learning: A Diagnostic for Self-Supervised Light-Curve Encoders"* — *AI4Physics Workshop, ICML* (2026) · [code & paper](https://github.com/emmachickles/period-diagnostic) · [poster](https://emmachickles.github.io/period-diagnostic/poster/poster.pdf)
- **Chickles, E.**, et al. *"An eclipsing 8.56-minute orbital period mass-transferring binary"* — *ApJ* (2026)
- **Chickles, E.**, et al. *"A gravitational-wave–detectable Type Ia supernova progenitor"* — *ApJ* (2025)

### 📫 Reach me
- 📧 echickle@mit.edu
- 🌐 [emmachickles.github.io](https://emmachickles.github.io/ztf-embedding-demo/)
- 🔭 [ORCID](https://orcid.org/0000-0003-4780-4105)
