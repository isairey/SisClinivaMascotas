<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

# 🐾 Sistema de Clínica Veterinaria

Aplicación web desarrollada en **PHP con Laravel** utilizando **Blade** como motor de plantillas. Este sistema permite gestionar de manera eficiente la información de una clínica veterinaria, incluyendo mascotas, dueños, citas y registros clínicos.

---

## 📋 Descripción

Este sistema fue diseñado para digitalizar y optimizar la administración de una clínica veterinaria, permitiendo un control organizado de pacientes (mascotas), propietarios y servicios médicos.

---

## 🎯 Objetivo

* Centralizar la información de la clínica
* Mejorar la gestión de pacientes y citas
* Facilitar el acceso a historiales clínicos
* Automatizar procesos administrativos

---

## 🚀 Características

* 🐶 Gestión de mascotas (CRUD)
* 👤 Registro de dueños
* 📅 Administración de citas
* 🩺 Historial clínico
* 💊 Registro de tratamientos
* 💰 Control de servicios y pagos
* 🔐 Sistema de autenticación de usuarios
* 📊 Panel administrativo

---

## 🛠️ Tecnologías Utilizadas

* 🐘 PHP
* 🚀 Laravel
* 🎨 Blade
* 🗄️ MySQL
* 🌐 HTML, CSS, JavaScript
* 🧰 Composer

---

## 📦 Instalación

### 1️⃣ Clonar el repositorio

```bash id="g2n7k1"
git clone https://github.com/isairey/SisClinicaMascotas.git
cd SistemaClinicaMascotas
```

---

### 2️⃣ Instalar dependencias

```bash id="d8p3m9"
composer install
npm install
```

---

### 3️⃣ Configurar entorno

```bash id="h5r2v7"
cp .env.example .env
```

Configura tu base de datos en `.env`:

```env id="w1k8q4"
DB_DATABASE=clinica_veterinaria
DB_USERNAME=root
DB_PASSWORD=
```

---

### 4️⃣ Generar clave de aplicación

```bash id="u9z6x2"
php artisan key:generate
```

---

### 5️⃣ Ejecutar migraciones

```bash id="p4c7n3"
php artisan migrate
```

---

### 6️⃣ Ejecutar el servidor

```bash id="v2m9q6"
php artisan serve
```

👉 Accede en: http://localhost:8000

---

## 📁 Estructura del Proyecto

```id="t6y1k8"
app/
 ┣ 📂 Models/
 ┣ 📂 Http/
 ┃ ┗ 📂 Controllers/
resources/
 ┣ 📂 views/ (Blade)
 ┣ 📂 css/
 ┗ 📂 js/
routes/
 ┗ 📄 web.php
database/
 ┗ 📂 migrations/
```

---

## 🔌 Funcionalidades

### 🐾 Mascotas

* Registro de pacientes
* Asociación con dueños
* Edición y eliminación

---

### 👤 Dueños

* Gestión de clientes
* Historial de mascotas

---

### 📅 Citas

* Programación de consultas
* Control de fechas

---

### 🩺 Historial Clínico

* Diagnósticos
* Tratamientos
* Medicamentos

---

## 🔐 Seguridad

* Autenticación de usuarios
* Protección CSRF
* Validación de formularios
* Control de acceso por roles

---

## 🧪 Pruebas

```bash id="r3m8k5"
php artisan test
```

---

## 🤝 Contribuciones

1. Fork del repositorio
2. Crear una rama (`git checkout -b feature/nueva-funcionalidad`)
3. Commit (`git commit -m 'Nueva funcionalidad'`)
4. Push (`git push origin feature/nueva-funcionalidad`)
5. Crear Pull Request

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT.

---

## 👨‍💻 Autor

Desarrollado por **Isai Reyes**

