# 📊 VRF-NBI: Python Code

## 📝 Description

This repository contains the **Python implementation** of the **Varimax Rotated Factor Normal Boundary Intersection (VRF-NBI)** method.

The code is designed to execute **all stages** of the **VRF-NBI process** using **Python**. It allows users to work with their **own datasets**, but the **original dataset** (from the published paper) is also provided. This dataset was generated via **Design of Experiments (DOE)** with responses from **Computational Fluid Dynamics (CFD)**. **Latent variable extraction** was performed using **Principal Components Factor Analysis (PCFA)**, and **Multiobjective Optimization (MO)** was done with the **Normal Boundary Intersection (NBI)** method. **Evaluation metrics** include **Shannon Entropy (S)** and **Generalized Distance (GD)**.

The code is designed to execute **all stages** of the **VRF-NBI** process using **Python**. It allows users to work with their **own datasets**; moreover, the **original datasets** (from the published papers) are also provided. These datasets were generated via **Design of Experiments (DOE)** with responses from **Computational Fluid Dynamics (CFD)**. **Latent variable extraction** was performed using **Principal Components Factor Analysis (PCFA)**, and **Multiobjective Optimization (MO)** was conducted with the **Normal Boundary Intersection (NBI)** method. **Evaluation metrics** include **Shannon Entropy (S)** and **Generalized Distance (GD)**.

> For **Excel/VBA implementation** of the method, see: [**VRF-NBI for Excel/VBA**](https://github.com/Matheuscp98/Normal_Boundary_Intersection)

**Note:** This code focuses on **applying the method**, not on **visualization/plotting**.

---

## 📚 Publications

In addition to ongoing manuscripts under review, the following public papers are already available:

- **Nonlinear Multiobjective Optimization of Efficiency Conditions using a CFD-DOE Hybrid Approach: A Practical Application in Centrifugal Fans for Industrial Ovens**  
  [Read here](https://www.sciencedirect.com/science/article/pii/S2451904925006900)
- **Strategies in Decision Making in a Multiobjective Context: Integration of DOE, NBI, and CFD in the Optimization of a Centrifugal Fan**  
  [Read here](https://publicacoes.softaliza.com.br/cilamce/article/view/10211/7235)
- **Optimizing Mesh and CFD Simulation Performance: A Multivariate Analysis Approach**  
  [Read here](https://publicacoes.softaliza.com.br/cilamce/article/view/8110/6998)
- **Multiobjective optimization of CFD simulation costs and quality: Exploring the Pareto frontier** (*Otimização Multiobjetivo de Custos e Qualidade de Simulações de CFD: Explorando a Fronteira de Pareto*)  
  [Read here](https://proceedings.science/sbpo/sbpo-2024/trabalhos/otimizacao-multiobjetivo-de-custos-e-qualidade-de-simulacoes-de-cfd-explorando-a?lang=pt-br)

---

## 🛠️ How to Use

1. **Clone or download** this repository or [**Script VRF-NBI**](VRF-NBI.ipynb).  
2. **Open** the notebook in **Jupyter**.  
3. **Install** the **required Python libraries** (see notebook header for details).  
4. **Use** your own dataset or the **provided sample dataset**.  
5. **Run** the code blocks to reproduce **all steps and results**.  
6. The code includes **detailed comments** and is **organized by functional blocks** for easier understanding.  

---

## 🖼️ Figures

| Example                                      | Screenshot                        | Description                                        |
|-----------------------------------------------|-----------------------------------|----------------------------------------------------|
| VRF-NBI CCD Design                           | ![VRF-NBI CCD Design](VRF-NBI_CCDDesign.jpg) | Design of experiments using Central Composite Design (CCD). |
| VRF-NBI Responses                            | ![VRF-NBI Responses](VRF-NBI_Responses.jpg) | Responses obtained from the experimental design (using CFD). |
| VRF-NBI Correlation and Covariance           | ![VRF-NBI Correlation Covariance](VRF-NBI_CorrelationCovariance.jpg) | Correlation and covariance matrix of the original responses. |
| VRF-NBI PCFA                                 | ![VRF-NBI PCFA](VRF-NBI_PCFA.jpg) | Results from Principal Components Factor Analysis (PCFA). |
| VRF-NBI DOE Analysis                         | ![VRF-NBI DOE Analysis](VRF-NBI_DOEAnalysis.jpg) | Analysis of DOE for the original responses and the rotated factors. |
| VRF-NBI Coefficients                         | ![VRF-NBI Coefficients](VRF-NBI_Coefficients.jpg) | Coefficients obtained from the analysis. |
| VRF-NBI Simplex Lattice Design               | ![VRF-NBI Simplex Lattice Design](VRF-NBI_SimplexLatticeDesign.jpg) | Visual representation of the Mixture Simplex Lattice Design. |
| VRF-NBI Individual Optimization              | ![VRF-NBI Individual Optimization](VRF-NBI_IndividualOptimization.jpg) | Results of individual optimization (original responses and rotated factors). |
| VRF-NBI Payoff Matrix                        | ![VRF-NBI Payoff Matrix](VRF-NBI_PayoffMatrix.jpg) | Payoff matrix, Utopia, Pseudo Nadir, and Scaled Payoff. |
| VRF-NBI Additional Functions                 | ![VRF-NBI Additional Functions](VRF-NBI_AdditionalFunctions.jpg) | Additional functions used in the NBI. |
| VRF-NBI Constraints                          | ![VRF-NBI Constraints](VRF-NBI_Constraints.jpg) | Constraints used in the NBI process. |
| VRF-NBI Results                              | ![VRF-NBI Results](VRF-NBI_Results.jpg) | Final results obtained from the VRF-NBI process with evaluation metrics. |

---

## 📬 Contact

<a href="mailto:matheusc_pereira@hotmail.com">
  <img src="https://i.ibb.co/k6Ddn36k/email.png" alt="E-mail" height="60"/>
</a>
<a href="https://www.linkedin.com/in/matheuscostapereira/">
  <img src="https://i.ibb.co/Kx4rZxdr/linkedin.png" alt="LinkedIn" height="60"/>
</a>
<a href="https://scholar.google.com.br/citations?user=1iDBIzYAAAAJ&hl=en-us">
  <img src="https://i.ibb.co/SwsRKK1t/scholar.png" alt="Google Scholar" height="60"/>
</a>
<a href="https://lattes.cnpq.br/7025666927284220">
  <img src="https://i.ibb.co/1fMjS38j/lattes.png" alt="Lattes" height="60"/>
</a>

---

> _Feel free to open issues or PRs, or reach out for collaboration or questions!_
