# turbo-ai
Turbo ai is Egypt's First Locally-Trained Neural Language Model Built from scratch by Youssef Hossam "me" by  PyTorch · CUDA 
⚙️ Neural Architecture

| Property | Value |
| :--- | :--- |
| **Model Type** | Decoder-Only Transformer (GPT-Style) |
| **Parameters** | ~160 Million |
| **Transformer Layers** | 12 |
| **Attention Heads** | 12 |
| **Embedding Dimension** | 768 |
| **Context Window** | 512 Tokens |
| **Vocabulary** | 32,000 Tokens (BPE) |
| **Attention Engine** | Flash Attention (SDPA) |
| **Inference Precision** | FP16 (Half-Precision CUDA) |
### 1. Navigate to the project folder
```cmd
cd C:\Users\
```

### 2. Install dependencies
```cmd
pip install -r requirements.txt
```

### 3. Train Titan's Brain
```cmd
py turbo_v3/main_v3.py train
```

### 4. Start Chatting
```cmd
py turbo_v3/main_v3.py chat
```

---
