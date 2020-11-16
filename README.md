# Text Classification Pytorch
This repo is meant to be an example of how to configure a pipeline for text classification with PyTorch and a custom dataset.
**WIP**: The final training stage is not yet fully functional!

## Textorch
In order to process the data from a **.csv**, it is used *torchtext.data.TabularDataset*. This class transforms **.csv**, **.tsv** or **.json** files of training, validation or testing in Datasets. 

*torchtext.data.Fields* are needed in order to define the structure or the dataset and the **Tokenizer** that is going to be used.

Finally, *torchtext.data.BucketIterator* transforms the data to be ready for a training or test stage.