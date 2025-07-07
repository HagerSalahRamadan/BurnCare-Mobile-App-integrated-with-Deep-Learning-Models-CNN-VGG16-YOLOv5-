# 🔥 BurnCare - Mobile App for Burn Treatment using Deep Learning

## 🧾 Introduction

Burns are among the most serious public health issues. A burn can occur due to heat, chemicals, sunlight, electricity, or radiation damaging the skin tissue. There are various degrees of burns: first, second, and third degree.

According to World Health Organization (WHO) statistics:
- Burn injuries cause over **180,000 fatalities** globally each year.
- In **Egypt**, burns are the **third leading cause of death**, with around **80,000 cases annually** (≈300 cases per day).

---

## 🚨 Problems

1. **Incorrect First Aid**  
   Many people apply toothpaste or ice on burns, which worsens the condition:
   - Toothpaste is non-sterile.
   - Ice increases skin irritation and pain.

2. **Lack of Medical Access**  
   Many patients live far from clinics or doctors, delaying treatment.

3. **Incomplete Recovery**  
   Due to poor follow-up or distance, many patients do not complete their treatment.

---

## 🔍 Related Work

Some existing apps for burn-related services include:
- Burn Ai, Burn Care, Burn Referral, Burn Medical Education, Burn Table App

### ✅ Advantages:
- Help doctors determine burn degree
- Calculate Burned Body Surface Area (BSA)
- Guide dehydration treatment in first 24 hours

### ❌ Limitations:
- Most apps target doctors only
- No patient-first aid or treatment features
- Some are iOS-only

---

## 💡 Our Solution

A **mobile application integrated with Deep Learning models** to:
- Provide a full burn care system connecting doctors and patients.
- Offer medical info, first aid, diagnosis, consultations, and recovery support.
- Ensure **data security** via encrypted patient images and transactions.

### Key Features:

1. **Immediate First Aid**  
   Based on burn degree to reduce infection and pain.

2. **24/7 Availability**  
   Supports urgent appointment booking for severe burns.

3. **Doctor Consultations**  
   Continuous follow-up and access to specialists.

---

## 🛠️ Other Services

- 🕑 Alerts for medication & consultation times  
- 💊 Pharmacy partnerships for 24h delivery  
- 📝 Patient feedback system for doctors

---

## 🤖 Machine Learning

### 🔹 Dataset
- 1,440 labeled images of burns (from Kaggle)
- Labels: first, second, third-degree burns
- Format: YOLO
- Resized to 224×224×3 and stored as 3D multichannel arrays

### 🔹 Models Used

#### 1. **CNN (Convolutional Neural Network)**
- Specialized for image recognition
- Structure: Convolutional layers + Pooling + Fully Connected
- Accuracy: **77.15%**

#### 2. **VGG16**
- Deep CNN with 16 layers (13 conv + 3 FC)
- Pretrained on ImageNet
- Input: 224×224×3 → Output: Class label
- Accuracy: **95.80%**

#### 3. **YOLOv5**
- Fast single-stage object detection
- Trained using focal loss to handle class imbalance
- Versions: YOLOv5s / m / l / x
- Detects multiple burn degrees per image
- Supports classification & precision-based detection

#### 4. **Ensemble Learning**
- Combines predictions from multiple models using **voting** to enhance accuracy
- ![Ensemble Learning Diagram](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/Ensemble%20Learning.jpg)

#### 5. **CNN and VGG16 Models Classification**

- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/CNN%20and%20VGG16%20Models%20Classifications.png)

#### 6. **YOLOv5 Detection & Classification**
- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/YOLOv5%20Detection%20%26%20Classification.png)
- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/YOLOv5%20Detection%20%26%20Classification3.png)
- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/YOLOv5%20Detection%20%26%20Classification2.png)



#### 7. **CNN & VGG16 Accuracy**
- CNN Accuracy
- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/CNN%20Accuracy.png)

- VGG16 Accuracy
- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/VGG16%20Accuracy.png)
  

#### 8. **YOLOv5 Precision**
- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/YOLOv5%20Precision1.png)

- ![Screenshot](https://github.com/HagerSalahRamadan/BurnCare-Mobile-App-integrated-with-Deep-Learning-Models-CNN-VGG16-YOLOv5-/blob/main/images/YOLOv5%20Precision2.png)


  
---

## 📌 Conclusion

1. **BurnCare** app serves both patients and doctors.
2. Offers:
   - Burn info + First aid
   - Burn degree detection
   - Doctor connection
   - Recovery instructions

---

## 🚀 Future Plan

- 🤝 Partner with more doctors and hospitals  
- 📈 Expand marketing via paid ads  
- 💊 Predict drug doses using ML  
- ⚠️ Predict mortality and post-burn complications using advanced ML models

---

## Contact
For any questions Contact via email **hagersalah.r39@gmail.com**.
