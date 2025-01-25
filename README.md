# Computational Biology Analysis

Welcome to the **Computational Biology Analysis** repository! This project is designed to provide a hands-on introduction to molecular dynamics (MD) analysis using Python, with an emphasis on learning fundamental principles and applying them in a way that prepares you for work in academic labs. The repository includes three examples that progressively build knowledge and skills, starting from simple concepts to more advanced topics.

---

## **What Is Alanine Dipeptide?**

Alanine dipeptide is a **small molecular model** used widely in molecular dynamics and computational biology. It consists of two alanine residues linked by a peptide bond and is often capped with:

- **Acetyl group (ACE)** at the N-terminus.
- **N-methyl group (NME)** at the C-terminus.

### **Key Features**
1. **Small Size**: Composed of only 22 atoms, making it computationally inexpensive to simulate and analyze.
2. **Simplified Backbone**: Includes the fundamental structural features of a peptide backbone, such as nitrogen (N), alpha carbon (Cα), and carbonyl carbon (C).
3. **Torsion Angles**:
   - **Phi (ϕ)**: Rotation around the N-Cα bond.
   - **Psi (ψ)**: Rotation around the Cα-C bond.
   - These angles define the conformational states of the molecule and are crucial for understanding protein structure.

### **Why It’s Used**
- **Educational Model**: Simplifies the study of backbone flexibility and torsion angles.
- **Energy Landscapes**: Helps map energy variations as a function of ϕ/ψ angles.
- **Benchmarking**: Frequently used to validate molecular dynamics software and force fields.

---

## **What Are PSF and DCD Files?**

### **PSF (Protein Structure File)**
- **Definition**: A file format that describes the **topology** of a molecular system.
- **Contents**:
  - Atom types, charges, and masses.
  - Bonds, angles, and dihedrals.
- **Role**: Acts as a "blueprint" of the molecular system for simulations and analysis.

### **DCD (Dynamic Coordinate Data)**
- **Definition**: A binary file format that stores **trajectory data**, capturing the time evolution of atomic positions during a simulation.
- **Contents**:
  - 3D coordinates of all atoms over time.
- **Role**: Provides the dynamic component of the system, enabling analysis of motion, flexibility, and interactions.

---

## **What Is a Ramachandran Plot?**

- **Definition**: A plot that visualizes the **torsion angles** (ϕ and ψ) of residues in a protein or peptide.
- **Purpose**: To study the conformational states and secondary structure of a molecule.
- **Phi (ϕ)**: Angle around the N-Cα bond.
- **Psi (ψ)**: Angle around the Cα-C bond.

### **How It’s Used**
- Identify common conformations, such as **alpha-helices** and **beta-sheets**.
- Detect unusual or disallowed conformational states.

---

## **Workflow Overview**
This repository includes three examples:

1. **Simple Example: Alanine Dipeptide**
   - Learn to compute and visualize torsion angles.
   - Generate a Ramachandran plot.

2. **Moderate Example: Protein RMSD Analysis**
   - Download the **2HHB** hemoglobin structure.
   - Analyze structural deviations over time using RMSD.

3. **Advanced Example: Protein-Ligand Interactions**
   - Explore hydrogen bonds, contact distances, and solvent-accessible surface area (SASA).
   - Perform clustering or PCA to analyze conformational changes.

---

## **Repository Structure**
```
computational-biology-analysis/
├── data/         # Dataset files (e.g., PDB, trajectories).
├── notebooks/    # Jupyter Notebooks for each example.
├── results/      # Plots and output files.
└── README.md     # Project overview.
```

---

## **Getting Started**

### **Prerequisites**
- Python 3.8+
- Install required packages:
  ```bash
  pip install MDAnalysis MDAnalysisTests biopython matplotlib seaborn numpy pandas scikit-learn nglview
  ```

### **How to Run the Examples**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/computational-biology-analysis.git
   cd computational-biology-analysis
   ```
2. Open the Jupyter Notebooks in the `notebooks/` folder:
   ```bash
   jupyter notebook
   ```
3. Follow the markdown explanations and execute the code cells.

---

## **Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests.

