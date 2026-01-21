<p align="start"><img src="medical.jpeg" alt="Alt text" width="300"/></p> 

# Organizing Medical Transcriptions with LLM

Automated extraction and ICD-10 code classification of clinical information from medical transcripts using OpenAI API.

## Overview
Processes unstructured medical transcriptions to extract patient age, specialty, and treatment recommendations, then maps treatments to ICD-10 codes for standardized healthcare documentation.

## Features
- Extract structured data from natural language medical notes
- Automated ICD-10 code classification
- OpenAI API integration with prompt engineering
- Pandas-based data structuring

## Tech Stack
- Python
- OpenAI API (GPT models)
- Pandas

## Usage
```python
# Process medical transcriptions
python extract_medical_data.py
```

## Dataset
Anonymized medical transcriptions categorized by specialty (`transcriptions.csv`)

## Output
Structured DataFrame containing:
- Patient age
- Medical specialty
- Treatment recommendations
- ICD-10 codes
