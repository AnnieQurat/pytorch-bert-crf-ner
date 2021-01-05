# dataset:
   the dataset is in the directory<br />
   glove embeddings are used and manually uploaded to models folder


# reference:<br />

   paper:<br />
           Neural Architectures for Named Entity Recognition<br />
           End-toEnd Sequence labeling via BLSTM-CNN-CRF<br />
           https://arxiv.org/abs/1603.01360<br />
           
   code:<br />
           https://github.com/glample/tagger<br />
# usage:
   python train.py for training the pretrained model<br />
   implementation.ipynb on Jupyter Notebook (errors not fixed yet)<br />
   'pip install visdom' for plotting

# performance

   ![alt text](https://github.com/AnnieQurat/pytorch-bert-crf-ner/blob/main/progress-epochs/200%20epochs.png)
   ![alt text](https://github.com/AnnieQurat/pytorch-bert-crf-ner/blob/main/progress-epochs/5000%20epochs.png)
   
   f1 91.00%
