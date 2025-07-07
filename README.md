# Machine Learning Lab

**Shahriar Hossain Shaikat**  
**ID:** 2215151034  
**Batch:** 51  
**Section:** 7A2  

---
## 🌸 CNN-Based Image Classification on TF Flowers
## 📘 Overview

A CNN model was built using TensorFlow to classify images from the TF Flowers dataset into 5 categories: Daisy, Dandelion, Rose, Sunflower, and Tulip.

---

## 📚 Dataset

- Source: TensorFlow Datasets (`tf_flowers`)
- Classes: 5
- Images: ~3,600+
- Preprocessing: 150x150 resizing, normalization, 80/20 train-test split

---

## 🧠 Model

- Layers: Conv2D → MaxPool → Conv2D → MaxPool → Conv2D → MaxPool → Flatten → Dense → Output
- Activation: ReLU (hidden), Softmax (output)
- Loss: Sparse Categorical Crossentropy
- Optimizer: Adam
- Epochs: 15  
- Batch Size: 32

---

## 📈 Results

- Training Accuracy: 99.86%
- Validation Accuracy: 65.94%
- Test Accuracy: 65.94%
- Overfitting observed after ~6–7 epochs

---

## ✅ Conclusion

The model learned training data well but did not generalize effectively. To improve:
- Use data augmentation
- Add dropout layers
- Apply early stopping
- Try transfer learning

---

## 📄 Report

📥 [View Full Report (Google Drive)](https://drive.google.com/file/d/1sNlVy2pWZh1HRUUs0lay9xkQSNoqB2gH/view?usp=drive_link)

---

> Submitted for Machine Learning Lab Assignment  
> Shahriar Hossain Shaikat | ID: 2215151034 | Batch: 51 | Section: 7A2
