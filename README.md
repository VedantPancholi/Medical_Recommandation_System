---

# 🩺 Medicine Prediction and Recommendations System

### Overview
A machine learning-powered system that predicts diseases based on user-reported symptoms and provides comprehensive recommendations including precautions, diets, medications, and workout plans.

### Features
- **Symptom-based Disease Prediction**: Input symptoms to predict the most likely disease.
- **Precautionary Measures**: Receive precautionary steps to manage the predicted disease.
- **Diet and Nutrition**: Tailored dietary suggestions to support recovery.
- **Medication Advice**: Recommended medications based on the disease.
- **Workout Suggestions**: Fitness and exercise tips to enhance recovery.

### How It Works
1. Input your symptoms when prompted by the system.
2. The system uses a Support Vector Classifier (SVC) to predict the disease.
3. You will receive:
   - A **disease description** explaining the predicted condition.
   - **Precautions** to take for managing the disease.
   - Suggested **diet** plans to aid recovery.
   - A list of **medications** for treatment.
   - Recommended **workout** routines to boost health.

### Technologies Used
- **Python**: Core programming language.
- **scikit-learn**: Support Vector Classifier (SVC) for prediction.
- **Pandas**: Data manipulation for symptoms, diseases, precautions, etc.
- **Numpy**: Numerical operations.

### Example

```plaintext
********************************Predicted Disease ************************************
Ashveen's Machine Prediction is:- Fungal infection
********************************Predicted Description ************************************
Fungal infection is a common skin condition caused by fungi.
********************************Predicted Precaution ************************************
1 : bath twice
2 : use detol or neem in bathing water
3 : keep infected area dry
4 : use clean cloths
********************************Predicted Diets ************************************
['Antifungal Diet', 'Probiotics', 'Garlic', 'Coconut oil', 'Turmeric']
********************************Predicted Medication ************************************
1 : ['Antifungal Cream', 'Fluconazole', 'Terbinafine', 'Clotrimazole', 'Ketoconazole']
********************************Predicted workout ************************************
1 : Avoid sugary foods
2 : Consume probiotics
3 : Increase intake of garlic
4 : Include yogurt in diet
```

### Contributing
Feel free to open issues or submit pull requests to improve this project.

---
