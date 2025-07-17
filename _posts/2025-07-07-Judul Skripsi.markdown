---
layout: post
title:  Hasil Skripsi
date:   2025-07-07 16:03:50 +0300
image:  mamdani.png
tags:   Fuzzy Logic Mamdani Python IoT
---

### 💡 Rancang Bangun Alat Pendeteksi Golongan Air Berdasarkan Kegunaannya Dengan Methode Fuzzy Logic Mamdani
Sebagai bagian dari tugas akhir dalam menyelesaikan studi Sarjana Teknik Informatika, saya mengerjakan sebuah proyek skripsi yang menggabungkan teknologi Internet of Things (IoT) dan kecerdasan buatan berbasis logika fuzzy. Proyek ini bertujuan untuk membangun sebuah alat pendeteksi kualitas air yang mampu mengklasifikasikan jenis air berdasarkan kelayakan penggunaannya, seperti air layak minum, air untuk kebutuhan domestik, atau air tercemar dan tidak layak digunakan.
![]({{site.baseurl}}/img/mamdani.png)

## Latar Belakang
Kualitas air menjadi isu penting dalam kehidupan masyarakat, terutama di wilayah-wilayah yang memiliki akses terbatas terhadap sumber air bersih. Oleh karena itu, diperlukan sebuah sistem cerdas yang dapat membantu mendeteksi kualitas air secara otomatis, cepat, dan akurat untuk mempermudah pengambilan keputusan dalam penggunaannya. Untuk itu, saya merancang sebuah alat yang dapat membaca data lingkungan secara langsung melalui sensor, mengolahnya menggunakan metode Fuzzy Logic Mamdani, dan menampilkannya secara real-time melalui dashboard digital.

## Teknologi dan Perangkat yang Digunakan
# Sensor Kualitas Air
Digunakan beberapa sensor utama untuk mendeteksi parameter penting seperti pH, TDS (Total Dissolved Solid), dan suhu air, yang menjadi indikator utama dalam menentukan kualitas air.

# Mikrokontroler dan Modul IoT
Arduino Uno: Sebagai otak utama dalam pemrosesan data sensor.
ESP8266 WiFi Module: Digunakan untuk mengirimkan data secara nirkabel ke platform cloud.
ATmega328P: Sebagai chip pengendali mikro utama yang terintegrasi dengan Arduino.

# Platform Monitoring dan Cloud Visualization
Untuk mengelola dan menampilkan data secara online, saya menggunakan beberapa platform IoT populer:

MQTT (Message Queuing Telemetry Transport): Protokol komunikasi ringan yang efisien untuk pertukaran data antar perangkat.
Blynk: Aplikasi mobile berbasis IoT yang memungkinkan tampilan real-time data sensor dengan antarmuka grafis yang menarik.
Antares (platform IoT Indonesia): Untuk manajemen data sensor dan pengembangan prototipe IoT secara lokal.
ThingsBoard: Platform open-source untuk visualisasi dan manajemen perangkat IoT.
ThingSpeak: Digunakan untuk menyimpan, menganalisis, dan menampilkan data sensor dalam bentuk grafik.

## Metode Fuzzy Logic Mamdani

Metode ini dipilih karena kemampuannya dalam menangani ketidakpastian dan nilai-nilai linguistik dalam klasifikasi kualitas air. Fuzzy Logic mampu memetakan input seperti nilai pH dan TDS ke dalam kategori linguistik (baik, sedang, buruk) dan memberikan keputusan akhir secara fleksibel dan logis.

# Bahasa Pemrograman dan Protokol

C++: Untuk pemrograman perangkat Arduino dan integrasi dengan sensor.
Python: Digunakan dalam simulasi dan pengujian logika fuzzy secara offline.
HTTPClient: Digunakan sebagai protokol untuk mengirim data dari perangkat ke platform cloud menggunakan jaringan internet.

## Tahapan Pengembangan
Proyek ini melalui beberapa tahapan penting:

Perancangan Alat: Membuat skematik perangkat keras serta integrasi sensor dengan mikrokontroler.
Implementasi Logika Fuzzy: Menyusun rule base dan fungsi keanggotaan pada sistem fuzzy Mamdani.
Pengujian dan Kalibrasi: Menguji keakuratan alat pada berbagai jenis sampel air (air minum kemasan, air sungai, air sumur, dan air limbah).
Integrasi IoT: Menghubungkan alat ke jaringan dan platform monitoring menggunakan ESP8266 dan protokol MQTT.
Visualisasi Data: Menampilkan hasil klasifikasi kualitas air dalam bentuk grafik interaktif di aplikasi Blynk dan dashboard ThingsBoard.

## Hasil dan Manfaat
Sistem yang dibangun mampu memberikan klasifikasi kualitas air secara real-time dan mengirimkan datanya ke platform cloud yang dapat diakses dari perangkat manapun. Hasil klasifikasi muncul dalam bentuk indikator seperti:

Layak Minum
Layak Domestik
Tidak Layak / Tercemar

# Dengan keberhasilan pengembangan sistem ini, proyek skripsi ini tidak hanya berkontribusi pada pengembangan teknologi monitoring lingkungan, tetapi juga membuktikan potensi fuzzy logic dan IoT sebagai solusi praktis dalam kehidupan sehari-hari.

# Penutup
Proyek ini merupakan salah satu pencapaian akademik yang paling berkesan dan menjadi fondasi bagi minat saya di bidang data processing, sensor-based intelligence, dan teknologi terapan berbasis IoT. Lewat proyek ini, saya belajar banyak mengenai integrasi lintas disiplin: mulai dari elektronika, pemrograman, komunikasi data, hingga artificial intelligence.

