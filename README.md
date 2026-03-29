# ML Experiments

Hands-on ML experiments — learning by doing, one notebook at a time.

## Experiments

| # | Experiment | Status | What I Learned |
|---|-----------|--------|---------------|
| 01 | [Llama 3.2 Fine-Tuning](01-llama-fine-tuning/) | In Progress | LoRA/PEFT, SFT, quantization, the HuggingFace ML stack |

## How to Run

Each experiment folder contains a Colab notebook. Click the "Open in Colab" badge or:

1. Go to `https://colab.research.google.com/github/vishnujayvel/ml-experiments/blob/main/<path-to-notebook>`
2. Runtime → Change Runtime Type → T4 GPU → Save
3. Run cells with Shift+Enter

## Stack

These experiments use the open-source HuggingFace ecosystem:

```
unsloth (speed) → trl + peft (training + LoRA) → transformers (models) → PyTorch (compute) → CUDA (GPU)
```
