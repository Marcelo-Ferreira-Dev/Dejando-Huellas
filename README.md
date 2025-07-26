<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions">
    <img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
  </a>
</p>

---

## 🐾 Dejando Huellas

**Dejando Huellas** es una plataforma integral para la gestión de hogares temporales, adopciones y seguimiento de perros rescatados. Construida con **Laravel 12**, utiliza el potente panel administrativo **Filament** para facilitar el trabajo diario de refugios y protectoras.

### ✨ Características principales

- Gestión completa de perros rescatados.
- Registro y seguimiento de hogares temporales.
- Proceso de adopción con validaciones.
- Panel administrativo moderno con [Filament](https://filamentphp.com/).
- Base de datos PostgreSQL.
- API documentada con Swagger (OpenAPI).
- Tests automáticos y E2E con PHPUnit y Cypress.
- Arquitectura profesional y extensible.

---

## ⚙️ Tecnologías utilizadas

- **PHP 8.3** con Laravel 12
- **Filament** (Panel administrativo)
- **PostgreSQL**
- **Composer**, **NVM**, **Node.js**, **Vite**
- **Swagger** para documentación de API
- **Cypress** para pruebas end-to-end
- **WSL 2** como entorno de desarrollo principal
- **Docker** (opcional para servicios externos)

---

## 🚀 Instalación rápida

```bash
git clone git@github.com:Marcelo-Ferreira-Dev/Dejando-Huellas.git
cd Dejando-Huellas
composer install
cp .env.example .env
php artisan key:generate

# Configura tu base de datos PostgreSQL en .env
php artisan migrate --seed

npm install && npm run dev
php artisan serve
