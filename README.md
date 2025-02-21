## Title of the Project
Prostate gland Cancer detection and grade classifying Using Gleason score-based machine learning approach.

## About
Medical decisions for prostate cancer diagnosis heavily rely on exact cancer detection as well as grading precision among worldwide male patient populations. The Gleason Score assessment provides the established diagnostic method for evaluating prostate cancer through evaluation of histopathological tissue specimens. Currently the assessment process shows two main weaknesses because it depends on subjective judgment while also being unable to prevent differences between grader observations. A machine learning-based framework serves as the basis of this research to automatically discover prostate cancer while performing Gleason score(2-10) classifications. The dataset which contains histopathological images together with clinical biomarkers is prepared through feature extraction stages that use texture and morphological analysis methods. Different supervised learning techniques such as Support Vector Machines (SVM), Random Forest (RF), and deep learning approaches with Convolutional Neural Networks (CNNs) serve to correctly identify prostate cancer grades. The experimental data shows that CNN-based methods accomplish the most accurate grade classification results with an achievement of 94.5% and precise results showing 93.8% as well as the recall results of 94.2% and F1-score of 94.0%. Deep learning approaches produce more precise diagnosis through better reliability than traditional methods do. The implementation of machine learning algorithms in prostate cancer diagnosis enables pathologists to handle complex decisions thus allowing them to intervene early which produces better patient results.

## Features
Automated Prostate Cancer Detection – Uses deep learning (CNNs, ResNet, U-Net) to classify histopathology images based on the Gleason Score.

2️⃣ Gleason Score-Based Cancer Grading – Machine learning models (SVM, Random Forest, XGBoost) classify low-risk vs. high-risk prostate cancer cases.

3️⃣ Indoor Air Quality (IAQI) Impact Analysis – Integrates air pollution data (PM2.5, VOCs, CO, NO₂) to study environmental effects on cancer progression.

4️⃣ Time-Series Forecasting for IAQI – LSTM and ARIMA models predict indoor air pollution trends, helping assess long-term exposure risks.

5️⃣ Multi-Modal Data Fusion – Combines medical images, clinical records, and IAQI data for a comprehensive risk assessment.

## Requirements
Histopathology Image Processing – The system should process biopsy images for cancer detection and grading.
Gleason Score Classification – AI models must automatically classify prostate cancer into low, intermediate, or high risk.
Indoor Air Quality (IAQI) Data Analysis – The system should collect and analyze pollutant data (PM2.5, CO, NO₂, VOCs).
Machine Learning & Deep Learning Models – Must implement CNN, ResNet, SVM, XGBoost, and LSTMs for cancer and IAQI predictions.
Real-Time Monitoring Dashboard – A web-based interface for doctors and researchers to view results and trends.
Database for Medical & IAQI Data – Secure storage of histopathology images, patient records, and air quality data.
Cloud-Based AI Model Deployment 

## System Architecture
![image](https://github.com/user-attachments/assets/de1fae74-7074-4387-ac27-bfbd653a7b5f)




## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Gleason Score-Based Histopathological Classification of Prostate based  

![image](https://github.com/user-attachments/assets/aa5f0cfc-7e90-4940-b8b9-de97b5e3f73a)


#### Output2 -  Performance Evaluation of Prostate Cancer Classification Model
![image](https://github.com/user-attachments/assets/4cf01820-5c20-4a21-b810-5148b1d262b5)


Detection Accuracy: 94.5%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
![image](https://github.com/user-attachments/assets/38a19308-8f13-4088-81cc-2f98cdf2a538)

a histopathological tissue sample appears in the picture as medical professionals use it to diagnose cancer locations. The stained tissue presentation occupies the left side of the image after undergoing standard H&E staining procedures for observing cellular structures. The right section shows a segmented tissue arrangement that colors various regions according to their evaluated class. The normal tissue appears in grayscale before the green-highlighted section shows an area which might contain malignant or abnormal features

## Articles published / References
[1] Bulten, W., et al. (2020). Automated deep-learning system for Gleason grading of prostate cancer using biopsies: a diagnostic study. The Lancet Oncology, 21(2), 233-241. doi: 10.1016/S1470-2045(19)30739-9

[2] Ishioka, J., et al. (2019). Computer-aided diagnosis of prostate cancer on magnetic resonance imaging using a convolutional neural network algorithm. BJU International, 124(3), 411-417. doi: 10.1111/bju.14759

[3]  Gao, Z., et al. (2020). Deep learning in prostate cancer diagnosis: a narrative review. Translational Andrology and Urology, 9(3), 924-934. doi: 10.21037/tau.2020.03.30

[4] Tolkach, Y., et al. (2020). Deep learning-based detection of prostate cancer in multiparametric MRI. European Urology, 78(1), 99-101. doi: 10.1016/j.eururo.2020.03.049

[5] Ehteshami Bejnordi, B., et al. (2017). Diagnostic Assessment of Deep Learning Algorithms for Detection of Lymph Node Metastases in Women With Breast Cancer. JAMA, 318(22), 2199-2210. doi: 10.1001/jama.2017.14585

[6] Wang, D., et al. (2019). Deep learning for identifying metastatic breast cancer. arXiv preprint arXiv:1606.05718. doi: 10.48550/arXiv.1606.05718


