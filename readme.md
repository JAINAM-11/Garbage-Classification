# Garbage Classification using PyTorch

## Stepwise Project Structure

### Step 1 – Install Dependencies
Use the following command in a fresh Python 3.11 environment:

```
pip install -r requirements.txt
```

### Step 2 – Technologies Used
- Python
- PyTorch
- Torchvision
- Scikit-learn
- Pillow
- Matplotlib
- tqdm

### Step 3 – Dataset Format
Organize dataset in this structure:

```
data/
├── cardboard/
├── glass/
├── metal/
├── paper/
├── plastic/
└── trash/
```

### Step 4 – Model
- Custom CNN (Convolutional Neural Network) neural network built from scratch
- GPU accelerated training using CUDA

### Step 5 – Output
- Saved trained model: `garbage_model.pth`
- Performance metrics: accuracy, precision, recall, f1-score

### Step 6 – Future Scope
- Improve dataset size and balance
- Use deeper CNN or ensemble techniques to target 96–99% accuracy

---
