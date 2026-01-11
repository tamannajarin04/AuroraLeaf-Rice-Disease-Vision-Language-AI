🌾 AuroraLeaf: Rice Leaf Disease Detection with Vision–Guided LLM-Based Advisory Support
Authors: Tamanna Jarin Tima, Md Sazid Sikder, Mahin Alam Rifat, Mohseu Minhaj Niloy
Domain: Agriculture AI, Computer Vision, Explainable AI, Vision–Language Systems
Platform: Google Colab
________________________________________
📌 Abstract
Rice is one of the most important staple crops worldwide, yet rice production is heavily threatened by leaf-borne diseases that significantly reduce both yield and quality. This project presents an interpretable vision–language framework for automated rice leaf disease detection and farmer-oriented advisory support. A CNN-based classifier is trained to recognize four major rice diseases: Bacterial Leaf Blight, Blast, Brown Spot, and False Smut. To enhance transparency and trust, Grad-CAM is applied to visualize disease-affected regions. Furthermore, a LoRA fine-tuned TinyLlama model generates bilingual (Bangla and English) agricultural recommendations based on disease type and context. The proposed system achieved 94% classification accuracy, demonstrating strong generalization and high potential for real-world deployment in smart agriculture.
________________________________________
🚀 Key Contributions
•	🔹 High-performance CNN-based rice leaf disease classifier (94% accuracy)
•	🔹 Explainable AI integration using Grad-CAM heatmaps
•	🔹 End-to-end vision–language agricultural decision support system
•	🔹 LoRA fine-tuned TinyLlama advisory module
•	🔹 Bilingual (Bangla & English) farmer-centric recommendations
•	🔹 Research-oriented yet beginner-friendly implementation
________________________________________
🎯 Objectives
•	Automate rice leaf disease identification
•	Enable early disease detection and intervention
•	Improve AI transparency through visual explanations
•	Provide context-aware agricultural advisory support
•	Bridge computer vision and language intelligence for smart farming
________________________________________
📂 Dataset
Source: Kaggle – Rice Crop Diseases Dataset
The dataset contains balanced samples from four disease classes:
•	Bacterial Leaf Blight
•	Blast Disease
•	Brown Spot Disease
•	False Smut Disease
Data split:
•	70% Training
•	15% Validation
•	15% Testing
Preprocessing techniques include:
•	Image resizing
•	Pixel normalization
•	Rotation, flipping, and zoom-based data augmentation
________________________________________
🧠 System Architecture
Pipeline Overview:
Rice Leaf Image → CNN Classifier → Grad-CAM Explainability → Disease Prediction → LoRA Fine-Tuned LLM → Bilingual Advisory Output
This architecture extends traditional disease classification by integrating explainable AI and large language models to support real agricultural decision-making.
________________________________________
⚙️ Methodology
1. Image Preprocessing
Standardization and augmentation were applied to enhance generalization and robustness.
2. Disease Classification
A CNN-based deep learning model was trained using the Adam optimizer and categorical cross-entropy loss for 15 epochs.
3. Explainability
Grad-CAM was employed to visualize discriminative image regions influencing model predictions.
4. Vision–Language Advisory
TinyLlama-1.1B was fine-tuned using LoRA on agriculture-specific prompts to generate bilingual disease explanations and management advice.
________________________________________
📊 Experimental Results
•	Overall Accuracy: 94%
•	Weighted F1-score: 0.94
Disease Class	Precision	Recall	F1-Score
Bacterial Leaf Blight	1.00	1.00	1.00
Blast Disease	0.88	0.88	0.88
Brown Spot Disease	0.88	0.88	0.88
False Smut Disease	1.00	1.00	1.00
Additional evaluations include confusion matrix analysis, ROC curves, Precision–Recall curves, and Grad-CAM visualizations.
________________________________________
🖼 Explainability Samples
Grad-CAM heatmaps consistently highlight disease-affected regions such as lesions and infected tissue, confirming that the model learns meaningful pathological features rather than background noise.
________________________________________
📄 Research Paper
📘 Rice Leaf Disease Detection with Vision-Guided LLM-Based Advisory Support
(Available in this repository)
________________________________________
▶️ How to Run
1.	Open the notebook in Google Colab
2.	Upload or link the dataset
3.	Run all cells sequentially
4.	Train the CNN model
5.	Evaluate performance
6.	Generate Grad-CAM visualizations
7.	Test the LLM advisory system
________________________________________
🌱 Future Work
•	Mobile and web-based farmer application
•	Real-time field deployment
•	Lightweight edge-AI model
•	Expanded multilingual support
•	Human-centered XAI evaluation with agricultural experts


