# 🛒 Laravel Minimarket System

Este proyecto es un sistema backend desarrollado con **Laravel**, orientado a la gestión de un **minimarket**. Permite manejar productos, categorías, ventas, clientes y control de stock. Puede ser utilizado junto a un frontend en React, Vue o una app móvil, o directamente con vistas Blade.

---

## 📌 Descripción

**Minimarket System** es una solución administrativa desarrollada en Laravel que permite controlar y automatizar las operaciones clave de un negocio minorista. Desde el registro de productos hasta la generación de ventas, este sistema ofrece una base robusta para administrar un minimarket de forma eficiente.

---

## 🚀 Características Principales

- Gestión de productos (CRUD)
- Control de stock y alertas de bajo inventario
- Registro de ventas y tickets
- Gestión de categorías y unidades
- Módulo de clientes
- Reportes básicos (diarios/mensuales)
- Autenticación y roles (admin, vendedor, etc.)

---

## 🛠️ Tecnologías Utilizadas

- Laravel 8
- PHP 8
- Composer
- MySQL / MariaDB
- Blade (vistas) o API REST (según uso)
- Bootstrap / Tailwind (para el frontend con Blade)
- Laravel Breeze / Sanctum / Passport (para autenticación, según configuración)

---

## 📦 Instalación del Proyecto

1. **Clonar el repositorio**

git clone https://github.com/ClownLuck444/laravel.git
cd minimarket-laravel

2. **Instalar dependencias**
composer install
3. **Configurar el archivo .env**
cp .env.example .env
4. **Ejecutar aplicacion**
php artisan serve

🧱 Estructura Básica
minimarket-laravel/
├── app/
│   ├── Http/
│   ├── Models/        # Producto, Venta, Cliente, etc.
├── database/
│   ├── migrations/
│   ├── seeders/
├── public/
├── resources/
│   └── views/         # Si usas Blade
├── routes/
│   └── web.php / api.php
└── .env
