# MDM2-p53-AlphaFold3-Analysis

### About This Project

This project analyzes the **interaction** between **MDM2** and **p53** proteins using AlphaFold 3.

**Simple explanation:**
- MDM2 and p53 are very important proteins in cancer research
- These two proteins bind together (form a complex)
- We analyze this binding (interaction)
- Then we make a mutation to break this binding and verify it

### What Do  I in This Project?

**Step 1:** Download and prepare proteins
- Get MDM2 and p53 files from RCSB PDB
- Save chains in separate files

**Step 2:** Analyze the interaction area (interface)
- Which amino acids touch each other?
- Calculate interaction strength
- Find critical residues

**Step 3:** Make AlphaFold 3 predictions
- Predict MDM2 alone
- Predict p53 alone
- Predict MDM2 + p53 complex together
- Compare scores (pLDDT, PAE)

**Step 4:** Make mutation and test
- Change one critical amino acid in p53
- Predict the mutant protein complex
- Show that interaction is lost

### How To Use

1. Open Google Colab
2. Run notebooks in order (Step 1 → Step 2 → Step 3 → Step 4)
3. Connect to Google Drive (code does this automatically)
4. Results are saved to Drive
5. Download reports and attach to assignment

### Results

After each step, these are saved:
- PDB files
- Interaction tables
- Scores (pLDDT, PAE, interface score)
- Graphs and images
- Mutation effects

### Requirements

- Google Colab (free or Pro)
- Google Drive
- GPU (L4 recommended)
- High RAM (52 GB recommended)

### Authors

- Student: Melisa Ağrı
- Supervisor: Prof. Dr. Gizem Dinler Doğanay (Istanbul Technical University, Department of Molecular Biology and Genetics)

### References

- PDB ID: 1YCR (MDM2-p53 crystal structure)
- AlphaFold 3: DeepMind
- BioPython: Biopython Project
