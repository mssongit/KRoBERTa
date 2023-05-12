## KRoBERTa

## 한국어 RoBERTa 모델 생성


Huggingface Model Download

https://huggingface.co/mssongit/KRoBERTa-base/tree/main

## How to use

### Requirements

- `pytorch`
- `transformers >= 4.5.1`
- `loguru ~=0.5.3
- `tqdm ~=4.62.3
- 'datasets >= 1.13.3'



```python
from transformers import AutoTokenizer, AutoModel

# Base Model

tokenizer = AutoTokenizer.from_pretrained("mssongit/KRoBERTa-base")

model = AutoModel.from_pretrained("mssongit/KRoBERTa-base")


## Tokenizer Train

BBPE Tokenizer, Vocab size = 72000
'''

## Base Model Loss

![image](https://github.com/mssongit/KRoBERTa/assets/95903180/9edac05f-7b8a-4fed-8acb-3ccd99ff6c78)
