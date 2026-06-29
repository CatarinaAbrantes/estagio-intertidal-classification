# Intertidal Species Classifier

Hierarchical deep learning pipeline for automated classification of 17 intertidal species from photographic datasets, developed during a curricular internship at CIBIO/BIOPOLIS (FCUP), 2026.

## Results
- **Balanced Accuracy:** 77.94% (83.80% with confidence threshold of 0.60)
- **Architecture:** EfficientNet-B0, two-level hierarchical classifier
- **Classes:** 17 intertidal species in 6 biological groups

## How to use
1. Open `notebook_final.ipynb` in Kaggle
2. Add datasets as input:
   - `catarinaabrantes/estagio-intertidal`
   - `catarinaabrantes/estagio-modelos-hierarquico-v5n`
3. Run sections 16–26 independently (no retraining needed — models are loaded from saved weights)

## Author
Catarina Dias de Almeida Abrantes (202306408)  
Supervisor: Fernando P. Lima  
FCUP / CIBIO-BIOPOLIS, 2026
