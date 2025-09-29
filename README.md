# 🔐 Validation & Authorization (PHP + MySQL)

## 🇷🇺 Описание (Russian)

Этот учебный проект я написал на **3-ем семестре**, когда только начал изучать PHP и MySQL.  
Задача проекта — реализовать **простую систему регистрации и авторизации пользователей** с сохранением данных в базе.  

### 📌 Основной функционал
- 📥 Регистрация нового пользователя (логин, пароль, имя)  
- 🔑 Авторизация через форму входа  
- 🛡️ Минимальная валидация (проверка длины логина, имени и пароля)  
- 💾 Хранение данных в MySQL  
- 🔒 Простое хеширование паролей (MD5 с "солью")  

> ⚠️ Проект учебный, поэтому код небезопасный для реального продакшена  
> (например, использует MD5 вместо `password_hash()` и есть уязвимости SQL-инъекций).  

---

## 🇬🇧 Description (English)

This is a **learning project** I built in my **3rd semester** while starting with PHP and MySQL.  
The goal was to implement a **basic user registration and login system** with database storage.  

### 📌 Main features
- 📥 User registration (login, password, name)  
- 🔑 Login form with authentication  
- 🛡️ Basic validation (checking login, name, and password length)  
- 💾 Data stored in MySQL  
- 🔒 Simple password hashing (MD5 with "salt")  

> ⚠️ This project is for educational purposes only.  
> The code is not secure for production use (e.g. MD5 instead of `password_hash()`, SQL injection risks).  

---

## ⚙️ Технологии / Technologies
- PHP  
- MySQL  
- HTML + CSS (Bootstrap)  

---

## 🚀 Как запустить / How to run
1. Скопировать проект в папку `htdocs` (XAMPP).  
2. Создать базу данных `register-bd` в MySQL.  
3. Импортировать таблицу `users` (структура: `id`, `login`, `pass`, `name`).  
4. Открыть `http://localhost/project/index.php`.  

---

✍️ Автор: **Farrux (alibayev03)**
