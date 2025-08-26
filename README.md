# 🐱🐶 Cats vs Dogs Classification using SVM  
*Prodigy Infotech Internship – Task 3*

---

## 📌 Task Description
Implement a *Support Vector Machine (SVM)* to classify images of cats and dogs from the Kaggle dataset.  

This project demonstrates how SVM can be applied for *binary image classification* by preprocessing images (resizing, grayscale conversion, feature flattening) and then training an SVM classifier.

---

## 📊 Dataset
The original dataset comes from Kaggle’s *Dogs vs Cats Competition*:  
🔗 [https://www.kaggle.com/c/dogs-vs-cats/data](https://www.kaggle.com/c/dogs-vs-cats/data)

Since the Kaggle dataset is very large (~800 MB), for demonstration in *Google Colab* we used only a *small subset of images* (a few cats and dogs) to train and test the SVM model.

---

## 🛠 Technologies Used
- Python  
- OpenCV (for image preprocessing)  
- NumPy  
- Scikit-learn (for SVM, train-test split, evaluation)  
- Matplotlib (for visualization)

---

## 🚀 How it Works
1. *Data Collection*  
   - Kaggle dataset (or a few sample images for a lightweight demo).  
2. *Preprocessing*  
   - Resize all images to 64×64.  
   - Convert to grayscale.  
   - Flatten each image into a 1D feature vector.  
3. *Model Training*  
   - Train an *SVM (Support Vector Machine)* classifier using Scikit-learn.  
4. *Evaluation*  
   - Evaluate model using accuracy and classification report.  
5. *Prediction*  
   - Test with new unseen cat/dog images.

---

## 📂 Project Structure
