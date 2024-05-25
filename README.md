# Medical-AI

The Medical Data Analyzer is a powerful tool designed to assist healthcare professionals in extracting valuable information from clinical text. By leveraging natural language processing (NLP) techniques, specifically the medspaCy library (built on top of spaCy), this analyzer can process unstructured medical data and provide insights related to patient diseases, diagnoses, and prescribed medications.

(https://github.com/saimenogm/Medical-AI/assets/32343117/201926c6-03c3-480e-8aef-097bc19cbada)

## Features

<b>1. Clinical Text Preprocessing </b>
Clean and preprocess raw clinical text to remove noise, abbreviations, and irrelevant information.
Normalize text (e.g., convert uppercase to lowercase, handle misspellings).
<b>2. Sentence Segmentation<b>
Split clinical notes into individual sentences for further analysis.
Ensure accurate context extraction by breaking down lengthy text.
<b>3. Named Entity Recognition (NER)</b>
Identify relevant entities (concepts) within clinical text.
<b>4. Extract the following vital information </b>
Diseases and Conditions: Recognize mentions of specific diseases or medical conditions (e.g., “hypertension,” “diabetes mellitus”).
Diagnoses: Capture diagnostic statements (e.g., “patient diagnosed with pneumonia”).
Medications: Extract information about prescribed drugs (e.g., “prescribed lisinopril 10 mg daily”).

Requirements
The following packages are required and installed:
- SpaCy
- MedSpacy
