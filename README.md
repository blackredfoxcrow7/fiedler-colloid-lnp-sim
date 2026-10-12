# Graph-Spectral Colloid & LNP Surfactant Phase Predictor (Fiedler-Colloid-LNP-Sim)

**Graph-Spectral Topological Physics Framework for Colloid Science, Surfactant Mesophase Transitions, and Lipid Nanoparticle (LNP) mRNA Drug Delivery Systems**

*Concept & Theory by Yoshihiro Honda (本多 義弘)*  
*Independent Researcher in Organic Chemistry, Japan*

---

## 🔬 Overview & Scientific Concept

In bulk liquid water, hydrogen-bond networks fluctuate randomly, causing isotropic proton diffusion without directional preference. However, in amphiphilic assemblies—such as **hexagonal surfactant hydrogels, Nafion interfaces, and Lipid Nanoparticle (LNP) cores**—bound water networks form directional, 1D/2D hydrogen-bonded channels.

This repository provides a **Graph-Spectral Predictive Framework** that bridges **organic chemical structural formulas and multi-component lipid mixing ratios** directly to **macroscopic physical functions ($\lambda_2$, directional Laplacian anisotropy $\sigma_z/\sigma_{xy}$, packing parameter $P$, and endosomal escape kinetics)**.

### Key Applications
1. **Colloid Science Education**: Interactive 3D visualization of liquid crystal mesophase transitions ($\text{Lamellar Bilayer } L_\alpha \leftrightarrow \text{Inverted Hexagonal } H_{II} \leftrightarrow \text{Bicontinuous Cubic } V_2 \leftrightarrow \text{Micellar } L_1$).
2. **LNP & mRNA Vaccine Engineering**: Predicts how tertiary amine protonation ($N \to NH^+$) at endosomal pH ($\approx 5.5$) triggers aqueous channel percolation and mRNA release for benchmark formulations (**Moderna SM-102**, **Pfizer/BioNTech ALC-0315**, **Onpattro DLin-MC3-DMA**).
3. **Anisotropic Proton Conduction**: Explains directional proton hopping ($E_a \approx 0.12\text{ eV}$) in nonionic + cationic hydrogel membranes.

---

## 🚀 Quick Start & Interactive 3D Visualizers

### 1. Colloid & LNP Phase Predictor 3D Simulator (Educational & Research Tool)
Open [`colloid_lnp_phase_simulator.html`](file:///home/eldenring/fiedler-colloid-lnp-sim/colloid_lnp_phase_simulator.html) directly in any modern Web browser.
- **Features**: Preset dropdown for literature benchmarks, interactive mixing ratio sliders, real-time 3D WebGL mesophase rendering, and 2D Ternary Phase Diagram (三角相図).

### 2. LNP mRNA Endosomal Release 3D Visualizer
Open [`lnp_mrna_release_visualizer.html`](file:///home/eldenring/fiedler-colloid-lnp-sim/lnp_mrna_release_visualizer.html) to inspect LNP core components (mRNA helix, ionizable lipids, DSPC, cholesterol, and pH-dependent water percolation channels).

### 3. Hexagonal Surfactant Gel Proton Channel 3D Visualizer
Open [`hexagonal_proton_gel_visualizer.html`](file:///home/eldenring/fiedler-colloid-lnp-sim/hexagonal_proton_gel_visualizer.html) to explore 1D H-bond water wire alignment and anisotropic proton hopping along the Z-axis.

---

## 🐍 Python Benchmark Engines

Run the Python verification engines to calculate exact Graph Laplacian Fiedler spectra ($\lambda_2$) and packing parameters:

```bash
# 1. Benchmark literature formulation engine (Moderna, Pfizer, Onpattro, Honda Gel)
python3 colloid_surfactant_phase_engine.py

# 2. Multi-component lipid formulation ratio screening engine
python3 lnp_formulation_phase_predictor.py

# 3. LNP internal water network percolation simulator
python3 lnp_mrna_water_network_sim.py

# 4. Hexagonal surfactant gel anisotropic proton conduction simulator
python3 hexagonal_gel_proton_graph_sim.py
```

---

## 📊 Benchmark Literature Verification Results

| Formulation / Reference | pH 7.4 (Storage) Phase | pH 5.5 (Endosomal) Phase | Packing $P$ | Anisotropy ($\sigma_z/\sigma_{xy}$) |
| :--- | :---: | :---: | :---: | :---: |
| **Moderna SM-102** *(Nature 2020)* | Lamellar Bilayer ($L_\alpha$) | Inverted Hexagonal ($H_{II}$) | $1.03 \to 1.62$ | **1.75** |
| **Pfizer ALC-0315** *(Nature 2021)* | Lamellar Bilayer ($L_\alpha$) | Inverted Hexagonal ($H_{II}$) | $1.03 \to 1.60$ | **1.75** |
| **Onpattro DLin-MC3-DMA** *(Nat. Nanotech 2019)* | Lamellar Bilayer ($L_\alpha$) | Inverted Hexagonal ($H_{II}$) | $1.03 \to 1.62$ | **1.75** |
| **Honda Industrial Hydrogel** *(Honda Concept)* | Lamellar Bilayer ($L_\alpha$) | Inverted Hexagonal ($H_{II}$) | $0.97 \to 1.38$ | **1.75** |

---

## 📄 License & Citation

Distributed under the MIT License.

```bibtex
@software{honda2026colloid,
  author = {Yoshihiro Honda},
  title = {Graph-Spectral Colloid & LNP Surfactant Phase Predictor},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/blackredfoxcrow7/fiedler-colloid-lnp-sim}
}
```
