# Conversational-Question-Answering

Notebook1:
Name of the notebook: CoQA_DrQAModel.ipynb

Steps to produce the results:
1. Load the dev and train json files submitted along with the report.
2. glove.6B.300d file needs to be downloaded from the link https://nlp.stanford.edu/projects/glove. Since the size of the file is 990MB, we have not included it in our submission.
3. Run all code blocks one after the other till the final block is reached. 
4. Once the final block is run, result is generated as result.json.
5. Run the result.json against the evaluation script to reproduce the results.

Notebook2:
Name of the notebook: CoQA_Seq2SeqModel.ipynb

Steps to produce the results:
1. Load the dev and train json files submitted along with the report
2. Run all code blocks one after the other till the final block is reached. 
3. Once the final block is run, result is generated as result.json.
4. Run the result.json against the evaluation script to reproduce the results.

evaluation_script.py 
This file is used to evaluate our results with CoQA dataset and generate in domain and out of domain results.
