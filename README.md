# Malicious Network Traffic Analysis Based on Feature Selection Methods

With the rise in sophisticated cyberattacks, the efficiency of intrusion detection systems becomes paramount. Machine learning models used for intrusion detection often encounter datasets with irrelevant or redundant features, leading to suboptimal performance. To address this challenge, feature selection techniques have been developed to extract the most informative features, enabling faster and more accurate detection of malicious patterns. We conducted a comparative analysis of four feature selection methods using the NSL-KDD dataset. Each of the explored methods leverage unique concepts to identify the most relevant features for intrusion detection. These concepts include: entropy, mutual information, chi-squared statistics and ANOVA. By evaluating and comparing the effectiveness of these methods, this study aims to provide insights into their respective strengths and weaknesses, guiding the selection of the most suitable approach for enhancing the efficiency of intrusion detection systems.
## Installation

To run the provided code, first download the Train_data.csv and Test_data.csv files located in the NSL-KDD Dataset folder.

Each of the files located in the Code folder can be accessed in any order using Google Colaboratory. Before running a file, upload the Train_data.csv and Test_data.csv files to the session storage.

A description of each python file is listed below.

**Entropy_Feature_Selection:** Extracts top 10, 15 and 20 NSL-KDD features based on entropy difference

**Entropy_NSLKDD_Models:** Tests entropy-based feature selection on 5 classification models

**Mutual_Information_Feature_Selection:** Extracts top 10, 15 and 20 NSL-KDD features based on information gain

**Mutual_Information_NSLKDD_Models:** Tests mutual information-based feature selection on 5 classification models

**Chi_Squared_Feature_Selection:** Extracts top 10, 15 and 20 NSL-KDD features based on chi-square statistic

**Chi_Squared_NSLKDD_Models:** Tests chi-square-based feature selection on 5 classification models

**ANOVA_Feature_Selection:** Extracts top 10, 15 and 20 NSL-KDD features based on f-statistic

**ANOVA_Information_NSLKDD_Models:** Tests ANOVA-based feature selection on 5 classification models
## Findings
For a closer look at findings, refer to the following:

- **[Research Paper](https://ieeexplore.ieee.org/document/10637359)**  
- **[Research Poster](https://drive.google.com/file/d/1x_qt4EtaNhDLbAaJAx6Ky0JHbGgAmpsK/view?usp=sharing)**
## Acknowledgements
This project was developed through my research at the National Science Foundation. I would like to thank Professor Park and Professor Di Troia for broadening my knowledge on machine learning and cybersecurity. I sincerely thank Kelsey Nguyen and everyone involved in the NSF REU program at SJSU for their guidance and support.
## Author

- [@sohinibagchi](https://github.com/sohinibagchi)