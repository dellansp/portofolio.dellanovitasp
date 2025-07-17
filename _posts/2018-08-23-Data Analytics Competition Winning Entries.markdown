---
layout: post
title:  IOT & INNOVATION PROJECT
date:   2025-07-01 16:03:00 +0300
image:  innovation.png
tags:   IoT, RnD, Embended System
---


## MENCIPTAKAN INOVASI SUNGGUH ASIK !

Saya adalah seorang IT Research Enthusiast, dengan minat khusus dalam pengembangan Internet of Things (IoT). Ketertarikan saya bermula sejak masa SMK, saat pertama kali mempelajari mikroprosesor, gerbang logika, dan bahasa pemrograman C++. Dari sana, saya berhasil membuat proyek prototipe rambu-rambu lalu lintas otomatis, yang menjadi titik awal eksplorasi saya di bidang teknologi tertanam.

Minat ini semakin berkembang ketika saya melanjutkan studi di jurusan Informatika. Selama kuliah, saya aktif dalam organisasi mahasiswa yang fokus pada riset, inovasi, robotika, dan kewirausahaan teknologi. Keterlibatan ini memperluas pengetahuan saya terhadap mikrokontroler seperti Arduino, ESP8266, dan berbagai modul sensor, sekaligus mengasah kemampuan saya dalam merancang sistem IoT yang terintegrasi.

### 💡 SMOKPOLISA – Sistem Monitoring Kebocoran Pipa Landfill Gas pada PLTSa Berbasis IoT
Salah satu proyek yang pernah saya kerjakan adalah SMOKPOLISA (Sistem Monitoring Kebocoran Pipa Landfill Gas pada PLTSa Berbasis Internet of Things). Proyek ini dirancang sebagai solusi untuk mendeteksi kebocoran gas metana dari pipa landfill di Pembangkit Listrik Tenaga Sampah (PLTSa). Sistem ini mengintegrasikan mikrokontroler seperti Arduino, ESP8266, dan ATmega, dengan berbagai platform IoT seperti MQTT, Blynk, Antares, ThingsBoard, dan ThingSpeak untuk melakukan pemantauan secara real-time.
![]({{site.baseurl}}/img/smokpolisa.png)

Pengembangan SMOKPOLISA meliputi implementasi sistem monitoring, integrasi antara perangkat keras dengan media pemantauan daring, serta perancangan prototipe dan mockup hardware yang mendekati kondisi implementasi nyata. Sistem ini diprogram menggunakan bahasa C++, Java, serta komunikasi berbasis HTTPClient.

Melalui proyek ini, saya tidak hanya memperdalam pemahaman teknis terkait IoT dan sensor lingkungan, tetapi juga berhasil membawa tim meraih peringkat 3 dalam ajang Lomba Karya Tulis Ilmiah Nasional (LKTIN) sebagai bentuk pengakuan terhadap inovasi dan kebermanfaatan proyek tersebut.

### 💡 MOGE (Monitoring Gas Environment) Berbasis IoT
Salah satu proyek yang saya kembangkan adalah MOGE (Monitoring Gas Environment), yaitu sistem berbasis Internet of Things (IoT) yang dirancang untuk mendeteksi kebocoran gas LPG pada area-area rawan seperti dapur industri, rumah tangga, atau fasilitas penyimpanan gas. Sistem ini bertujuan untuk memberikan peringatan dini secara real-time guna mencegah potensi kebakaran atau ledakan akibat akumulasi gas.
![]({{site.baseurl}}/img/moge.png)

Dalam pengembangannya, sistem ini memanfaatkan mikrokontroler seperti Arduino, ESP8266, dan ATmega, yang diintegrasikan dengan platform IoT seperti MQTT, Blynk, Antares, ThingsBoard, dan ThingSpeak. Data dari sensor gas diproses dan dikirimkan ke cloud untuk dipantau melalui dashboard maupun notifikasi pada perangkat pengguna.
Tahapan proyek mencakup implementasi sensor gas dan modul komunikasi, integrasi perangkat keras dengan sistem pemantauan daring, serta desain dan pembuatan mockup prototipe untuk pengujian simulasi kebocoran gas di lingkungan terkendali. Proses pemrograman dilakukan menggunakan C++, Java, dan protokol komunikasi berbasis HTTPClient.

