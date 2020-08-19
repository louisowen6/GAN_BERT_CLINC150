# Semi-supervised Intent Classification with GAN-BERT

This is the code implementation of TDS Article "[Semi-supervised Intent Classification with GAN-BERT](https://towardsdatascience.com/semi-supervised-intent-classification-with-gan-bert-934d8659bca2)". The CLINC150 data is provided [here](https://github.com/clinc/oos-eval). The codes used are based on the [official repo of GAN-BERT](https://github.com/crux82/ganbert/tree/ff1a87548e8d8f11da468375d317e918c7162e20), with some minor changes and additions. All of the changes in codes are listed [here](https://github.com/louisowen6/GAN_BERT_CLINC150/blob/master/changes.txt)

# Requirements

tensorflow-gpu==1.14.0

gast==0.2.2

git+https://github.com/guillaumegenthial/tf_metrics.git

# Usage

First thing first you have to download the BERT model [here](https://storage.googleapis.com/bert_models/2018_10_18/cased_L-12_H-768_A-12.zip). Then, if you have your own GPU you can download the [Google Colab Notebook](https://colab.research.google.com/drive/1f1rVGJgwVrUXhwyV3w5cW_yjPA_twkNh?usp=sharing) and run the script inside the notebook locally or you can upload this repo to your Google Drive then run it using the Google Colab's GPU. 

# References

GAN-BERT Paper: https://www.aclweb.org/anthology/2020.acl-main.191.pdf

CLINC150 Paper: https://www.aclweb.org/anthology/D19-1131.pdf
