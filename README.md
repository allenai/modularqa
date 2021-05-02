# ModularQA
ModularQA is a QA system that answers complex multi-hop and discrete reasoning questions by decomposing them into sub-questions answerable by two sub-models: a neural factoid single-span QA model and a symbolic calculator. These sub-questions and answers provided by the sub-model provide a natural language explanation of the
model’s reasoning. This system is designed and trained based on the Text Modular Networks framework where the decompositions are generated in the language of the sub-models without needing annotated decompositions. For more details, refer to the [paper](https://www.semanticscholar.org/paper/0e1d82d24d58433ce9e211551605a0bfd296624f).



## Paper
```
Text Modular Networks: Learning to Decompose Tasks in the Language of Existing Models
Tushar Khot, Daniel Khashabi, Kyle Richardson, Peter Clark, Ashish Sabharwal
NAACL 2021
```
Bibtex:
```
@inproceedings{WhatsMissing19,
  title={Text Modular Networks: Learning to Decompose Tasks in the Language of Existing Models},
  author={Tushar Khot, Daniel Khashabi, Kyle Richardson, Peter Clark, Ashish Sabharwal},
  booktitle={NAACL},
  year={2021}
}
```


## Demo
[https://modularqa-demo.apps.allenai.org/](https://modularqa-demo.apps.allenai.org/)

Note that responses might be slow

## Data
We used the following subsets of HotpotQA and DROP to train and evaluate our models
 * [HotpotQA](https://ai2-public-datasets.s3.amazonaws.com/modularqa/hotpot_subset.zip)
 * [DROP](https://ai2-public-datasets.s3.amazonaws.com/modularqa/drop_subset.zip)
 * [DROP Evaluation Partitions](https://ai2-public-datasets.s3.amazonaws.com/modularqa/drop_partitions.zip)


[NextGen Training Data](https://ai2-public-datasets.s3.amazonaws.com/modularqa/modularqa_nextgen_train.zip):
The decomposition chains generated from these DROP+HotpotQA subsets. These chains were used to train the NextGen model.


## Models
To be updated soon

## Code
To be updated soon

