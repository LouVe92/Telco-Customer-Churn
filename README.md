# **Welcome to Telco-Customer-Churn!**
### An Exploratory Data Analysis of Churn Customer

Project ini merupakan project Data Science pertama yang saya post ke Github, yang meliputi Data Cleaning dan Exploratory Data Analysis, termasuk Statistical Summary, Univariate Analysis dan Bivariate/Multivariate Analysis, serta Deep Dive Question menggunakan bahasa pemograman Python.

### **File Description**
Selain README file, terdapat hanya 1 file lain di dalam repository, yaitu file notebook yang dapat dijalankan dengan menggunakan Google Colab. File tersebut berisikan step-by-step yang dilakukan, coding, beserta observation ataupun interpretasi yang didapatkan.


### **Business Understanding**
Perusahaan bernama Telco merupakah perusahaan telekomunikasi yang menyediakan layanan telepon dan internet. Perusahaan ingin mencari tahu customer mana yang telah churn dan layanan apa yang menjadi penyebanya.

Churn sendiri berarti customer yang berhenti ataupun tidak lagi membayar untuk menggunakan layanan yang disediakan oleh perusahaan.


### **Preliminary**
*   Objective Statement:
    *   Mendapatkan business insight untuk mengetahui customer mana yang churn dan tidak churn
    *   Mendapatkan business insight untuk mengetahui service apa yang menjadi penyebab customer churn
    *   Mendapatkan business insight dengan menjawab pertanyaan sebagai berikut:
        1. Berapa jumlah customer yang join phone service dan internet service berdasarkan tipenya?
        2. Berapakah rata - rata pembayaran per bulan per tipe internet service?
        3. Berapakah rata - rata pembayaran per bulan per senior citizen dan non senior citizen yang churn dan tidak churn?
       
*   Challenges:
    *   Jumlah data yang besar
    *   Adanya white space
    *   Adanya kolom dengan tipe data yang tidak sesuai

*   Methodology/Analytic Technique:
    *   Exploratory Data Analysis
    *   Deep-Dive Exploration

*   Business Benefit:
    *   Mencegah customer untuk churn

*   Expected Outcomes: 
    * Mengetahui customer mana yang churn dan tidak churn
    * Mengetahui service apa yang menjadi penyebab customer churn
    * Rekomendasi bisnis

### **Data Understanding**
*   Sumber data: Telco Customer Churn yang berasal dari Kaggle, yang dapat diakses melalui link sebagai berikut:
https://www.kaggle.com/blastchar/telco-customer-churn

*   Data detail:
    *   customerID: ID customer
    *   gender: jenis kelamin customer
    *   SeniorCitizen: apakah customer termasuk senior citizen atau tidak
    *   Partner: apakah customer memiliki partner atau tidak
    *   Dependents: apakah customer memiliki dependents atau tidak
    *   tenure: berapa lama customer telah bergabung dengan perusahaan (dalam jumlah bulan)
    *   PhoneService: apakah customer join phone service atau tidak
    *   MultipleLines: apakah customer join multiple lines service (beberapa line telepon) atau tidak
    *   InternetService: internet service provider yang digunakan
    *   OnlineSecurity: apakah customer join online security atau tidak
    *   DeviceProtection: apakah customer join device protection atau tidak
    *   TechSupport: apakah customer join tech support atau tidak
    *   StreamingTV: apakah customer join streaming TV atau tidak
    *   StreamingMovies: apakah customer join streaming movies atau tidak
    *   Contract: jangka waktu contract customer
    *   PaperlessBilling: apakah customer menggunakan paperless billing atau tidak
    *   PaymentMethod: metode pembayaran customer
    *   MonthlyCharges: jumlah yang ditagihkan pada customer setiap bulan
    *   TotalCharges: total jumlah yang telah ditagihkan pada customer
    *   Churn: apakah customer akan churn atau tidak
