# Customer Churn Prediction using Machine Learning

## Introduction

### Latar Belakang

DQLab Telco merupakan perusahaan Telco yang sudah mempunyai banyak cabang tersebar dimana-mana. Sejak berdiri pada tahun 2019, DQLab Telco konsisten untuk memperhatikan customer experience nya sehingga tidak akan di tinggalkan pelanggan.

Walaupun baru berumur 1 tahun lebih sedikit, DQLab Telco sudah mempunyai banyak pelanggan yang beralih langganan ke kompetitior. Pihak management ingin mengurangi jumlah pelanggan yang beralih (churn) dengan menggunakan machine learning.

Setelah mempersiapkan data sekaligus melakukan Cleansing, maka sekarang saatnya untuk membuat model yang tepat untuk memprediksi churn pelanggan.

### Tugas dan Langkah

Pada tugas kali ini, akan dilakukan Pemodelan Machine Learning dengan menggunakan data pada bulan Juni 2020.

Langkah-langkah yang akan dilakukan adalah :

1. Melakukan Exploratory Data Analysis
2. Melakukan Data Pre-Processing
3. Melakukan Pemodelan Machine Learning
4. Menentukan Model Terbaik

### Data yang Digunakan

Untuk Dataset yang digunakan sudah disediakan dalam format csv, silahkan baca melalui fungsi pandas di python df_load = pd.read_csv('https://storage.googleapis.com/dqlab-dataset/dqlab_telco_final.csv')

Untuk detil datanya adalah sebagai berikut:

1. UpdatedAt Periode of Data taken
2. customerID Customer ID
3. gender Whether the customer is a male or a female (Male, Female)
4. SeniorCitizen Whether the customer is a senior citizen or not (Yes, No)
5. Partner Whether the customer has a partner or not (Yes, No)
6. tenure Number of months the customer has stayed with the company
7. PhoneService Whether the customer has a phone service or not (Yes, No)
8. InternetService Customer’s internet service provider (Yes, No)
9. StreamingTV Whether the customer has streaming TV or not (Yes, No)
10. PaperlessBilling Whether the customer has paperless billing or not (Yes, No)
11. MonthlyCharges The amount charged to the customer monthly
12. TotalCharges The total amount charged to the customer
13. Churn Whether the customer churned or not (Yes, No)

