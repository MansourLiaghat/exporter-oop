# 📦 Exporter OOP – مبدل فرمت با برنامه‌نویسی شی‌گرا در PHP

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/MansourLiaghat/exporter-oop)  
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)  
[![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/MansourLiaghat/exporter-oop/releases)

پروژه‌ی **Exporter OOP** یک ابزار ساده و قابل توسعه برای تبدیل داده‌ها به فرمت‌های مختلف مانند JSON، XML و CSV است که با استفاده از زبان PHP و رویکرد برنامه‌نویسی شی‌گرا (OOP) توسعه یافته است. این پروژه به‌عنوان یک نمونه آموزشی برای درک بهتر مفاهیم OOP در PHP طراحی شده است.

## 📚 فهرست مطالب

- [ویژگی‌ها](#-ویژگیها)
- [پیش‌نیازها](#-پیشنیازها)
- [نصب و راه‌اندازی](#-نصب-و-راهاندازی)
- [نحوه استفاده](#-نحوه-استفاده)
- [ساختار پروژه](#-ساختار-پروژه)
- [مجوز](#-مجوز)
- [اطلاعات تماس](#-اطلاعات-تماس)

## ✨ ویژگی‌ها

- تبدیل داده‌ها به فرمت‌های مختلف (JSON، XML، CSV)  
- طراحی ماژولار با استفاده از اصول OOP  
- قابلیت افزودن فرمت‌های جدید با پیاده‌سازی کلاس‌های جدید  
- رابط کاربری ساده برای ورود و مشاهده خروجی تبدیل  

## ⚙️ پیش‌نیازها

- PHP نسخه 7.4 یا بالاتر  
- وب‌سرور محلی مانند XAMPP یا MAMP  

## 🚀 نصب و راه‌اندازی

1. مخزن را کلون کنید:

   ```bash
   git clone https://github.com/MansourLiaghat/exporter-oop.git
   cd exporter-oop
   ```

2. پروژه را در وب‌سرور محلی خود قرار دهید.

3. آدرس فایل `index.php` را در مرورگر باز کنید:

   ```
   http://localhost/exporter-oop/index.php
   ```

## 🧪 نحوه استفاده

1. داده‌های مورد نظر را در فرم وارد کنید.  
2. فرمت خروجی (JSON، XML، CSV) را انتخاب نمایید.  
3. دکمه "Export" را فشار دهید تا نتیجه را مشاهده کنید.  

## 📁 ساختار پروژه

```
exporter-oop/
├── Export/
│   ├── ExportInterface.php
│   ├── JsonExporter.php
│   ├── XmlExporter.php
│   └── CsvExporter.php
├── assets/
│   └── css/
├── autoloader.php
├── index.php
├── process.php
└── README.md
```

## 📄 مجوز

این پروژه تحت مجوز MIT منتشر شده است. برای اطلاعات بیشتر، فایل [LICENSE](LICENSE) را مشاهده نمایید.

## 📬 اطلاعات تماس

- GitHub: [MansourLiaghat](https://github.com/MansourLiaghat)
