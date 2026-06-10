# NeuralNetworks-Group6

## Description

This repository contains the complete work of Group 6 for the **Neural Networks (2019781)** course.
The project is finished and includes:

- Development and comparison of Shallow MLP and Deep Neural Network models.
- Data generation and augmentation using GAN/Autoencoder approaches.
- Results analysis and final deliverables in notebooks and report documents.
- Course presentation materials.

## Repository Structure

```text
NeuralNetworks-Group6/
|-- README.md
|-- ClassPresentations/
|   |-- DeepNN/
|   |   |-- deep-NN-06.ipynb
|   |   |-- deep-NN-06-inception.ipynb
|   |-- ShallowNN/
|       |-- shallow-NN-6.ipynb
|-- project/
|   |-- data/
|   |   |-- microbioma_aumentado_gan_CLR.csv
|   |   |-- otu_genus_clr_prevfiltered-hp.csv
|   |   |-- otu_genus_clr_prevfiltered-nhp.csv
|   |   |-- sample_metadata_binary-hp.csv
|   |   |-- sample_metadata_binary-nhp.csv
|   |-- final/
|   |   |-- Notebooks/
|   |   |   |-- Analisis_Resultados_Deep_vs_Shallow_actualizado.ipynb
|   |   |   |-- Entrega2-DeepNeuralNetwork.ipynb
|   |   |   |-- Entrega2-GANComplementada.ipynb
|   |   |   |-- Entrega2ShallowMLP_DatosGAN.ipynb
|   |   |-- report/
|   |-- progress/
|   |   |-- notebooks/
|   |   |   |-- a-preanalisis.ipynb
|   |   |   |-- b-hp_eda_featuring_engineering.ipynb
|   |   |   |-- c-no_hp_eda_featuring_engineering.ipynb
|   |   |   |-- Entrega1Autoencoders.ipynb
|   |   |   |-- Entrega1ShallowGAN.ipynb
|   |   |   |-- Entrega1ShallowMLP.ipynb
|   |   |   |-- Shalow_vae_gan_microbiome.ipynb
|   |   |-- report/
|   |-- proposal/
```

## Final Deliverables

- Final notebooks in `project/final/Notebooks/`.
- Final report in `project/final/report/`.
- Evidence of the development process in `project/progress/`.

## How to Run the Notebooks

1. Create and activate a Python virtual environment (recommended).
2. Install the base dependencies:

```bash
pip install jupyter notebook pandas numpy scikit-learn matplotlib seaborn tensorflow
```

3. Open Jupyter and run the notebooks in the following suggested order:

- Exploration/preparation: `project/progress/notebooks/`
- Final modeling: `project/final/Notebooks/`
- Comparative analysis: `project/final/Notebooks/Analisis_Resultados_Deep_vs_Shallow_actualizado.ipynb`

## Team Members

- Laura Camila Giron Pinto - lgironp@unal.edu.co
- David Felipe Marin Rosas - dmarinro@unal.edu.co
- Nicolas Martinez Lopez - nmartinezl@unal.edu.co
- Diego Esteban Morales Granados - dimorales@unal.edu.co
- Sergio Ivan Motta Doncel - smottad@unal.edu.co

## Course

- Subject: Neural Networks
- Group: 6
- Year: 2026
