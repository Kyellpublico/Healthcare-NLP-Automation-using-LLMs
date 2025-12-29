# Medical Transcription Organizer using LLMs (OpenAI API)

## Project Overview
Medical professionals often document patient encounters using unstructured clinical transcriptions. 
This project demonstrates how Large Language Models (LLMs) can be used to automatically extract key medical information and map treatments to standardized ICD-10 codes, supporting downstream use cases such as insurance claims processing and medical reporting.

The solution uses the OpenAI API to:
- Extract patient age and recommended treatment from free-text medical transcriptions
- Automatically retrieve relevant ICD-10 codes based on extracted treatments
- Structure the extracted data into a clean, analysis-ready dataset

## Business Use Case
Healthcare organizations frequently handle large volumes of unstructured medical notes. 
Manual data extraction is time-consuming and error-prone. This solution demonstrates how AI-driven automation can:
- Reduce administrative workload
- Improve coding accuracy
- Support scalable medical documentation workflows

## Tools & Technologies
- Python
- Pandas
- OpenAI API (GPT-4o-mini)
- Prompt Engineering
- 
## Project Workflow
1. Load anonymized medical transcription data
2. Use LLM function calling to extract:
   - Patient age
   - Recommended treatment or procedure
3. Query the LLM to retrieve ICD-10 codes for the extracted treatment
4. Combine results into a structured dataset for downstream use

## Output
The final output is a structured table containing:
- Medical specialty
- Patient age
- Recommended treatment or procedure
- Associated ICD-10 code(s)

## Notes
This project was originally completed as part of a DataCamp learning program and was independently refactored and documented to reflect real-world AI automation and healthcare data processing standards.
