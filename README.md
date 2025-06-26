# 📊 VRF-NBI: Python Code

## 📝 Description

This repository contains the **Python implementation** of the Varimax Rotated Factor Normal Boundary Intersection (VRF-NBI) method.

The code is designed to execute all stages of the VRF-NBI process using Python. It allows users to work with their own datasets, but the original dataset (from the published paper) is also provided. This dataset was generated via Design of Experiments (DOE) with responses from Computational Fluid Dynamics (CFD). Latent variable extraction was performed using Principal Components Factor Analysis (PCFA), and multiobjective optimization was done with the Normal Boundary Intersection (NBI) method. Evaluation metrics include Shannon Entropy (S) and Generalized Distance (GD).

> For Excel/VBA implementation of the method, see: [VRF-NBI for Excel/VBA](https://github.com/Matheuscp98/Normal_Boundary_Intersection)

**Note:** This code focuses on applying the method, not on visualization/plotting.

---

## 🛠️ How to Use

1. **Clone or download** this repository or [VRF-NBI.ipynb](VRF-NBI.ipynb).
2. **Open** the notebook in Jupyter.
3. **Install** the required Python libraries (see notebook header for details).
4. **Use** your own dataset or the provided sample dataset.
5. **Run** the code blocks to reproduce all steps and results.
6. The code includes detailed comments and is organized by functional blocks for easier understanding.

---

## 📚 Publications

In addition to ongoing manuscripts under review, the following public papers are already available:

- **Nonlinear Multiobjective Optimization of Efficiency Conditions using a CFD-DOE Hybrid Approach: A Practical Application in Centrifugal Fans for Industrial Ovens**  
  *(The main Python example dataset is from this work. Manuscript currently under review; )*
- **Strategies in Decision Making in a Multiobjective Context: Integration of DOE, NBI, and CFD in the Optimization of a Centrifugal Fan**  
  [Read here](https://publicacoes.softaliza.com.br/cilamce/article/view/10211/7235)
- **Optimizing Mesh and CFD Simulation Performance: A Multivariate Analysis Approach**  
  [Read here](https://publicacoes.softaliza.com.br/cilamce/article/view/8110/6998)
- **Otimização Multiobjetivo de Custos e Qualidade de Simulações de CFD: Explorando a Fronteira de Pareto**  
  [Read here](https://proceedings.science/sbpo/sbpo-2024/trabalhos/otimizacao-multiobjetivo-de-custos-e-qualidade-de-simulacoes-de-cfd-explorando-a?lang=pt-br)

---

## 🖼️ Figures

| Example                                      | Screenshot                        | Description                                        |
|-----------------------------------------------|-----------------------------------|----------------------------------------------------|
| VRF-NBI CCD Design                           | ![VRF-NBI CCD Design](VRF-NBI_CCDDesign.jpg) | Design of experiments using Central Composite Design (CCD). |
| VRF-NBI Responses                            | ![VRF-NBI Responses](VRF-NBI_Responses.jpg) | Responses obtained from the experimental design (using CFD). |
| VRF-NBI Correlation and Covariance           | ![VRF-NBI Correlation Covariance](VRF-NBI_CorrelationCovariance.jpg) | Correlation and covariance matrix of the original responses. |
| VRF-NBI PCAFA                                | ![VRF-NBI PCAFA](VRF-NBI_PCAFA.jpg) | Results from Principal Components Factor Analysis (PCAFA). |
| VRF-NBI DOE Analysis                         | ![VRF-NBI DOE Analysis](VRF-NBI_DOEAnalysis.jpg) | Analysis of DOE for the original responses and the rotated factors. |
| VRF-NBI Coefficients                         | ![VRF-NBI Coefficients](VRF-NBI_Coefficients.jpg) | Coefficients obtained from the analysis. |
| VRF-NBI Simplex Lattice Design               | ![VRF-NBI Simplex Lattice Design](VRF-NBI_SimplexLatticeDesign.jpg) | Visual representation of the Mixture Simplex Lattice Design. |
| VRF-NBI Individual Optimization              | ![VRF-NBI Individual Optimization](VRF-NBI_IndividualOptimization.jpg) | Results of individual optimization (original responses and rotated factors). |
| VRF-NBI Payoff Matrix                        | ![VRF-NBI Payoff Matrix](VRF-NBI_PayoffMatrix.jpg) | Payoff matrix, Utopia, PseudoNadir, and Scaled Payoff. |
| VRF-NBI Additional Functions                 | ![VRF-NBI Additional Functions](VRF-NBI_AdditionalFunctions.jpg) | Additional functions used in the NBI. |
| VRF-NBI Constraints                          | ![VRF-NBI Constraints](VRF-NBI_Constraints.jpg) | Constraints used in the NBI process. |
| VRF-NBI Results                              | ![VRF-NBI Results](VRF-NBI_Results.jpg) | Final results obtained from the VRF-NBI process with evaluation metrics. |

---

## 📬 Contact

<a href="mailto:matheusc_pereira@hotmail.com"><img src="https://img.shields.io/badge/E--mail-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="E-mail"/></a>
<a href="https://www.linkedin.com/in/matheuscostapereira/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://lattes.cnpq.br/7025666927284220"><img src="https://img.shields.io/badge/Lattes-4169E1?style=for-the-badge&logoColor=white" alt="Lattes"/></a>

---

> _Feel free to open issues or PRs, or reach out for collaboration or questions!_
