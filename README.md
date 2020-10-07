# coronawhy_lit_review_tool
CoronaWhy is a group of volunteer researchers, data scientist, engineers, and others, who are building an AI-powered literature review tool. 

At the height of the COVID-19 pandemic, more than 300 papers on SARS-CoV-2 were being published *each day*.  Built out of the CORD-19 Kaggle challenge, we realized that we needed to continue our work to produce a tool that would enable medical researchers to quickly sift through this massive amount of information.  Thus, our vision of an AI-powered literature review tool was born.

This repository constitutes a portion of my contribution to that tool.  The FAISS similarity search (utilizing SPECTER document embeddings) will be a feature in our tool allowing researchers to find papers similar to one that they select.

I'm also working on an NLP NER model to extract the sample size from papers.  This code will be updated at a later date in this repo, but can currently be found [here](https://github.com/CoronaWhy/task-ties/blob/master/task_ties/Sample_Size_Extraction_%26_Modeling.ipynb).  This model currently needs further refinement.  Training data was manually annotated via local implementation of [Doccano](https://github.com/doccano/doccano).

My work at the moment centers around refactoring the code from this NLP model (and various others) for implementation in a pipeline.

Updates forthcoming.
