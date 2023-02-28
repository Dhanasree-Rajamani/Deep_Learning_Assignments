Build a Chat GPT like application using Gradio and Google Flan t5 Large hugging face : 

Using the Google flan T5 Large instead of the Google flan T5 XL because the T5 large model is trained with 780M parameters and the T5 xl model is trained with 3B parameters, which requires much more RAM than the large model. My colab did not have the required RAM, so using the large training model.

The purpose of using the T5 model is text summarization, which is trained end-to-end with text as input as modified text as output. This protects sensitive texts, while preserving it's business utility. These are used for instruction finetuning, multitask instruction finetuning, chain-of-thought finetuning

Used Gradio for UI, The document below contains some screenshots of the application built

(Executable) Colab link : https://colab.research.google.com/drive/17sFxIM-gNrf1WQAK7g3QhCr1TLAPKzUd?usp=sharing

Output Screenshots :  https://docs.google.com/document/d/1SeMbD89H-mOMEM-1RW7HGT-iQ2fWWv0DFlbPsN_Qn9c/edit?usp=sharing
