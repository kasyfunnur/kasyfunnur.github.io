---
title: "New Osase"
excerpt: " OSASE (Operation Supervisory & Alert System For Electrical) is a monitoring system developed by PT Telkom to monitor and retrieve measurement data via sensors that have been installe<br/><img src='/images/newosase.png'>"
collection: portfolio
---


<img src='/images/index_tls.png'>

# About

New ​OSASE (Operation Supervisory and Alert System for Electrical) adalah sistem yang dikembangkan oleh PT Telkom Indonesia untuk memantau dan memberikan peringatan dini terhadap gangguan pada sistem Civil Mechanical Electrical (CME). Sistem ini berfungsi untuk memonitor pasokan listrik dari PLN dan Diesel Engine Generator (DEG), suhu dan kelembaban ruangan, serta volume bahan bakar pada tangki suplai DEG. OSASE membantu dalam mendeteksi dan mencegah gangguan yang dapat mempengaruhi layanan telekomunikasi.

# Dashboard

## Monitoring

<img src='/images/dashboard_monitoring.png'>

## Detail Monitoring

<img src='/images/dashbiard_detail.png'>

## Detail RTU

<img src='/images/detail_RTU.png'>

# Functional - Non Functional Requirements

## Functional Requirements

| No  | Functional                                                                                                                                                                                          |
|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|1    | Sistem dapat memfilter dan menampilkan peta informasi terkait RTU dengan visualisasi warna persentase alert port setiap wilayahnya                                                                  |
|2    | Sistem dapat memfilter dan menampilkan informasi terkait RTU dalam bentuk topologi                                                                                                                  |
|3    | Sistem dapat memfilter dan menampilkan informasi terkait port sensor table dalam bentuk tabel                                                                                                       |
|4    | Sistem dapat memfilter dan menampilkan informasi terkait location monitoring dalam bentuk tabel                                                                                                     |
|5    | Sistem dapat menampilkan informasi summary terkait RTU dalam bentuk persentase dan tabel                                                                                                            |
|6    | Sistem dapat menampilkan informasi terkait BBM monitoring dalam bentuk tabel                                                                                                                        |
|7    | Sistem dapat menampilkan informasi summary terkait MD & RTU dalam bentuk tabel                                                                                                                      |
|8    | Sistem dapat menampilkan informasi terkait IP Rectifier Link dalam bentuk tabel                                                                                                                     |
|9    | Sistem dapat menampilkan laporan ketersediaan RTU dalam bentuk tabel                                                                                                                                |
|10   | Sistem dapat menampilkan laporan summary alarm dalam bentuk tabel                                                                                                                                   |
|11   | Sistem dapat menampilkan laporan detail alarm dalam bentuk tabel                                                                                                                                    |
|12   | Sistem dapat memanajemen data user, role, permission, organization, location, notification, telegram group, API, RRD, MD, RTU, port type, BBM tank, BBM pricing, IP rectifier, formula, dan tags    |



## Non - Functional Requirements

| No  | Non Functional                                                      |
|-----|---------------------------------------------------------------------|
|1    | Sistem berupa aplikasi website                                      |
|2    | Website dapat diakses hanya melalui jaringan intranet perusahaan    |
|3    | Website menggunakan sistem operasi Linux Red Hat Enterprise Server  |
|4    | Website menggunakan server platform Nginx                           |
|5    | Website menggunakan aplikasi server NodeJS dan VueJS                |
|6    | Website menggunakan database platform PostgreSQL dan Redis          |
|7    | Website menggunakan third party component Metronics                 |


# Technology Stack

## Frontend

- HTML
- CSS
- Javascript
- Vue Js

## Backend

- Node js

## Database

- Postgree Sql
- Prometheus
- Redis

# Architecture New Osase

<img src='/images/arsitek_osase.png'>

