# Sneakers & Boot Annotation Dataset  

This repository contains **image annotations for sneakers and boots**, created using **CVAT (Computer Vision Annotation Tool)**. These annotations can be used for **image classification, object detection, and deep learning model training**.

## 📂 Dataset Overview  
- **📸 Images**: Contains labeled images of sneakers and boots.  
- **📝 Annotations**: Available in different formats such as **COCO JSON, YOLO, and Pascal VOC**.  
- **🛠️ Tools Used**: CVAT for annotation.  

## 🚀 Usage  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/saba386/sneakers-boot-annotation.git
cd sneakers-boot-annotation
```


### 2️⃣ Download Annotations  
- Use the annotation files to train your **object detection** or **classification** models.  

### 3️⃣ Load the Dataset (Example in Python)  
```python
import json

with open("annotations.json") as f:
    annotations = json.load(f)

print(annotations)
```

### 4️⃣ Train a Model  
- Use **TensorFlow, PyTorch, or YOLO** for training an image classification or object detection model using this dataset.  

## 📑 Formats Available  
- **COCO JSON** (For object detection)  
- **Pascal VOC XML**  
- **YOLO TXT Format**  

