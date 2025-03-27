---
title: "Toyota Car Sales E-Invoice"
excerpt: "Automating invoicing for Toyota car sales, integrating with existing ERP systems.<br/><img src='/images/ToyotaCarSalesE-Invoice.png'>"
collection: portfolio
---

<br />

<img src='/images/index_tls.png'>

# About

**Toyota Logistic System (TLS)** adalah sistem yang mengelola seluruh proses logistik Toyota, termasuk distribusi barang dan kendaraan dari pabrik ke dealer atau pelanggan akhir. Untuk meningkatkan efisiensi dan kepatuhan terhadap regulasi perpajakan, Toyota membutuhkan **modul e-Faktur** yang memungkinkan pembuatan, pengelolaan, dan pelacakan faktur elektronik secara otomatis dan sesuai dengan standar pajak yang berlaku.

# Functional - Non Functional Requirements

## Functional Requirements

| No  | Functional                | Description                                                                     |
|-----|---------------------------|---------------------------------------------------------------------------------|
|1    | Pembuatan Faktur Otomatis | Sistem harus dapat menghasilkan e-Faktur berdasarkan transaksi logisti          |
|2    | Validasi Data             | Sistem harus memeriksa kesesuaian data sebelum menerbitkan faktur               |
|3    | Integrasi dengan Pajak    | Modul harus terhubung dengan sistem perpajakan nasional seperti DJP Indonesia   |
|4    | Penyimpanan Faktur        | Semua faktur harus disimpan dalam sistem terpusat dan dapat diakses kapan saja  |
|5    | Pelacakan & Audit         | Sistem harus menyediakan log transaksi untuk keperluan audit                    |
|6    | Notifikasi & Pengiriman   | Faktur dapat dikirimkan otomatis ke distributor atau pelanggan                  |
|7    | Integrasi Pembayaran      | e-Faktur harus dapat dikaitkan dengan sistem pembayaran Toyota                  |

## Non - Functional Requirements

| No  | Non Functional              | Description                                                           |
|-----|-----------------------------|-----------------------------------------------------------------------|
|1    | Keamanan                    | Data e-Faktur harus terenkripsi dan memiliki kontrol akses            |
|2    | Ketersediaan                | Sistem harus memiliki uptime minimal **99.5%**                        |
|3    | Skalabilitas                | Sistem harus mampu menangani peningkatan jumlah faktur setiap tahun   |
|4    | Kepatuhan                   | Harus sesuai dengan regulasi pajak nasional dan internasional         |

# Technology Stack

## Frontend

- HTML
- CSS
- Javascript
- Angular Js

## Backend

- .Net 8

## Database

- SQL Server
- Redis

# Business Proccess

<img src='/images/tls_faktur.png'>
