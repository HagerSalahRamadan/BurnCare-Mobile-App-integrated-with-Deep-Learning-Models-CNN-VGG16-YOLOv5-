![image](https://github.com/user-attachments/assets/6d766a32-efa0-4742-8ba6-8ac0c14c5ad6)![image](https://github.com/user-attachments/assets/a8787330-9d59-4cfd-a92f-d53ca5197df6)![image](https://github.com/user-attachments/assets/d4efcf3c-6501-4b10-bcb2-2455d0c80754)# 🔥 BurnCare - Mobile App for Burn Treatment using Deep Learning

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
- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)

#### 5. **CNN and VGG16 Models Classification**

- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)


#### 6. **YOLOv5 Detection & Classification**
- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)
- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)
- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)




#### 7. **YOLOv5 Precision**
- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)

- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)


#### 8. **CNN & VGG16 Accuracy**
- CNN Accuracy
- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)

- VGG16 Accuracy
- ![Ensemble Learning Diagram](./images/ensemble_diagram.png)

  
---

## 📱 User Interface

### 🔹 Welcome Page
### 🔹 Patient Features:
- Sign Up / Login
- Burn degree detection
- First aid guidance
- Book appointments
- Follow-up consultations

### 🔹 Doctor Features:
- Review cases
- Chat with patients
- Upload recommendations

---

## 🎬 Video Demo

*(Insert a link to your app walkthrough video or demo GIF)*

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

