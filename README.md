# Sustainable-approach-of-reduced-waste-using-Optimised-ml-Algorithm-for-predicting-crop-yields

Sustainable Agriculture Framework: Yield Forecasting & Waste Detection
📋 Project Overview
This project presents a complete machine-learning framework designed to improve sustainable agriculture. It addresses the modern struggle with unpredictable crop yields, improper fertilizer application, and rising agricultural waste through an integrated approach combining Predictive Analytics and Computer Vision.
+3

✨ Key Features

Crop & Fertilizer Recommendation: Suggests the most suitable crop and optimal fertilizer combinations based on soil nutrient profiles.
+3


Yield Forecasting: Provides accurate estimates of crop yield (Q/acre) to help farmers plan for the season.
+1


Real-time Waste Detection: Uses YOLOv8 to identify and localize fruits and vegetable waste in farmland images.
+3


Data Imbalance Correction: Employs SMOTE to ensure minority classes are well-represented during training, leading to 100% accuracy in specific classification tasks.
+4


Interactive Web Dashboard: A Flask-based interface for easy data input and visual result interpretation.
+3

🛠️ Technical Stack
Language: Python


Framework: Flask (Web Interface) 
+2


ML Models: Voting Classifier, Decision Tree, MLP-ANN, Bagging 
+4


Computer Vision: YOLOv8, YOLOv7, YOLOv5 
+2


Techniques: SMOTE (Data Balancing), Label Encoding, Feature Scaling 
+1

🌍 Real-World Application

Precision Farming: Farmers can avoid "guesswork" by receiving exact fertilizer recommendations (e.g., NPK basal dose and Urea), preventing soil degradation.
+3


Resource Optimization: By detecting waste through computer vision, farmers can identify areas of resource inefficiency and adjust their practices accordingly.
+4


Economic Security: Accurate yield predictions (like 11 Q/acre for Muskmelon) allow farmers to make informed financial and logistics decisions before the harvest.
+1

📊 System Workflow

Data Source: Multiple datasets covering crop recommendations, yield metrics, and agricultural waste images.
+1


Preprocessing: Data cleaning, normalization, and SMOTE application.


Training: Parallel pipelines for ML classification (Crop/Fertilizer) and YOLO object detection (Waste).


Inference: Interactive results delivered via the Flask web app.
