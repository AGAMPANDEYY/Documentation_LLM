
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

-Contains JSONL files for Statute identification

format-

id [string]: id/name of the fact instance / section instance
text [list[string]]: text in the form of list of sentences (each sentence is a string)
labels [list[string] / null]: gold-standard labels (not needed for inference) 

- ### For role labelling of sentences such as identification of arguements, judgments by panels, labelling conversation (**Web Crawling se dataset**)

legal judgments from the Supreme Court of India,crawled from the website of Thomson Reuters Westlaw India
(http://www.westlawindia.com).We crawled 53,210 documents in total

-i) Criminal–16 documents
-(ii)Land and property–10 documents 
-(iii)Constitutional–9 documents
-(iv)Labour and Industrial–8 documents
-(v)Intellectual Property Rights–7 documents

Rheotorical Role Labels will act like-

<img width="413" alt="image" src="https://github.com/AGAMPANDEYY/Documentation_LLM/assets/94832116/c923fa3a-f0a3-4a3b-bed8-f057fe518e30">


- ### Court Judgment Prediction (ILDC Dataset)[Binary Text Classification]: Predicting whether the claims/petitions of a court case will be accepted/rejected

large corpus of 35k Indian Supreme Court cases annotated with original court decisions.
