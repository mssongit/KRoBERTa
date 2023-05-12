## KRoBERTa

## 한국어 RoBERTa 모델 생성


Huggingface Model Download

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
