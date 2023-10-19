# SOP for Project

## 1-Writing Code using LLAMA 70B chat model 

"TheBloke/Llama-2-70B-chat-GPTQ"
https://github.com/NisaarAgharia/Indian-LawyerGPT/blob/main/Inference_Code/Faster-llm-inference_Code.ipynb

## 2- Finetuining PEFT using LORA config
https://github.com/NisaarAgharia/Indian-LawyerGPT/blob/main/Inference_Code/Inference_LawyerGPT_Finetune_falcon7b_Indian_Law_Data.ipynb

## 3-Method for deployment of LLM code on AWS cloud service (SaaS Service) on Amazon Sagemaker Notebook:

Here in the documentation, Amazon Sagemaker (AWS) is used to deploy our LLM Model and then Gradio is used for UI of chatbot (our's will Be done by frontend developers)
In the code, we need to change the model id in the config ={......}

https://github.com/NisaarAgharia/Indian-LawyerGPT/blob/main/Inference_Code/sagemaker-notebook.ipynb
https://huggingface.co/blog/sagemaker-huggingface-llm
