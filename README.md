# Name Entity Recognition for Medical Documents  

## Overview  
This project implements a Named Entity Recognition (NER) system to extract and classify medical entities from clinical documents. A custom BiLSTM-CRF model is developed, optimized for handling specialized medical terminology.  

Key Features:  
- **BiLSTM-CRF Model**: A robust architecture designed for medical entity extraction.  
- **Custom Text Preprocessing**: A pipeline tailored for medical text, handling specialized terminology and abbreviations.  
- **Automated Annotation Tool**: A tool to streamline the labeling process, significantly reducing manual effort.  

## Dataset  
The dataset for this project is sourced from Kaggle and contains labeled clinical notes. You can access the dataset here:  
[Kaggle Dataset: Medical NER Dataset](https://www.kaggle.com/datasets/sushilkumarinfo/covid-ner-data-set)  

## Project Structure  
All coding and experimentation are conducted in a single Jupyter notebook for simplicity and clarity.  

- **`ner_medical_documents.ipynb`**: This notebook includes the preprocessing, model development, training, evaluation, and result visualization.  

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo/medical-ner.git  
   cd medical-ner

   ```
   ```bash
   pip install -r requirements.txt

## Usage
1. Follow the step-by-step workflow in the notebook to:
* Preprocess the dataset.
* Train the BiLSTM-CRF model.
* Evaluate model performance.
* Use the automated annotation tool for labeling new data.

## Results
The BiLSTM-CRF model effectively identifies medical entities such as diseases, medications, and treatments with high precision and recall. Detailed metrics are available in the notebook.
   

    
