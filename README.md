# ITAI-2277_CapstoneProject_TriagePalHealthCareAgent_JBPortfolio
To streamline preliminary medical triage by pre-analyzing patient submitted images of eyes or wounds and text based symptoms to generate rapid, actionable insights for clinicians. 

# Capstone Project: Multimodal AI for Telehelth Triage
TriagePal is a prototype application that uses multimodal Artificial Intelligence (AI) to streamline preliminary assessments in healthcare settings. It is designed to assist nurses and clinicians by rapidly analyzing patient submitted data specifically, images of common conditions like eye infections and text based symptom descriptions to generate a structured triage urgency score and a concise clinical report. 

This project demonstrates the full machine learning lifecycle, from data acquisition and model development to application deployment. 

# Key Features
- Computer Vision (CV): Utilizes a Transfer Learning model (MobileNetV2) to classify images like detecting Conjunctivitis in eye photos.
- Structured Triage Output: Generates a clear, actionable Triage urgency Score (Low, Medium, High) and a Clinician Report based on model predictions and symptom input.
- Interactive Web Application: Deployed via Streamlit for real-time interaction, allowing users to upload images and input text symptoms.
- Modular Codebase: Organized into phases, demonstrating the iterative development process of an AI system.

  # Technical Stack
  - Primary Language: Python
  - Deep Learning Framework: TensorFlow/Keras
  - Computer Vision Model: MobileNetV2 (Transfer Learning)
  - Web Framework: Streamlit
  - Data Tools: NumPy, Pandas, Scikit-learn, Matplotlib
  - Development Environment: Google Colab, GitHub
