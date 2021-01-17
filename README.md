# Automatic Misogyny Identification for Italian tweets with UmBERTo
Automatic Misogyny Identification (AMI) is a new task in Natural Language Processing that belongs to the domain of Text Classification and it has been proposed for the first time by Fersini et al. at the Evalita 2018 evaluation campaign [1]. In this Notebook we will show how we fine-tuned UmBERTo [2], a pretrained language model based on RoBERTa [3], on the same dataset of the shared task. 
This notebook reports how, after fine-tuning the model for binary classification on a set of tweets labelled with misogyny value (either 1 or 0), the model was able to beat the performances of the best model in the challenge (*bakarov.c.run2*) and achieve state-of-the-art performances.

# Accuracy on AMI EvalITA 2018 dataset
 Model | Accuracy 
--- | --- 
bakarov.c.run2 | 0.844 
ami_umberto | **0.868**

# References
[1] Elisabetta Fersini, Deborah Nozza, and Paolo Rosso. 2018b. Overview of the evalita 2018 task on automatic misogyny identification (ami). In *Proceedings of the 6th evaluation campaign of Natural Language Processing and Speech Tools for Italian. Final Workshop (EVALITA 2018)*, Turin, Italy. CEUR.org.
[2] https://github.com/musixmatchresearch/umberto
[3] Yinhan Liu, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, Mike Lewis, Luke Zettlemoyer, and Veselin Stoyanov. 2019. Roberta: A robustly optimized BERT pretraining approach. ArXiv preprint 1907.11692.

