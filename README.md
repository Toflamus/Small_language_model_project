# Small_language_model_project
This is a project of my course "Deep learning Fundamentals and Practice". Note, code and other materials will be uploaded

## Learning materials

### Hugging face
[Hugging face intro-Chinese version in Zhihu](https://zhuanlan.zhihu.com/p/535100411)  
[Hugging face courses and tutorial](https://huggingface.co/learn/nlp-course/chapter1/1)  

### miniGPT: model archtecture
[mingpt](https://github.com/karpathy/minGPT)

## Pretrain 

### Dataset 
[TinyStories](https://huggingface.co/datasets/roneneldan/TinyStories)
### Tokenizer
gpt-2like Byte-Pair-Enconding(BPE) tokenizer: [roneneldan](https://huggingface.co/roneneldan/TinyStories-1M)
### Pretrain code
See the file: [Server_Training_a_causal_language_model_from_scratch_(PyTorch).ipynb](https://github.com/Toflamus/Small_language_model_project/blob/main/Server_Training_a_causal_language_model_from_scratch_(PyTorch).ipynb) This is adapted from the NLP course in hugging face. See [here](https://huggingface.co/learn/nlp-course/chapter7/6?fw=pt). 
### Model 
Right now this model and relative information of the pretain process can be found [here](https://huggingface.co/Toflamus/GPT-2_para3M)

## Finetune 
### Dataset 
[standford alpaca](https://github.com/tatsu-lab/stanford_alpaca)
### Finetune code
See file: [Server_Fineture_process.ipynb](https://github.com/Toflamus/Small_language_model_project/blob/main/Server_Finetune_process.ipynb)
### Model 
Right now this model and relative information of the pretain process can be found [here](https://huggingface.co/Toflamus/GPT-2_3M_finetuned2)
