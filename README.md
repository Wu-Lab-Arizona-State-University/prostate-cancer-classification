# About

This is a repository that contains information about the *prostate cancer* case study reported in [A Transfer Learning-Based Framework for Classifying Lymph Node Metastasis in Prostate Cancer Patients](url-pending).

<!------------------>

# Abstract

Prostate cancer is the second most common new cancer diagnosis in the United States. It is usually slow growing; and when low-grade and confined to the prostate gland, it can be treated either conservatively (active surveillance) or with surgery. However, if the cancer has spread beyond the prostate, such as to the lymph nodes, then that indicates a more aggressive cancer and surgery may not be adequate.  The challenge is that it is often difficult for radiologists reading prostate-specific imaging such as magnetic resonance images (MRIs) to differentiate malignant lymph nodes from non-malignant ones. An emerging field is to develop Artificial Intelligence (AI) models including machine learning and deep learning on medical imaging to assist the diagnostic task. Earlier research focused on implementing texture algorithms to extract imaging features used in classification models. More recently, researchers began studying the use of deep learning for both stand-alone feature extraction as well as end-to-end classification tasks. In order to tackle the challenges inherent in small datasets, this study was designed as a scalable hybrid framework utilizing pre-trained ResNet-18, a deep learning model, to extract features which were subsequently fed into a machine learning classifier to automatically identify malignant lymph nodes in patients with prostate cancer. For comparison, two texture algorithms are implemented including Gray Level Co-occurrence Matrix (GLCM) and Gabor. Using an institutional prostate lymph node dataset (42 positives, 84 negatives), the proposed framework achieved an accuracy of 76.19%, sensitivity of 79.76% and specificity of 69.05%. Using GLCM features, the classification achieved an accuracy of 61.90%, sensitivity of 74.07% and specificity of 42.86%. Using Gabor features, the classification achieved an accuracy of 65.08%, sensitivity of 73.47% and specificity of 52.50%. Our results demonstrate that a hybrid approach, i.e., using a pre-trainined deep learning model for feature extraction, followed by a machine learning classifier, is a viable solution. This hybrid approach is especially useful in medical imaging-based applications with small datasets.

<!------------------>

# Data

## Description

- As described in our [paper](url-pending), the data used for our analyses comprised a total of 126 lymph node images (41 metastatic, 85 normal), acquired from 15 patients with prostate cancer.

- Disease: lymph node metastasis of the prostate

- Stages: Ta, Tis, T0, T1, T2, T3, T4

- Region-of-interest (ROI) annotation technique: Performed manually by radiologists

For more details, interested readers are directed to the **Dataset** section of the [paper](url-pending).

## Availability

Data will be made available under reasonable request to the corresponding author, [Suryadipto Sarkar](suryadipto.sarkar@fau.de) (more contact details below).


<!------------------>

# Citing the work

## MLA

Will be made available upon publication.

## APA

Will be made available upon publication.

## BibTex

Will be made available upon publication.

<!------------------>

# Contact

&#x2709;&nbsp;&nbsp;suryadipto.sarkar@fau.de<br/>
&#x2709;&nbsp;&nbsp;ssarka34@asu.edu<br/>
&#x2709;&nbsp;&nbsp;ssarkarmanipal@gmail.com

<!------------------>

# Impressum

Suryadipto Sarkar ("Surya"), MS<br/><br/>
PhD Candidate<br/>
Biomedical Network Science Lab<br/>
Department of Artificial Intelligence in Biomedical Engineering (AIBE)<br/>
Friedrich-Alexander University Erlangen-Nürnberg (FAU)<br/>
Werner von Siemens Strasse<br/>
91052 Erlangen<br/><br/>
MS in CEN from Arizona State University, AZ, USA.<br/>
B.Tech in ECE from MIT Manipal, KA, India.
