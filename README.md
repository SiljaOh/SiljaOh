<h1 align="center">Silja Ohlsen</h1>
<p align="center">
  <b>Machine learning for science</b> · geometric deep learning · proteomics · protein structure<br>
  B.Sc. Bioinformatics, TU Munich &amp; LMU Munich · Cusanuswerk Scholar
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/silja-ohlsen-55135a398/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:silja@ohlsen.family"><img src="https://img.shields.io/badge/Email-silja%40ohlsen.family-555?logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 🔬 Current research: MIT DeCoDE Lab

**Student Researcher · Massachusetts Institute of Technology · since May 2026**
*Geometric deep learning surrogates for car crash simulation · supervised by Mohamed Elrefaie (MIT)*

Full-vehicle crash simulations take hours to days per design. We train neural surrogates that predict the complete crash sequence in seconds. Our **hierarchical model** splits the vehicle into its semantic parts, encodes each part's 3D geometry, passes messages across part interfaces, applies physics-based self-attention and decodes the deformation over time.

**My contribution:** the geometric encoder (functional attention over region tokens per part) and the benchmarking pipeline (FIGConvNet, GeoTransolver, MeshGraphNet, PointNet++).

| vs. GeoTransolver (state of the art) | Result |
|---|---|
| Parameters | **−87 %** (0.89M vs. 7.08M) |
| Mean squared error | **−9 %** |
| Peak error | **−29 %** |
| Relative L2 error | on par |

📄 *Manuscript in preparation for ICML 2027 · code private until publication*

---

## 🏆 Highlights

- **1st place**, peptide retention time prediction challenge, TUM Computational Mass Spectrometry (Jan 2026) → [`rt-prediction`](https://github.com/SiljaOh/rt-prediction)
- **R² = 0.977** for collision cross section prediction on 840,000+ peptides with an LSTM, Computational Mass Spectrometry group of Prof. Mathias Wilhelm, TUM
- **Teaching Assistant**, Linear Algebra for Computer Science, TUM
- **2nd place statewide**, German Mathematics Olympiad (Hesse)

## 🧬 Selected projects

| Project | What | Stack |
|---|---|---|
| [**rt-prediction**](https://github.com/SiljaOh/rt-prediction) | 🏆 Winning model for peptide retention time: ExtraTrees on physicochemical features + per-run calibration, MAE 2.78 min on 73,782 peptides | Python, scikit-learn |
| [**protein-structure-prediction**](https://github.com/SiljaOh/protein-structure-prediction) | GOR I–V secondary structure prediction (67.1 % Q3 on CB513) and pairwise alignment, from scratch | Java, Python |
| [**needleman-wunsch**](https://github.com/SiljaOh/needleman-wunsch) | Global protein sequence alignment with BLOSUM62, traceback and tests: my first alignment implementation (Jan 2025) | Java |
| [**bioinformatics-toolkit**](https://github.com/SiljaOh/bioinformatics-toolkit) | Alignment web server: Gotoh, Smith-Waterman, free-shift; HOMSTRAD validation and gap-parameter tuning | Java, Python, MariaDB |

## 🛠️ Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![PyG](https://img.shields.io/badge/PyTorch_Geometric-3C2179?logo=pyg&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
