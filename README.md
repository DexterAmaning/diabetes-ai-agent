diabetes-ai-agent
Multimodal AI Agent for Early Diabetes Detection & Retinopathy Screening 
Overview 
This project develops a multimodal AI system that combines structured clinical data and retinal fundus images to enable early detection of diabetes and diabetic retinopathy. The system integrates: - Tabular risk prediction (BMI, HbA1c, glucose, etc.) - Deep learning image classification (retinal images) - AI decision-support layer for clinical recommendations

Objectives - Detect diabetes risk early using patient clinical features - Classify diabetic retinopathy severity from retinal images - Combine both predictions into a unified AI agent - Support screening in dental and primary care settings 
Models 
Tabular Model - Logistic Regression - Random Forest - SVM 
Image Model - CNN (EfficientNet / ResNet / custom CNN) - Image preprocessing: resizing, normalization
Evaluation Metrics - F1 Score - ROC-AUC - Confusion Matrix - Training vs Validation Curves 
Current Progress - [x] Tabular data preprocessing - [x] Initial ML models trained - [x] Retinal CNN pipeline (in progress) - [x] Model evaluation (F1, confusion matrix) - [ ] Multimodal integration - [ ] Deployment (Gradio/Streamlit) 
Tech Stack - Python - TensorFlow / Keras - Scikit-learn - Pandas / NumPy - Matplotlib / Seaborn - Gradio / Streamlit
Use Case Designed for early screening of diabetes and diabetic retinopathy, with potential integration into clinical workflows in dental and primary care settings. 
Future Work - Improve model generalization - Deploy as a web application - Integrate explainability (SHAP) - Expand dataset and validation

Author Prince Kwarteng Amaning
