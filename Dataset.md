
### Dataset Generation

<img src="https://github.com/AGAMPANDEYY/Documentation_LLM/assets/94832116/d8311065-9b8f-4f53-8c37-1e720cba9457" width=300 >

  **JSONL Dataset**
  
- Articles of Constitution **12k**
- Constitution of India -- Q/A format (GPT-4)-- **1k**
- Sythetic data generation using Claude 2 (Advanced Prompts- containes Case Citations, Bench details,Comment and Analysis of cases)
- Chain of thoughts (unsure about this rn)
- Datasets generated -**16k**


# DATASET & LINKS

https://zenodo.org/records/6053791 
Contains JSONL files for 

format-

id [string]: id/name of the fact instance / section instance
text [list[string]]: text in the form of list of sentences (each sentence is a string)
labels [list[string] / null]: gold-standard labels (not needed for inference) 
