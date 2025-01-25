# Computational Biology Analysis

This repository provides hands-on examples of molecular dynamics (MD) analysis using Python and popular libraries such as **MDAnalysis**. These examples are designed to help beginners understand fundamental biomolecular analysis workflows and prepare for applications in academic and research environments.

---

## Examples in This Repository

### 1. **Protein RMSD Over Time**
- **Goal**: Analyze the structural stability of a protein during a molecular dynamics simulation.
- **Key Steps**:
  - Load a protein trajectory.
  - Select the protein backbone for analysis.
  - Calculate the **Root-Mean-Square Deviation (RMSD)** of the structure over time relative to a reference (initial frame).
  - Visualize RMSD as a line plot to identify trends, such as stabilization or structural flexibility.
- **What It Teaches**:
  - How to load protein structure and trajectory files into Python using MDAnalysis.
  - Understanding RMSD as a measure of protein stability.
  - Producing insightful visualizations of molecular dynamics data.

---

### 2. **Alanine Dipeptide Analysis**
- **Goal**: Explore the conformational states of alanine dipeptide using torsion angle analysis.
- **Key Steps**:
  - Load the **PSF** (structure) and **DCD** (trajectory) files for alanine dipeptide.
  - Compute backbone torsion angles (**phi** and **psi**) for all frames of the simulation.
  - Plot a **Ramachandran Plot** to visualize conformational preferences.
- **What It Teaches**:
  - Basics of molecular trajectories and torsion angle analysis.
  - How to generate a Ramachandran plot and interpret conformational clusters.
  - Understanding secondary structure formation principles in simple peptides.

---

## Key Concepts
1. **Root-Mean-Square Deviation (RMSD)**:
   - A quantitative measure of structural deviation over time during a molecular dynamics simulation.
   - Low RMSD indicates stability, while high RMSD suggests structural changes.

2. **Torsion Angles**:
   - **Phi (ϕ)** and **Psi (ψ)** angles describe the backbone flexibility of peptides and proteins.
   - A Ramachandran plot reveals conformational preferences and potential secondary structure regions.

3. **Molecular Trajectories**:
   - Time-resolved data that capture atomic movements during simulations, allowing for dynamic analyses.

---

## Repository Structure

```plaintext
computational-biology-analysis/
├── notebooks/       # Jupyter notebooks for each example
│   ├── protein_rmsd_analysis.ipynb
│   ├── alanine_dipeptide_analysis.ipynb
├── data/            # Placeholder for trajectory and structure files
├── results/         # Plots and analysis results
└── README.md        # This README file
```

---

## Prerequisites

### Python Environment
Ensure you have **Python 3.8+** installed. The following packages are required:
- **MDAnalysis**: Molecular dynamics analysis.
- **Matplotlib**: Visualization library.
- **NumPy**: Numerical computations.

### Install Required Libraries
You can install the necessary packages via pip:
```bash
pip install MDAnalysis matplotlib numpy
```

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/computational-biology-analysis.git
   cd computational-biology-analysis
   ```

2. **Run the Notebooks**:
   Navigate to the `notebooks/` folder and launch the examples in Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. **Follow Along**:
   - Open `protein_rmsd_analysis.ipynb` for protein RMSD analysis.
   - Open `alanine_dipeptide_analysis.ipynb` for alanine dipeptide analysis.

---

## Next Steps

### Future Examples
- **Protein-Ligand Interactions**: Study hydrogen bonds, contact distances, and solvent exposure.
- **Principal Component Analysis (PCA)**: Explore global conformational changes in proteins.
- **RMSF (Root-Mean-Square Fluctuation)**: Analyze per-residue flexibility.

### Contribution
Contributions are welcome! Feel free to open issues or submit pull requests for improvements and new examples.

---

## License
This project is licensed under the **MIT License**.
