# Object Detection with Faster R-CNN

This repository contains an implementation and tutorial for **object detection** using **Faster R-CNN with a ResNet-50 backbone** in PyTorch.  
The model is pretrained on the **COCO dataset** and can detect 80 common object categories (person, car, dog, etc.).

## 🚀 Run in Google Colab
You can open and run the notebook directly in Colab with the link below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshita18/Object-detection-with-faster-R-CNN/blob/main/Object_detection_with_faster_R_CNN.ipynb)

---

## 📂 Files
- `Object_detection_with_faster_R_CNN.ipynb` → main Google Colab notebook with code and explanations.

---

## ⚙️ Features
- Load a **pretrained Faster R-CNN model** from `torchvision`.
- Run inference on images (predict bounding boxes, classes, and confidence scores).
- Post-processing helper functions to:
  - Filter predictions by confidence threshold.
  - Select specific object classes (e.g., only `"person"`).
- Visualization with OpenCV + Matplotlib (bounding boxes and labels).

---

## 🖼️ Example Output
The notebook will show images with detected objects, like this:

[ "person: 0.95" box drawn around the detected object ]