Melalui proyek MOGE, saya memperoleh pengalaman dalam merancang sistem keselamatan berbasis teknologi IoT sekaligus mengasah keterampilan dalam integrasi perangkat pintar yang aplikatif dan solutif di bidang keamanan lingkungan.

#### Dataset Name: Taipei Real Estate Dataset.xlsx

#### Dataset Overview

The Taipei Real Estate dataset comprises property information from Xindian District, New Taipei City. The dataset is in xlsx format, containing a total of 414 records. "NA" denotes missing data. It includes 6 explanatory variables:

X1 = Transaction Year-Month (e.g., 2013.250 represents March 2013, 2013.500 represents June 2013, and so on)

X2 = Age of the Property (in years)

X3 = Distance to the Nearest Bus Stop (in meters)

X4 = Number of Nearby Convenience Stores (integer)

X5 = Geographic Latitude Coordinates (in degrees)

X6 = Geographic Longitude Coordinates (in degrees)

The response variable:
Y = Unit Area Price (price per ping, measured in New Taiwan Dollars, where 1 ping = 3.3 square meters)

### Outline of Analysis Report

Project overview, analysis objectives, summary of methods used, results analysis, conclusions, etc. The analysis report must include the basic requirements, while participants are encouraged to add their own analysis content beyond the basics.

### Data cleaning

####Analyzing the Basic Structure of the Dataset

Querying and Outputting the First 5 and Last 5 Rows of Data

First 5 Rows:

![]({{site.baseurl}}/img/16.jpg)

Last 5 Rows:

![]({{site.baseurl}}/img/17.jpg)

Identifies and outputs the types of all feature in the dataset:

![]({{site.baseurl}}/img/18.jpg)

#### Missing Values 
1. Mean imputation
![]({{site.baseurl}}/img/19.jpg)
2. Median imputation
![]({{site.baseurl}}/img/20.jpg)
3. Mode imputation
![]({{site.baseurl}}/img/21.jpg)
4. Forward fill
![]({{site.baseurl}}/img/22.jpg)
5. Backward fill
![]({{site.baseurl}}/img/23.jpg)
6. Pandas linear interpolation
![]({{site.baseurl}}/img/24.jpg)

#### Outliers

Viewing data outliers:
![]({{site.baseurl}}/img/25.jpg)

Next, conducting an initial visualization of the correlation within the structured data.

![]({{site.baseurl}}/img/27.jpg)

![]({{site.baseurl}}/img/28.jpg)

#### Data standardization

Utilizing the StandardScaler() method from sklearn to perform standardization on the data, resulting in data with a mean of 0 and a variance of 1 after processing.
![]({{site.baseurl}}/img/26.jpg)

#### Constructing the model after splitting the data using K-fold Cross Validation

![]({{site.baseurl}}/img/29.jpg)
![]({{site.baseurl}}/img/30.jpg)
![]({{site.baseurl}}/img/31.jpg)
![]({{site.baseurl}}/img/32.jpg)
![]({{site.baseurl}}/img/33.jpg)
![]({{site.baseurl}}/img/34.jpg)

#### Analyzing Model Accuracy
![]({{site.baseurl}}/img/35.jpg)
![]({{site.baseurl}}/img/36.jpg)
![]({{site.baseurl}}/img/37.jpg)
![]({{site.baseurl}}/img/38.jpg)
![]({{site.baseurl}}/img/39.jpg)
![]({{site.baseurl}}/img/40.jpg)
![]({{site.baseurl}}/img/41.jpg)
![]({{site.baseurl}}/img/42.jpg)
![]({{site.baseurl}}/img/43.jpg)

#### Error Analysis and Model Parameter Testing
![]({{site.baseurl}}/img/44.jpg)
![]({{site.baseurl}}/img/45.jpg)
![]({{site.baseurl}}/img/46.jpg)
![]({{site.baseurl}}/img/47.jpg)
![]({{site.baseurl}}/img/48.jpg)


#### Model Evaluation
![]({{site.baseurl}}/img/49.jpg)
![]({{site.baseurl}}/img/50.jpg)

Results Analysis:

By comparing the results of various models including Linear Regression, Linear Regression after dropping features using VIF, Ridge Regression, Lasso Regression, Bayesian Ridge Regression, Random Forest Regressor, Linear Regression VIF, Random Forest Regressor VIF, and Random Forest Regressor RFE, a comparison was conducted using two-dimensional tables and bar charts depicting the outcomes of each model. It was observed that the Random Forest Regressor RFE exhibited the most favorable performance.
