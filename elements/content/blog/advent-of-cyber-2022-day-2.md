+++
categories = ["Advent of Cyber 2022  "]
date = 2023-02-13T16:00:00Z
description = ""
draft = true
image = "/images/c0a5c0197614aad4d2ca911414683e7f.png"
title = "Advent of Cyber 2022  (Day 2)"
type = "featured"

+++
**_Selamat datang di Advent of Cyber dari TryHackMe_**! Saya mulai agak terlambat tahun ini karena Pekerjaan Menumpuk,

tetapi saya menyempatkan untuk menyelesaikan tantangan ini! Tantangan dari Tryhackme bisa di selesaikan oleh pemula.

### **_Siklus 1:_** 

Masuk Fokus utama dari rangkaian tahap ini adalah untuk seorang penyerang memperoleh akses ke sistem atau lingkungan jaringan.

Langkah-langkah:

**Rekognisi:** Penyerang melakukan penelitian pada target menggunakan informasi yang tersedia secara publik. 

**Peralatan:** Menyiapkan infrastruktur yang diperlukan untuk menghosting pusat kendali dan kontrol (C2) sangat penting dalam menjalankan serangan. 

**Pengiriman:** Payload adalah instrumen jahat yang dikirimkan ke target melalui berbagai cara, seperti phishing email dan serangan rantai pasokan. 

**Rekayasa Sosial:** Penyerang akan menipu target mereka untuk melakukan tindakan yang tidak terpercaya dan tidak aman terhadap payload yang baru saja mereka kirimkan, sering membuat pesan mereka muncul berasal dari sumber internal yang terpercaya. 

**Eksploitasi:** Jika penyerang menemukan kerentanan yang ada, kelemahan perangkat lunak atau perangkat keras, dalam aset jaringan, mereka dapat menggunakannya untuk memicu payload mereka. 

**Persistensi:** Penyerang akan meninggalkan kehadiran cadangan di jaringan atau aset untuk memastikan mereka memiliki titik akses ke target mereka. 

**Pembelaan Pengelakan:** Penyerang harus tetap anonim selama eksploitasi mereka dengan menonaktifkan dan menghindari mekanisme pertahanan keamanan apa pun yang diaktifkan, termasuk menghapus bukti keberadaan mereka. 

**Komando & Kendali:** Ingatlah infrastruktur yang disiapkan penyerang? Saluran komunikasi antara sistem yang tercompromi dan infrastruktur penyerang didirikan melalui internet.

### **Siklus 2:**

 Melalui Dalam fase ini, penyerang akan tertarik untuk memperoleh lebih banyak akses dan hak istimewa ke aset dalam jaringan.

**Pivoting:** Ingat sistem yang mungkin digunakan penyerang untuk persistence? Sistem ini akan menjadi peluncur serangan untuk sistem lain dalam jaringan. 

**Discovery:** Penyerang akan berusaha mengumpulkan sebanyak mungkin informasi tentang sistem yang dikompromikan, seperti pengguna dan data yang tersedia. Alternatifnya, mereka dapat menemukan kerentanan dan aset jaringan secara remote. Ini membuka jalan untuk fase berikutnya. 

**Privilege Escalation:** Akses terbatas mencegah penyerang untuk menjalankan misi mereka. Oleh karena itu, mereka akan mencari hak istimewa yang lebih tinggi pada sistem yang dikompromikan dengan mengeksploitasi kerentanan atau kesalahan konfigurasi yang diidentifikasi. 

**Execution:** Dengan hak istimewa yang ditingkatkan, kode berbahaya dapat diunduh dan dieksekusi untuk mengekstrak informasi sensitif atau menimbulkan kerusakan lebih lanjut pada sistem. 

**Credential Access:** Sebagian dari informasi sensitif yang diekstrak akan mencakup kredensial login yang disimpan di hard disk atau memori. Ini memberikan penyerang dengan lebih banyak kekuatan untuk serangan mereka. 

**Lateral Movement:** Dengan menggunakan kredensial yang diekstrak, penyerang dapat bergerak di sekitar sistem atau penyimpanan data yang berbeda dalam jaringan, misalnya, di dalam satu departemen.

### **Siklus 3:** 

Keluar Pada fase ini, kerahasiaan, integritas, dan ketersediaan aset atau layanan dapat terganggu. Uang, ketenaran, atau sabotase akan mendorong penyerang untuk melancarkan serangan mereka, menimbulkan kerusakan sebanyak mungkin, dan menghilang tanpa terdeteksi.

**Pengumpulan:** Setelah menemukan jackpot data dan informasi, penyerang akan mencoba mengumpulkan semua yang mereka butuhkan. Dengan melakukan itu, kerahasiaan aset akan terganggu sepenuhnya, terutama ketika menangani rahasia dagang dan informasi keuangan atau identifikasi pribadi (PII) yang harus dijaga kerahasiaannya. 

**Eksfiltrasi:** Penyerang harus mengeluarkan rampasan mereka dari jaringan. Berbagai teknik dapat digunakan untuk memastikan bahwa mereka telah mencapai tujuan mereka tanpa menimbulkan kecurigaan. 

**Dampak:** Saat mengganggu ketersediaan atau integritas aset atau informasi, penyerang akan menggunakan semua hak akses yang diperoleh untuk memanipulasi, mengganggu, dan merusak. Bayangkan reputasi, kerusakan keuangan, dan sosial yang harus dipulihkan oleh sebuah organisasi. 

**Tujuan:** Penyerang mungkin memiliki tujuan lain yang dapat memengaruhi lanskap sosial atau teknis yang menjadi target mereka. Mendefinisikan dan memahami tujuan-tujuan ini cenderung membantu tim keamanan mempelajari alat serangan dari pihak lawan dan melakukan penilaian risiko untuk mempertahankan aset mereka.

**_Tantangan pertama dimulai dengan tautan ke situs web The Best Festival Company yang telah dicoret-coret:_**

![](/images/trak.webp)

**_Pertanyaan 1:_** Siapakah penyerang yang menyerang jaringan Santa tahun ini?

**Answer:** The Bandit Yeti

![](/images/try-1.png)

![](/images/try4.png)

![](/images/try3.png)![](/images/try2.png)

**_Pertanyaan 2:_** Apa bendera yang mereka tinggalkan?

**Answer:** THM{IT'S A Y3T1 CHR1$TMA$}

Mungkin hanya itu yang  dapat saya sampaikan untuk Advent OF Cyber 2022 (Day 1).