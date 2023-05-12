## KRoBERTa

## 한국어 RoBERTa 모델 생성


Huggingface Model Download

## How to use

### Requirements

- `pytorch <= 1.8.0`
- `transformers >= 3.0.1`
- `emoji ~= 0.6.0`
- `soynlp ~= 0.0.493`

```python
from transformers import AutoTokenizer, AutoModel

# Base Model

tokenizer = AutoTokenizer.from_pretrained("mssongit/KRoBERTa-base")

model = AutoModel.from_pretrained("mssongit/KRoBERTa-base")
