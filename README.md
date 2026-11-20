# NandiBERT examples

Small, runnable examples for fine-tuning `FrontiersMind/NandiBERT-150M` & `FrontiersMind/NandiBERT-450M`. Each notebook explains the task, inspects real data, trains a task head, and evaluates it.

## Setup

Use Python 3.10+ and a CUDA GPU. From this directory:

```bash
pip install -r requirements.txt
```

The model card asks for Transformers 5.x and `trust_remote_code=True`. Install the version compatible with the checkpoint's custom code.

## Notebooks

- `glue/finetune_sst2.ipynb`: sentence sentiment classification.
- `glue/finetune_mrpc.ipynb`: sentence-pair paraphrase classification.
- `glue/finetune_mnli.ipynb`: three-way natural language inference.
- `ner/finetune_naamapadam.ipynb`: Hindi NER with Naamapadam.