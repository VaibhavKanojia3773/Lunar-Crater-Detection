# Lunar-Crater-Detection
Lunar crater detection on ISRO hackathon



Detailed solution and Approach 
1. Data Preparation and Preprocessing:
Data Acquisition: Obtain OHRC datasets in PDS4 format from Chandrayaan Map Browse.
Selenoreferencing: Use auxiliary information to accurately project and localize images.
Preprocessing Steps:
Convert images to grayscale.
Apply Gaussian blur to reduce noise.
Use Canny edge detection to highlight crater and boulder boundaries.
Objective: Simplify image features to enhance distinguishability for the detection model.

2. Model Development and Training:
Model Architecture: Convolutional Neural Network (CNN)
Layers: Multiple convolutional layers for feature extraction, max-pooling layers for down-sampling, dense layers for classification.
Training Process:
Data Augmentation: Increase diversity with transformations (rotation, scaling, etc.).
Loss Function: Minimize binary cross-entropy.
Performance Metric: Accuracy.
Evaluation: Test on separate dataset to ensure generalization to new images.

3. Detection, Post-processing, and Evaluation:
Detection:
Use the trained model to detect craters and boulders in OHRC images.
Extract contours using image processing techniques.
Quantification:
Measure selenographic position and diameter of detected features.
Generate a polygonal shape file with boundaries and relevant information.
Evaluation Metrics:
Accuracy: Precision of detected features compared to actual craters/boulders.
Relevance: Degree of match between detected features and actual craters.
Metrics: Use precision, recall, and F1-score for comprehensive evaluation.
Objective: Ensure accurate detection and detailed information presentation, meeting project objectives effectively.

![image](https://github.com/user-attachments/assets/d02ba26b-3176-40ac-b768-d9b49cff0c28)

![image](https://github.com/user-attachments/assets/7909183a-b347-4c3c-b183-7a8e18d77fed)

![image](https://github.com/user-attachments/assets/d854bc0b-1580-45e1-ab80-55db511d9295)

![image](https://github.com/user-attachments/assets/022f8dc6-ce7a-4b21-950b-9f56416893ff)

![image](https://github.com/user-attachments/assets/430700d1-544b-4946-abb3-397b48f8c442)



Future Work and Acknowledgments
Continuous Improvement
Enhancing model accuracy and efficiency
Incorporating advanced techniques and algorithms
Expanding dataset for better generalization
Knowledge and Experience
Gained hands-on experience in AI/ML
Developed practical skills in image processing
Learned valuable lessons in project execution
Gratitude
Thrilled to participate in this hackathon
Appreciate the opportunity to innovate and contribute
Thank you for providing this platform to showcase our work







