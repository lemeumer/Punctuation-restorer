# Punctuation Restoration (CPU-Friendly, English Tuned)

## How to Use

### 1. Set Up Environment
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 2. Train the Model
```bash
python train.py
```

### 3. Test the Model
```bash
python test_model.py
```

### Notes
- Uses `google/flan-t5-small` (English-optimized).
- Input is lowercase, punctuation-less text.
- Trains on 5,000 AG News samples (good for CPU).
