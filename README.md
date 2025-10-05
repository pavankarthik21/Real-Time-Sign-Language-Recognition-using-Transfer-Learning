# 🖐 Real-Time Sign Language Recognition using Transfer Learning  

**Academic Major Project (B.Tech – Computer Science & Engineering)**  
**Institution:** Gokaraju Rangaraju Institute of Engineering and Technology, Hyderabad  
**Year:** 2023  
**Mentor:** Dr. Lipika Goel, Associate Professor  
**Team Members:**  
- Pavan Karthik (19241A05L6)  
- Pradyumna Sinha (19241A05M0)  
- Jashwanth Naidu (19241A05J4)  
- Anand Thota (19241A05M6)

---

## 📄 Overview  

This repository contains the final **major project report** completed as part of the Bachelor of Technology in **Computer Science and Engineering**.  
The project focused on developing a **Real-Time Sign Language Recognition system** using **Transfer Learning** and the **TensorFlow Object Detection API**.

The goal was to bridge the communication gap between hearing-impaired and normal individuals by recognizing hand gestures from a webcam feed and translating them into corresponding text in real time.

---

## 🧠 Abstract  

Communication is essential for human interaction, but the hearing-impaired community often faces barriers due to lack of common language understanding.  
This project proposes a solution that captures hand gestures via webcam and recognizes them using a deep learning model fine-tuned through **Transfer Learning**.  
By leveraging a pretrained **SSD MobileNet V2** model, the system accurately identifies common sign gestures and displays their meanings instantly.

---

## ⚙️ Technologies Used  

| Tool / Library | Purpose |
|----------------|----------|
| **Python 3** | Core programming language |
| **OpenCV** | Capturing and processing video frames |
| **TensorFlow 2.x** | Model training and detection |
| **NumPy** | Array and matrix computations |
| **LabelImg** | Manual image labeling |
| **Jupyter Notebook** | Model development and testing |

---

## 🧩 System Workflow  

1. Capture sign language gesture images using a webcam  
2. Label gestures using **LabelImg**  
3. Split into training and test datasets  
4. Convert to **TFRecords** and create label maps  
5. Fine-tune **SSD MobileNet V2 (COCO)** using Transfer Learning  
6. Perform real-time detection on webcam input  

---

## 🎯 Project Scope  

- Detects six basic sign language gestures: *Hi*, *Yes*, *No*, *Thank You*, *Good*, *I Am Fine*  
- Demonstrates the effectiveness of Transfer Learning with limited datasets  
- Enables a low-cost and accessible method for real-time communication  

---


## 🧾 Citation  

> Pavan Karthik, Pradyumna Sinha, Jashwanth Naidu, Anand Thota.  
> *"Real-Time Sign Language Recognition Using Transfer Learning."*  
> Major Project Report, GRIET, Hyderabad, 2023.

---

## 🏷️ License  

This repository is shared for **academic and portfolio purposes only**.  
All rights are reserved by the original authors and **Gokaraju Rangaraju Institute of Engineering and Technology, Hyderabad**.

---

## 🖼️ Optional Additions  

You can optionally add:  
- `/assets/sample_output.png` → screenshots from the report  
- `/assets/certificate.pdf` → project completion certificate  
- `/presentation/major_project_slides.pptx` → final presentation slides  

---

> **Tip:** Keep your repository public and add a clear description like  
> *"Undergraduate major project demonstrating real-time sign language recognition using deep learning (TensorFlow Transfer Learning)"*  
> in your GitHub repo settings.
