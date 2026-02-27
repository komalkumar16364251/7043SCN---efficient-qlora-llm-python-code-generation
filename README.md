# Efficient QLoRA Adaptation of a Compact LLM for Python Code Generation

This project implements efficient fine-tuning of a compact Large Language Model (LLM) for Python code generation using QLoRA (Quantized Low-Rank Adaptation). QLoRA enables parameter-efficient fine-tuning by freezing the base model weights and training low-rank adapter layers.

---

## Project Objectives

* Fine-tune a compact LLM using QLoRA
* Enable efficient Python code generation
* Reduce memory usage using quantization
* Evaluate model performance

---

## Technologies Used

* Python
* HuggingFace Transformers
* QLoRA
* PyTorch
* Google Colab

---

## Model Architecture

The project uses a Transformer-based Large Language Model with QLoRA adapters for efficient fine-tuning.

---

## Results

The QLoRA-fine-tuned model successfully generated Python code based on instructions.

### Example Output

```
def add(a, b):
    return a + b
```

### Evaluation Metrics

**BLEU: {'bleu': 0.6606328636027614, 'precisions': [0.8888888888888888, 0.75, 0.5714285714285714, 0.5], 'brevity_penalty': 1.0, 'length_ratio': 1.0, **translation_length': 9, 'reference_length': 9}
ROUGE: {'rouge1': np.float64(0.875), 'rouge2': np.float64(0.7142857142857143), 'rougeL': np.float64(0.875), 'rougeLsum': np.float64(0.875)}

The results demonstrate effective parameter-efficient fine-tuning of a compact LLM using QLoRA.


## Author
KOMAL KUMAR KARAMALA 
16364251
MSC DATA SCIENCE AND COMPUTATIONAL INTELLIGENCE
