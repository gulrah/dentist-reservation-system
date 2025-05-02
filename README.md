# 🦷 Dentist Reservation System

![Laravel](https://img.shields.io/badge/Laravel-10.x-f9322c?style=flat&logo=laravel)
![PHP](https://img.shields.io/badge/PHP-%5E8.1-8892BF?style=flat&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-8.x-00618A?style=flat&logo=mysql)
![Chart.js](https://img.shields.io/badge/Chart.js-4.x-FF6384?style=flat&logo=chartdotjs)

> **A multilingual appointment platform for dental clinics**  
> Author: **Gulnar Rahimli**

---

## ✨ Key Features
| Module | Highlights |
| ------ | ---------- |
| **Online Booking** | Patient‑friendly form, real‑time slot check (AJAX) |
| **Admin Dashboard** | Statistics rendered with **Chart.js** (appointments, revenue, patients) |
| **Notifications** | Real‑time alerts via AJAX polling |
| **E‑mail** | SMTP integration for confirmations & reminders |
| **Languages** | English · Azerbaijani · Russian |
| **CMS** | Blog, FAQ, gallery, contact page |
| **Role-Based Access** | Admin, Dentist, Reception panels |
| **Frontend** | HTML, CSS, Bootstrap, jQuery (no SPA or Vue) |

---

## 🛠 Tech Stack
| Layer | Tech |
| ----- | ---- |
| **Backend** | Laravel 10 · PHP 8.2 |
| **Database** | MySQL 8 |
| **Frontend** | Blade templates · HTML · CSS · JavaScript · jQuery · Chart.js |
| **E‑mail** | Laravel Mail + SMTP |
| **Languages** | Laravel JSON & PHP-based translation (ENG · AZ · RU)

---

## 🚀 Quick Start

```bash
git clone https://github.com/gulrah/dentist-reservation-system.git
cd dentist-reservation-system

# setup
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed


php artisan serve    # http://localhost:8000
