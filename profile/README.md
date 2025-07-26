# Danalensa - *masa depan keuanganmu, diprediksi hari ini*

[![Cover PPT](https://github.com/user-attachments/assets/791c53eb-adc2-423a-bb60-7df22e2c7997)](https://docs.google.com/presentation/d/1LvhT7sEjKJ1_EdTiRrie6BM95V8PQC6NX5NVtxymkOA/edit?usp=sharing)

**Danalensa** adalah sebuah inisiatif untuk membangun asisten keuangan pribadi berbasis AI yang dirancang untuk mengantisipasi potensi kesulitan finansial, sehingga dapat mengambil keputusan dan membangun kebiasaan menabung untuk memenuhi kewajiban finansial mereka.

## 💥Latar Belakang Masalah

Jutaan pekerja di sektor ekonomi digital dan informal Indonesia (seperti pelaku UMKM, freelancer, dan pekerja gig-economy lainnya) adalah tulang punggung ekonomi, namun mereka menghadapi **ketidakpastian arus kas yang tinggi**. Kondisi ini membuat mereka sangat rentan terhadap guncangan finansial, kesulitan memenuhi kewajiban (seperti iuran BPJS dan cicilan), dan pada akhirnya menjadi target utama pinjaman online ilegal. Sedangkan solusi yang ada saat ini bersifat reaktif, hanya mencatat masa lalu.

## 💡Solusi

Pendekatan proaktif. Danalensa ingin menjawab tantangan fundamental, seperti yang diidentifikasi oleh AFPI(Asosiasi Fintech Pendanaan bersama Indonesia), yaitu pentingnya mengelola cash flow dengan baik.
Asisten keuangan AI yang sistematis membangun dana darurat, sebuah solusi jangka panjang yang juga direkomendasikan oleh akademisi.

* *Memprediksi* (*Forecast*), yaitu meramal saldo kas harian 30 hari ke depan dengan Time-Series.
* *Memperingatkan* (*Warns*), yaitu mengidentifikasi potensi defisit dari keuangan pengguna.
* *Memberdayakan* (*Empowers*), yaitu memberi rekomendasi untuk membangun Dana Siaga (dana yang disiapkan pengguna untuk menghadapi atau melakukan pembayaran tagihan) secara disiplin.

### Figma
* [Hi-Fi Design](https://www.figma.com/design/MI8p0P9HxzTg3wP9eeJwp5/Danalensa?node-id=2-215&t=Z5o03dwDw2VskAPr-1)
* Prototype
  - [First On Boarding](https://www.figma.com/proto/MI8p0P9HxzTg3wP9eeJwp5/Danalensa?page-id=2%3A217&node-id=187-2595&viewport=454%2C266%2C0.1&t=V8sqznxFiXhAeGiu-9&scaling=scale-down&content-scaling=fixed&starting-point-node-id=187%3A2595&show-proto-sidebar=1)
  - [Tambah Dana Siaga Pertama Kali](https://www.figma.com/proto/MI8p0P9HxzTg3wP9eeJwp5/Danalensa?page-id=2%3A217&node-id=198-1959&viewport=454%2C266%2C0.1&t=V8sqznxFiXhAeGiu-9&scaling=scale-down&content-scaling=fixed&starting-point-node-id=198%3A1959&show-proto-sidebar=1)
  - [Tambah Transaksi Saldo Kas](https://www.figma.com/proto/MI8p0P9HxzTg3wP9eeJwp5/Danalensa?page-id=2%3A217&node-id=256-2869&viewport=454%2C266%2C0.1&t=V8sqznxFiXhAeGiu-9&scaling=scale-down&content-scaling=fixed&starting-point-node-id=256%3A2869&show-proto-sidebar=1)
  - [Tambah Transaksi Dana Siaga](https://www.figma.com/proto/MI8p0P9HxzTg3wP9eeJwp5/Danalensa?page-id=2%3A217&node-id=275-5746&viewport=454%2C266%2C0.1&t=V8sqznxFiXhAeGiu-9&scaling=scale-down&content-scaling=fixed&starting-point-node-id=275%3A5746&show-proto-sidebar=1)

## 📦 Komponen Proyek

Proyek ini terdiri dari beberapa komponen utama yang bisa Anda jelajahi:

* *[ML-POC] ml-danalensa-poc:* Repositori untuk riset dan validasi baseline model AI menggunakan Python dan SARIMA. Berisi notebook eksperimen dan script untuk generasi data sintetis.
* *[Mobile App] mobile-app-danalensa:* Repositori untuk pengembangan aplikasi mobile menggunakan Flutter yang akan menjadi antarmuka utama bagi pengguna.

## 🛠️ Tech Stack

* *Frontend:* Flutter
* *Backend & AI:* Python, Statsmodels
* *Infrastruktur:* Google Cloud Platform (Cloud Run, Vertex AI, Cloud SQL)

> Proyek ini sedang dikembangkan sebagai bagian dari partisipasi dalam BI-OJK Hackathon 2025

Terima kasih sudah berkunjung!👋

