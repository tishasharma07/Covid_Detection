# Covid_Detection Using Deep Learning

DataSet Description

COVID CXR Image Dataset
It is a comprehensive collection of posteroanterior (PA) view chest X-ray images aimed at assisting AI-based diagnostic systems in detecting COVID-19 and other lung conditions. This dataset compiles images from multiple sources and research papers, providing a valuable resource for the research community. It has also been utilized in the COVID Lite paper, which demonstrated significant results using a novel CNN-based approach.

Dataset Composition
Total Images: 1,823 chest X-ray (CXR) images
Categories: 
COVID-19 Cases: 536 images
Viral Pneumonia Cases: 619 images
Normal (Non-Pneumonia) Cases: 668 images
Age Range of COVID-19 Cases: 18-75 years
![image](https://github.com/user-attachments/assets/454bc2ea-d790-458c-a22b-2585982f8cc1)
![image](https://github.com/user-attachments/assets/e65c6b78-2ecd-4fcb-817d-f9c0661b2fd6)

Split Ratios:
Training (80%) – For model learning.
Validation (10%) – For hyperparameter tuning.
Testing (10%) – For final model evaluation.
![image](https://github.com/user-attachments/assets/bde4ad05-eb39-4f30-a254-b0bab65d9f3d)

![image](https://github.com/user-attachments/assets/181a7f37-9662-45d0-b8bb-b0c4edabcfb5)

![image](https://github.com/user-attachments/assets/ba1f31da-5a5b-42fd-8b7d-40b2d9546872)

![image](https://github.com/user-attachments/assets/991ae8d9-5379-4c21-b029-0a1ed3759287)

![image](https://github.com/user-attachments/assets/cab87c45-227c-4df8-bf8d-a33813cc8dcf)

Results

📈 Model accuracy improved over iterations, starting from 55.79% and reaching 97.67% for the testing dataset.


The evaluation of the CNN model on the validation dataset showed promising results, with a high accuracy rate of 95.91% and minimal overfitting since the model performed well on both training and validation data. This indicates that the model generalized effectively to unseen data.

Expanding the dataset with more diverse and annotated chest X-ray images can enhance the model's ability to generalize to a broader range of cases.This includes obtaining more COVID-19 positive cases and samples from other lung diseases, further improving the model’s robustness.



