## Alpha Team - HR Analytics: Employee Promotion Data
Tommy Sachi - Aidil Junirzan Rivai


## Table Of Content

 - Introduction
 - Problem Statement
	 - Problem Statement for Machine Learning
	 - Problem Statement for Analytics
 - EDA
	 - Data Cleaning
	 - Feature Enginerring
 - Modeling

## Introduction
Data menjelaskan mengenai 2 dataset(train dan test) dengan tujuan untuk memprediksi menggunakan machine learning, karyawan mana yang bisa dipromosikan.
Kedua dataset memiliki struktur yang sama yaitu 12 variabel yang menggambarkan total 54.808 karyawan dari sebuah perusahaan MNC besar.
 

## Problem Statement
- Berdasarkan dataset yang diperolah ada beberapa permasalahan yang akan dipecahkan, yaitu:
**Problem Statement for Machine Learning:**
- Bagaimana cara memprediksi Promosi Karyawan sehingga kita dapat memiliki target yang tepat dari karyawan potensial dan berprestasi untuk mengurangi pendekatan subjektivitas dan mengoptimalkan lingkungan kerja ?

**Problem Statement for Analytics:**
Profil karyawan seperti apa yang harus kita pertahankan untuk menemukan kandidat promosi yang potensial?

## EDA
Sumber Data: https://www.kaggle.com/arashnic/hr-ana
Data yang tercatat pada CSV ini merupakan record karyawan pada sebuah perusahaan MNC besar. Data ini terdiri dari 12 kolom fitur dengan 54.808 record

**Metadata**

- employee_id: Unique ID untuk karyawan
- department: Departemen Karyawan
- region: Wilayah kerja karyawan
- education: Tingkat pendidikan Karyawan
- gender: Jenis Kelamin karyawan
- recruitment_channel: Jalur Recruitment karyawan
- no_of_trainings: jumlah training yang diselesaikan pada tahun sebelumnya(soft skills, technical skills, dll)
- age: Usia Karyawan
- previous_year_rating: Peringkat karyawan pada tahun sebelumnya
- length_of_service: Lama kerja Karyawan
- awards_won?: penghargaan yang diterima oleh karyawan(bila ada penghargaan yang diterima pada tahun sebelumnya diberikan "1" selain itu 0)
- avg_training_score: Skor rata-rata pada evaluasi pelatihan terakhir
- is_promoted: (Target/Karyawan) yg akan direkomendasikan untuk promosi

## Modelling
Model yang digunakan adalah KNN, Logistic Regression dan Decision Tree, model akan memprediksi karyawan mana yang kemungkinan akan di promosikian. Ketiga model akan dibandingkan dan menggunakan model dengan nilai F1 score yang tinggi.
