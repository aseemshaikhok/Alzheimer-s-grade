# **Alzheimer’s Grade Prediction**  

## **Overview**  
This project aims to assist medical professionals in diagnosing and grading the severity of Alzheimer’s disease using machine learning models. By leveraging both MRI images and clinical tabular data, the system provides a more objective and accurate assessment of Alzheimer’s progression.  

## **Motivation**  
Grading Alzheimer’s severity is subjective and varies among clinicians due to:  
- Overlapping symptoms with other conditions  
- Lack of a definitive test  
- Subjectivity in cognitive assessments  
- Late-stage diagnoses  

## **Approach**  
- **Data Sources:**  
  - **Image Dataset:** [Kaggle - Alzheimer’s MRI Images](https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images)  
  - **Clinical Dataset:** [Kaggle - Alzheimer’s Clinical Data](https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset)  
- **Models Used:**  
  - **Image Classification:** VGG-16, ResNet50, InceptionV3, DenseNet, AlexNet  
  - **Tabular Classification:** Random Forest  
- **Tech Stack:**  
  - **Training:** Google Colab (reduced training time from 5 hours to 30 mins)  
  - **Model Optimization:** Early stopping, dropout, image augmentation  
  - **Deployment:** Streamlit and SHAP for visualization and interpretability  

## **Challenges Faced**  
- Initial model accuracy was low (~60%)  
- Lack of medical image classification research  
- Difficulties in finding optimal pre-trained weights  
- Complexity in combining tabular and image models  

## **Solutions & Improvements**  
- Used callbacks, early stopping, and best model saving  
- Explored feature fusion, ensemble learning, and weighted averaging  
- Shifted deployment from Flask to Streamlit for a smoother experience  

## **Future Enhancements**  
- Improve model accuracy with continued training  
- Enhance GUI for better usability  
- Expand dataset for more diverse predictions  
