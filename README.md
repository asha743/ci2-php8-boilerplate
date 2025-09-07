# CodeIgniter 2 PHP 8 Boilerplate

🚀 A modernized boilerplate for CodeIgniter 2 projects running on PHP 8.2/8.3+.This project patches the original CodeIgniter 2.2.6 core (system/ folder) to remove deprecated features, fix dynamic property issues, and update old MySQL calls for compatibility with modern PHP and MariaDB/MySQL.

## ✨ Features

✅ Fully compatible with PHP 8.2/8.3

✅ Dynamic properties declared (no more deprecation warnings)

✅ Replaced legacy mysql_* with mysqli

✅ Clean CodeIgniter 2.2.6 core ready for new projects

✅ Drop-in boilerplate for legacy CI2 apps that need to run today

✅ Works with MariaDB/MySQL 5.7+

## 📖 Why This Exists

CodeIgniter 2 was officially retired in 2015 and was never updated for PHP 7 or PHP 8.However, many developers still maintain or extend legacy CodeIgniter 2 applications.This repo provides a drop-in foundation so you can:

Build new projects with the lightweight CI2 framework on modern PHP

Upgrade old CI2 apps to run without errors on PHP 8+

Avoid fighting with deprecated features every time you set up a project

## 📂 Project Goals

Provide a stable boilerplate for CodeIgniter 2 apps running on PHP 8+

Document all changes made to the core for future maintainers

Keep this project as a reference for legacy CI2 modernization

Encourage community-driven improvements for security, performance, and developer experience

## 🔧 Getting Started

Clone this repo

Configure application/config/config.php and application/config/database.php

Point Apache/Nginx to the project’s root and enable mod_rewrite

Start building your app 🚀

## 🤝 Contributing

This project is open to contributions! If you’ve modernized a part of CodeIgniter 2, improved security, or added useful developer tools, feel free to:

Fork the repo

Create a new branch

Submit a pull request

Ideas for future contributions:

Add Composer support

Replace CI2’s old encryption class with OpenSSL

Provide a migration path to CodeIgniter 3/4 while keeping CI2 compatibility

## 🔍 Keywords

CodeIgniter 2, PHP 8, legacy framework, CodeIgniter 2 boilerplate, CodeIgniter PHP 8 compatibility, PHP 8 upgrade, CodeIgniter 2.2.6, CodeIgniter deprecated, modern CodeIgniter 2, PHP 8 migration

