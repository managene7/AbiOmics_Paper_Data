# AbiOmics: An End-to-End Pipeline to Train AI Models for the Classification of Plant Abiotic Stresses Using Transcriptomic Profiling Data

## Abstract
Abiotic stress is a primary constraint on global crop productivity, reducing potential yields by up to 70%. While advanced sensing and imaging technologies can detect physiological decline, they often fail to discriminate among specific stressor types, a critical requirement for precise agricultural management. Transcriptomic profiling offers a high-dimensional solution to this diagnostic bottleneck, given the rapid and sensitive shifts in gene expression that occur upon stress onset. In this study, we developed a new method to diagnose plant abiotic stress by classifying stress types using AI models trained on transcriptomic profiling data. For a broader applicability of the method, we also developed a robust pipeline, AbiOmics, that can train AI models to identify and distinguish plant abiotic stresses. We used four major abiotic stressors, salt, cold, heat, and drought, to test the method. Using a curated metadata collection of 1,243 Arabidopsis leaf transcriptomes from public databases, we identified 320 stress-specific marker genes by differential expression and confirmed their functions using Gene Ontology (GO) enrichment analyses. A single-layer perceptron was trained on these features using five-fold cross-validation. The model achieved a macro-average F1-score of 0.90 and an overall accuracy of 91% during cross-validation, with 93% accuracy on an independent test set. Furthermore, the model demonstrated the capacity to generalize to multi-stress conditions, successfully identifying both heat and salt signatures in combinatorial treatment samples. Our results provide the first transcriptomic-based diagnostic tool capable of discriminating among abiotic stressors. This approach offers a foundation for high-confidence stress labeling in AI-driven crop management and provides a quantitative molecular framework for precision breeding under global climate change.

<img width="896" height="314" alt="image" src="https://github.com/user-attachments/assets/79be35b9-a4d0-4b5a-9577-e557af342983" />

## Usage
This code was developed with Python 3.10.12.
To run the code, first install the Python packages listed in requirements.txt.
The code can be run with Jupyter Notebook.

Model training and validation codes can be performed with the "main_training_and_evaluation.ipynb" file.
PCA and t-SNE analyses can be performed using the "PCA_and_t-SNE_analysis.ipynb" file.

If you have any questions, email to: minkju3003@gmail.com
