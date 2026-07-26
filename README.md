## SMILES Validator

A Python tool for validating SMILES strings and computing basic molecular properties using RDKit.

## Project information 
- **Phase :** 1 - Python Foundation
- **Author:** Suraj Gade
- **GitHub:** github.com/surajgade17
- **Goal:** Cheminformatics & AI Drug Discovery

## What is SMILES?
SMILES (Simplified Molecular Input Line Entry System) is a way to represent  chemical molecules as text strings.

| Molecule | SMILES |
|----------|--------|
| Ethanol  | CCO    |
| Aspirin  | CC(=O)Oc1ccccc1C(=O)O |
| Benzene  | c1ccccc1 |
| Caffeine | CN1C=NC2=C1C(=O)N(C(=O)N2C)C |

## Features
- Validate single SMILES string
- Get basic molecular properties
- Batch validate multiple SMILES
- Compute molecular formula and weight
- Count number of atoms

## Sample Output
```
==================================================
SMILES VALIDATOR — Suraj Gade
==================================================

SINGLE SMILES VALIDATION:
  [Valid ✅] CCO
  [Valid ✅] CC(=O)Oc1ccccc1C(=O)O
  [Valid ✅] c1ccccc1
  [Invalid ❌] INVALID_SMILES
  [Valid ✅] CN1C=NC2=C1C(=O)N(C(=O)N2C)C

BASIC INFO — Aspirin:
  SMILES: CC(=O)Oc1ccccc1C(=O)O
  Formula: C9H8O4
  Weight: 180.16
  Atoms: 13

BATCH RESULTS:
  Valid ✅   | CCO
  Valid ✅   | CC(=O)Oc1ccccc1C(=O)O
  Valid ✅   | c1ccccc1
  Invalid ❌ | INVALID_SMILES
  Valid ✅   | CN1C=NC2=C1C(=O)N(C(=O)N2C)C
```

## Tools Used
- Python 3
- RDKit
- Google Colab

## How to Run
1. Open Google Colab
2. Install RDKit:
   pip install rdkit-pypi
3. Run smiles_validator.py

## What I Learned
- How SMILES strings represent molecules
- Using RDKit to parse and validate molecules
- Computing basic molecular properties
- Writing clean Python functions
- Handling invalid inputs gracefully

## Connect
- LinkedIn: linkedin.com/in/surajgade
- GitHub: github.com/surajgade17
