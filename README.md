# 🚢 Ship Detection in Satellite Imagery  

![Ship Detection](https://your-image-url-here.com) *(Replace with an actual image if available)*  

## 📌 Project Overview  
This project leverages **YOLOv3 (You Only Look Once)** to detect ships in satellite imagery. The dataset consists of **26.9k images**, all labeled in **YOLO format**, ensuring efficient and accurate ship detection. The dataset includes only one class: `"ship"` for focused training and evaluation.  

## 🌍 Applications of Ship Detection  
Ship detection has multiple real-world applications, including:  
- **Maritime Safety** – Preventing collisions and ensuring safe navigation.  
- **Fisheries Management** – Monitoring fishing activities and preventing overfishing.  
- **Marine Pollution Monitoring** – Identifying ships involved in pollution incidents.  
- **Defense & Maritime Security** – Tracking unauthorized vessels and enhancing national security.  
- **Anti-Piracy & Illegal Immigration** – Detecting unauthorized activities at sea.  

---

## 🔥 Model & Implementation  

### 🚀 YOLOv3 for Ship Detection  
We employed **YOLOv3**, a fast and accurate object detection model, suitable for real-time applications.  

### 🛠 Implementation Details  
- **Framework**: PyTorch & OpenCV  
- **Training Environment**: Google Colab  
- **Pretrained Weights**: YOLOv3 trained on the COCO dataset  
- **Input Image Size**: `416x416`  
- **Loss Function**: Binary Cross-Entropy & Mean Squared Error  
- **Optimizer**: Adam / SGD  
- **Augmentations**: Resizing, flipping, and color transformations  

---

## 🎯 Results  
✅ **Achieved high accuracy** in detecting ships across various images.  
✅ **Optimized real-time inference**, making it suitable for maritime applications.  
✅ **Trained & tested using Google Colab**, leveraging GPU acceleration for faster processing.  

---

## 🛠 Usage  

### 🔹 Clone the Repository  
```bash  
git clone https://github.com/aralantahir66/ships_detection_in_satellite_imagery.git  
 
```
upload on google colab and run  yolov3_on_colab.ipynb
```

### 🔹 Open in Jupyter Notebook / Google Colab  
You can also run the project in **Jupyter Notebook** or **Google Colab** by uploading the `.ipynb` file and running the cells.  

---

## 🚀 Future Improvements  
🔸 Experimenting with **YOLOv8** for improved accuracy and efficiency.  
🔸 Deploying the model as a **real-time API** for maritime surveillance.  
🔸 Fine-tuning on additional **weather-variant datasets** for robustness.  

---

## 📚 References  
- [YOLOv3 Paper](https://arxiv.org/abs/1804.02767)  
- [Dataset on Kaggle](https://www.kaggle.com/datasets/siddharthkumarsah/ships-in-aerial-images)  

📌 *Feel free to contribute, raise issues, or suggest improvements!*  

⭐ **If you found this project useful, please give it a star!** ⭐
