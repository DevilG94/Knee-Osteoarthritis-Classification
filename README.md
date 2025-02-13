#                                          Knee-Osteoarthritis-Classification

Osteoarthritis of the knee happens when the cartilage in your knee joint breaks down, causing the bones to rub together. This friction causes pain and swelling in your knee, leading to stiffness. Osteoarthritis is a degenerative joint disease — a product of wear and tear over time. It’s very common, and the knee, which takes a lot of stress over your lifetime, is one of the most common joints affected.
Project Update: Knee Osteoarthritis Classification Using Xception, MobileNet, Attention, Squeeze-and-Excitation Networks

Excited to share my latest deep learning project on Knee Osteoarthritis Classification! 🦵📊 Using advanced CNN architectures like Xception, MobileNet, and Attention-based Squeeze-and-Excitation Networks, I developed a model to classify knee X-ray images into three categories:

 ✅ Normal
 ✅ Osteopenia
 ✅ Osteoporosis

📌 Dataset Overview:

Total Images: 3,780
Balanced Classes: 1,260 images per category
Preprocessing: Image resizing (224x224), normalization, augmentation
Oversampling: Addressed class imbalance using RandomOverSampler

🏋️ Model Training & Implementation:
Backbone Architectures: Xception, MobileNet, Attention Mechanisms
Optimized Training: Batch size = 16, Adam optimizer, learning rate tuning
GPU Acceleration: Utilized dual GPUs for faster training

🎯 Results & Performance:

🏋️ Model Performance:

🔹 Xception:
Accuracy: 67%
F1-Score: 0.68 (Weighted Avg)
Class 0 (Normal): Precision: 0.81 | Recall: 0.56 | F1: 0.66
Class 1 (Osteopenia): Precision: 0.70 | Recall: 0.73 | F1: 0.72
Class 2 (Osteoporosis): Precision: 0.58 | Recall: 0.73 | F1: 0.65

🔹 MobileNet:
Accuracy: 70%
F1-Score: 0.69 (Weighted Avg)
Class 0 (Normal): Precision: 0.69 | Recall: 0.82 | F1: 0.75
Class 1 (Osteopenia): Precision: 0.66 | Recall: 0.78 | F1: 0.72
Class 2 (Osteoporosis): Precision: 0.79 | Recall: 0.50 | F1: 0.61

📈 Insights & Takeaways:
 ✅ Xception & MobileNet performed exceptionally well in extracting fine details
 ✅ Attention Mechanisms improved focus on critical knee joint areas
 ✅ Squeeze-and-Excitation Blocks enhanced feature selection and boosted accuracy

This research contributes to automated medical imaging analysis, aiding radiologists in early osteoarthritis detection. Looking forward to optimizing the model further and exploring real-world applications!
