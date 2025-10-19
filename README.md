# ECG-FM PEFT Fine-Tuning

This repository contains the lab work for fine-tuning the **ECG-FM** foundation model for ECG classification using **Parameter-Efficient Fine-Tuning (PEFT)** techniques, specifically **Adapters** and **LoRA**.

---

## Repository Contents

- **`report.pdf`**: Detailed report including:
  - Experimental results
  - Accuracy and loss plots per epoch
  - Confusion matrices
  - Discussion and conclusions

- **`ECG_PEFT_Lab.ipynb`**: Jupyter notebook containing:
  - The actual training code
  - Preprocessing steps
  - Model fine-tuning for ECG-FM, Adapters, and LoRA
  - Generation of plots and evaluation metrics

- **Other files**:
  - `.gitignore` – ignores large files (like CSV datasets)
  - `requirements.txt` – Python dependencies for running the notebook

---

## Key Highlights

- Fine-tuning **ECG-FM** using PEFT methods significantly reduces trainable parameters while maintaining competitive performance:
  - **Adapter**: ~5.66% of parameters
  - **LoRA**: ~3.26% of parameters
- Provides plots and metrics comparing full fine-tuning vs. PEFT methods.
- Supports reproducibility and step-by-step experimentation.

---