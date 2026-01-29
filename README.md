# Generative Ai and NLP Lab-1
# NLP Experiments with Transformers

## Experiments Done

### 1. Text Generation
Models used:
- BERT
- RoBERTa
- BART

Observation:
- BERT and RoBERTa do not generate proper text.
- BART generates meaningful sentences.

### 2. Fill Mask
Models used:
- BERT
- RoBERTa
- BART

Observation:
- BERT and RoBERTa correctly predict masked words.
- BART predicts reasonable words but is less accurate.

### 3. Question Answering
Models used:
- BERT
- RoBERTa
- BART

Observation:
- All base models give partial or weak answers.
- Models are not fine-tuned for question answering.

## Tools Used
- Python
- Hugging Face Transformers

## Conclusion
Model performance depends on model architecture and training objective.
