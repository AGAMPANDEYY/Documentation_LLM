
### Dataset Generation

<img src="https://github.com/AGAMPANDEYY/Documentation_LLM/assets/94832116/d8311065-9b8f-4f53-8c37-1e720cba9457" width=300 >

  **JSONL Dataset**
  
- Articles of Constitution **12k**
- Constitution of India -- Q/A format (GPT-4)-- **1k**
- Sythetic data generation using Claude 2 (Advanced Prompts- containes Case Citations, Bench details,Comment and Analysis of cases)
- Chain of thoughts (unsure about this rn)
- Datasets generated -**16k**


# DATASET & LINKS

### Contains JSONL files for Statute identification

https://zenodo.org/records/6053791 

format-

id [string]: id/name of the fact instance / section instance
text [list[string]]: text in the form of list of sentences (each sentence is a string)
labels [list[string] / null]: gold-standard labels (not needed for inference) 

- ### For role labelling of sentences such as identification of arguements, judgments by panels, labelling conversation (**Web Crawling se dataset**)

legal judgments from the Supreme Court of India,crawled from the website of Thomson Reuters Westlaw India
(http://www.westlawindia.com). 53,210 documents in total

-i) Criminal–16 documents
-(ii)Land and property–10 documents 
-(iii)Constitutional–9 documents
-(iv)Labour and Industrial–8 documents
-(v)Intellectual Property Rights–7 documents

Rheotorical Role Labels will act like-

<img width="413" alt="image" src="https://github.com/AGAMPANDEYY/Documentation_LLM/assets/94832116/c923fa3a-f0a3-4a3b-bed8-f057fe518e30">

### Train  Data
https://storage.googleapis.com/indianlegalbert/OPEN_SOURCED_FILES/Rhetorical_Role_Benchmark/Data/train.json

### Test Data

https://storage.googleapis.com/indianlegalbert/OPEN_SOURCED_FILES/Rhetorical_Role_Benchmark/Data/dev.json


- ### Court Judgment Prediction (ILDC Dataset)[Binary Text Classification]: Predicting whether the claims/petitions of a court case will be accepted/rejected

  

large corpus of 35k Indian Supreme Court cases annotated with original court decisions.

### Q&A 150 JSONL

https://github.com/NisaarAgharia/Indian-LawyerGPT/blob/main/dataset/150_lawergpt_dataset_qna_v1_train.jsonl

https://github.com/NisaarAgharia/Indian-LawyerGPT/blob/main/dataset/50_lawergpt_dataset_qna_v1_train.jsonl

### Constitution Q&A JSONL

https://github.com/NisaarAgharia/Indian-LawyerGPT/blob/main/dataset/933prompts_constitution_train.jsonl

### 21 Case Studies  and 19 Articles .txt files

https://github.com/NisaarAgharia/Indian-LawyerGPT/tree/main/dataset/21

https://github.com/NisaarAgharia/Indian-LawyerGPT/tree/main/dataset/Refined%20Reports%20Article%2019

### Prompts 

https://github.com/NisaarAgharia/Indian-LawyerGPT/tree/main/dataset/prompts

### For Legal doc Summarizer

<img width="555" alt="image" src="https://github.com/AGAMPANDEYY/Documentation_LLM/assets/94832116/4dce4cf4-ed0c-496c-8073-77e698eade59">

https://zenodo.org/records/7152317#.Yz6mJ9JByC0
