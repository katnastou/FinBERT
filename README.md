# FinBERT

BERT model trained from scratch on Finnish.

# Release 0.2

**October 24, 2019** Beta version of the BERT base uncased model trained from scratch on a corpus of Finnish news, online discussions, and crawled data. 

Download the model here: [bert-base-finnish-uncased.zip](http://dl.turkunlp.org/finbert/bert-base-finnish-uncased.zip)

# Release 0.1

**September 30, 2019** We release a beta version of the BERT base cased model trained from scratch on a corpus of Finnish news, online discussions, and crawled data. 

Download the model here: [bert-base-finnish-cased.zip](http://dl.turkunlp.org/finbert/bert-base-finnish-cased.zip)

## Usage

If you want to use the model with the huggingface/transformers library, follow the steps in [huggingface_transformers.md](https://github.com/TurkuNLP/FinBERT/blob/master/huggingface_transformers.md)

Initial, as of yet unpublished and therefore unofficial evaluation results of the model are as follows:

### Named Entity Recognition on the FiNER data

| Model          | Accuracy |
|--------------------|----------|
| Rule-based (FiNER) | 87%      |
| BERT-Base Multilingual Cased (Google) | 88% |
| FinBERT-Base Cased  | 91% |


### PoS tagging

UD_Finnish-TDT test set, gold segmentation

| Model                         |      |
|-------------------------------|------|
| BERT-Base Multilingual Cased (Google) | 96.93% |
| FinBERT-Base Cased          | 98.45% |

