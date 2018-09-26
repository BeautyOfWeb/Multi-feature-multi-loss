A multi-feature multi-loss neural network model for predicting the disease progression of multiple myeloma.

This is my solution (https://www.synapse.org/#!Synapse:syn11310698/wiki/495700) for Multiple Myeloma DREAM Challenge (https://www.synapse.org/#!Synapse:syn6187098/wiki/401884)

My results were ranked 4th in both sub-challenge 2 and sub-challenge 3.

I implemented the model using PyTorch.

Instructions:
1. Run prepare_data-new.ipynb to preprocess microarray and RNAseq expression training data
2. Run prepare_snv.ipynb to preprocess snv training data
3. For subchallenge 2, run exp-train.ipynb
4. For subchallenge 3, run snv-exp-train.ipynb
5. workflow.ipynb is used to bulk submit jobs for training in local computer cluster (not necessary)
6. Folder dl/ contains some useful functions used in exp-train.ipynb and snv-exp-train.ipynb
