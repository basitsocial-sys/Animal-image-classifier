

#  Animal Image Classifier 

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify African animals (e.g., Lion, Elephant, Zebra, Giraffe) based on images. The model is trained and evaluated on a custom dataset.

---

##  Features

- Built using PyTorch with a simple CNN architecture  
- Supports training, validation, and testing splits  
- Tracks accuracy and loss over epochs  
- Saves trained model to `.pt` file  
- Inference visualization using Matplotlib  

---

##  Model Summary

- **Convolutional Layers:** 3  
- **Activation:** ReLU  
- **Pooling:** MaxPool  
- **Fully Connected Layers:** 2  
- **Optimizer:** Adam  
- **Loss Function:** CrossEntropyLoss  
- **Validation Accuracy:** 100%  

---

##  Requirements

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## 🏃‍♂️ How to Run

### ▶️ Train the Model

```bash
# Make sure you're in the project folder
jupyter notebook
```

- Open: `WildNet Animal Image Classifier.ipynb`  
- Run all cells sequentially to train the model

---

###  Inference on Test Set

After training completes, the notebook visualizes predictions on random test images from the test set.

---

##  Model Saving

The trained model is automatically saved at:

```bash
models/safari_classifier.pt
```

You can later load this model for inference.

---


##  Author

**basit ali**  
 Animal Image Classifier 

