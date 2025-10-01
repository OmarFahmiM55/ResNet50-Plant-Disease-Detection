#  Plant Disease Detection using ResNet50

This project applies **ResNet50**, a deep learning architecture, to detect plant diseases from leaf images.  
It is part of a comparative study where different CNN architectures (MobileNetV2, ResNet50, VGG16, InceptionV3, Xception) are evaluated for plant disease classification.

---

##  Dataset
- **Size:** 80,000+ images  
- **Classes:** 38 different plant diseases (including healthy leaves)  
- **Source:** Kaggle  

---

##  Model Details
- **Architecture:** ResNet50  
- **Input size:** 224x224 RGB images  
- **Optimizer:** Adam (lr=0.01)  
- **Loss Function:** Categorical Crossentropy  
- **Batch Size:** 32  
- **Epochs Trained:** 100  

---

##  Training Results
After training for **100 epochs**, ResNet50 achieved:

| Metric        | Training | Validation |
|---------------|----------|------------|
| Loss          | 0.0151   | 0.0462     |
| Accuracy      | 99.67%   | 99.22%     |

 The model shows **excellent generalization** with very high validation accuracy and low loss.

---
