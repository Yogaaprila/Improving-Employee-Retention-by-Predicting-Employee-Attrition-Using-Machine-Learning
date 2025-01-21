# Improving Employee Retention by Predicting Employee Attrition Using Machine Learning
![Alt Link](pictures/employee-retention.png)

---

## Background
Human resources (HR) is the main asset that needs to be managed properly by the company so that business goals can be achieved effectively and efficiently. A technology start-up company is facing a problem about the human resources in the company. Therefore, the company wanted to know how to keep employees in the current company, which could result in increased costs for employee recruitment and training for new entrants. By knowing the main factors that cause employees not to feel, the company can immediately overcome it by creating programs that are relevant to employee problems to help the company.

---

## Problem
The company is currently facing a significant issue as many employees have submitted their resignations, yet no decisive action has been taken to address the problem. As the data science team, we will conduct an in-depth analysis to assess the current state of the workforce and investigate the underlying causes driving employee resignations. This will enable the company to devise strategies to reduce employee turnover and improve retention rates.
To address this challenge, we will employ a statistical approach comprising both descriptive and inferential methods. Descriptive statistics and visualizations will be used to provide an overview of the workforce's current condition. Inferential statistics, including machine learning models, will be utilized to identify key factors influencing employee resignations. Based on these insights, we aim to recommend targeted strategies to improve employee retention, ultimately helping the company reduce costs and enhance operational efficiency.

---

## Goal
Adopting a statistical approach that combines descriptive methods (descriptive calculations and visualizations) and inferential methods (machine learning) to address the identified issues.

---

## Objective
1. Importing the necessary libraries and dataset.  
2. Conducting Exploratory Data Analysis (EDA) to understand the overall condition of employees in the company.  
3. Performing data preprocessing, including handling missing values, detecting and addressing anomalies, encoding categorical features, etc.  
4. Building classification models using machine learning techniques.  
5. Selecting the best model based on evaluation metrics.  
6. Fine-tuning the hyperparameters of the best model to achieve optimal results.  
7. Identifying the most influential features affecting employee resignation using feature importance analysis.  
8. Developing business recommendations and strategies based on insights from EDA and machine learning analysis.
   
---

## Dataset
| **Feature**                      | **Explanation**                                  |
|----------------------------------|--------------------------------------------------|
| **Username**                     | Unique employee username.                        |
| **EnterpriseID**                 | ID within the enterprise.                       |
| **StatusPernikahan**             | Marital status.                                 |
| **JenisKelamin**                 | Gender.                                         |
| **StatusKepegawaian**            | Employment status.                              |
| **Pekerjaan**                    | Job position.                                   |
| **JenjangKarir**                 | Career level.                                   |
| **PerformancePegawai**           | Performance rating.                             |
| **AsalDaerah**                   | Region of origin.                               |
| **HiringPlatform**               | Platform used for hiring.                      |
| **SkorSurveyEngagement**         | Engagement score.                               |
| **SkorKepuasanPegawai**          | Employee satisfaction score.                   |
| **JumlahKeikutsertaanProjek**    | Number of projects participated in.            |
| **JumlahKeterlambatanSebulanTerakhir** | Recent monthly delay count.                    |
| **JumlahKetidakhadiran**         | Absence count.                                  |
| **NomorHP**                      | Employee's phone number.                        |
| **Email**                        | Employee's email address.                      |
| **TingkatPendidikan**            | Educational level.                              |
| **PernahBekerja**                | Previous employment history.                   |
| **IkutProgramLOP**               | Participation in a specific program (LOP).     |
| **AlasanResign**                 | Reason for resignation (if applicable).        |
| **TanggalLahir**                 | Date of birth.                                  |
| **TanggalHiring**                | Date of hiring.                                 |
| **TanggalPenilaianKaryawan**     | Date of employee evaluation.                   |
| **TanggalResign**                | Date of resignation.                           |

---

## Metric Evaluation
1. Accuracy : A straightforward metric that gives a clear idea of how well a model is performing overall.

---

## Tool
1. Python Programming Language
2. Jupyter Notebook / Jupyterlab
