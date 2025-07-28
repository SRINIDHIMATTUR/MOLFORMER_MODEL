# MOLFORMER_MODEL
Molecular Property Prediction Using Transformer-Based MoLFormer Model on SMILES Representations
This project focuses on developing a machine learning model for predicting molecular properties directly from SMILES (Simplified Molecular Input Line Entry System) strings using transformer-based architectures, specifically MoLFormer. The goal is to improve predictive accuracy and generalization across various chemical datasets, addressing the limitations of traditional methods in drug discovery and material science.

Project Overview
The cheminformatics discipline applies computational methods to store, analyze, and visualize chemical information. SMILES notation, which encodes molecular structures as linear ASCII strings, is particularly well-suited for natural language processing (NLP) methods. This project leverages the power of transformer models, widely used in NLP for contextual linkages and long-range dependencies, to interpret molecular sequences and forecast properties like solubility, toxicity, bioactivity, and reactivity.

A key aspect of this research is the integration of a robust MLOps (Machine Learning Operations) infrastructure to ensure reproducibility, dependability, and maintainability of the models throughout their lifecycle.

Problem Statement
The primary challenge is to develop a machine learning model capable of predicting molecular properties directly from SMILES strings using transformer-based architectures (MoLFormer) to improve predictive accuracy and generalization across various chemical datasets. Traditional methods often lack scalability and interpretability.

Motivation
Modern drug discovery demands interpretable, scalable, and accurate models that can:

Explain why certain molecular structures exhibit specific properties.

Guide medicinal chemists in rational drug design.

Provide confidence estimates for predictions.

Identify key structural features for optimization.

Objectives
Develop Interpretable MoLFormer: Create a transformer-based architecture with built-in interpretability features.

Implement Attribution Methods: Design molecular substructure attribution techniques.

Create Visualization Tools: Develop novel chemical interpretability visualization methods.

Build Interactive Platform: Construct a user-friendly dashboard for chemists.

Tune MoLFormer: Predict molecular properties on benchmarks such as ESOL, FreeSolv, and QM9.

Develop Scalable Pipeline: Facilitate reproducible model life cycle management with GitHub Actions, Docker, and MLflow for SMILES string preparation and inference.

Scope
This research encompasses the development of a comprehensive MoLFormer-based prediction system capable of forecasting multiple molecular properties simultaneously. It integrates a complete MLOps pipeline featuring automated CI/CD workflows and seamless connectivity to major molecular databases (ChEMBL, PubChem, ZINC). The investigation includes both batch processing for large-scale virtual screening and real-time prediction interfaces, complemented by advanced model interpretability features and comprehensive benchmarking.

Exclusions: This research explicitly excludes laboratory validation of computational predictions, retrosynthetic analysis and synthesis pathway generation, and three-dimensional molecular structure prediction or quantum mechanical property calculations.

Project Team
This project was submitted by:

Pranav (1BM22A1090)

Srujan B J (1BM22A1134)

Sriharsha K (1BM22A1131)

Srinidhi S Mattur (1BM22A1132)

Under the Guidance of:

Dr. Seemanthini K (Associate Professor, Dept. of MEL, BMSCE, Bengaluru - 19)

Department: Machine Learning (UG Program: B.E. in Artificial Intelligence and Machine Learning)
Institution: B.M.S. College of Engineering (An Autonomous Institute, Affiliated to VTU), Bengaluru - 560 019.
University: Visvesvaraya Technological University, Belagavi - 590 018, Karnataka.

Technologies and Methodologies
Core Model: Transformer-Based MoLFormer

Molecular Representation: SMILES (Simplified Molecular Input Line Entry System)

Operational Framework: MLOps (Machine Learning Operations)

CI/CD workflows (e.g., GitHub Actions)

Containerization (e.g., Docker)

Experiment Tracking/Lifecycle Management (e.g., MLflow)

Databases (Connectivity): ChEMBL, PubChem, ZINC

System Architecture (Conceptual)
The system is designed as a Molecular Screening Platform that takes SMILES strings as input, processes them through a MoLFormer model (involving Attention, Feed Forward, and Positional Encoding layers), and outputs predictions for properties like Solubility, Toxicity, and Bioactivity.

Literature Review (Key Influences)
The project builds upon foundational work in cheminformatics and transformer architectures, including:

SMILES: Weininger, 1988

Open Babel: O'Boyle et al., 2011

MoLFormer: Rong et al., 2022

Transformer Architecture: Vaswani et al., 2017

SMILES Transformer: Honda et al., 2019

ChemBERTa: Grand et al., 2020

MoleculeNet: Wu et al., 2018

Neural Message Passing Networks (MPNNs): Gilmer et al., 2017

Molecular Representation Analysis: Yang et al., 2019

PotentialNet: Feinberg et al., 2018

In Silico Drug Design Reviews: Brown, 2020

GNNs for Molecular Property Prediction: Li et al., 2021

Self-supervised Learning on Molecular Graphs: Lin et al., 2020

ZINC Database: Irwin & Shoichet, 2005
