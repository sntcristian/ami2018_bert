# Automatic Misogyny Identification for Italian tweets with UmBERTo
Automatic Misogyny Identification (AMI) is a new task in Natural Language Processing that belongs to the domain of Text Classification and it has been proposed for the first time by Fersini et al. at the Evalita 2018 evaluation campaign [1]. In this Notebook we will show how we fine-tuned UmBERTo [2], a pretrained language model based on RoBERTa [3], on the same dataset of the shared task. 
This notebook reports how, after fine-tuning the model for binary classification on a set of tweets labelled with misogyny value (either 1 or 0), the model was able to beat the performances of the best model in the challenge (*bakarov.c.run2*) and achieve state-of-the-art performances.

# Accuracy on AMI EvalITA 2018 dataset
 Model | Accuracy 
--- | --- 
bakarov.c.run2 | 0.844 
--- | --- 
ami_umberto | 0.868
