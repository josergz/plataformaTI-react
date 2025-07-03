# Plataforma TI - Laravel + React

Este proyecto es una aplicación web construida con **Laravel 12** y **React** usando el **Starter Kit oficial** de Laravel.

## 🚀 Requisitos

Antes de comenzar, asegúrate de tener instalado:

- PHP >= 8.2
- Composer
- Node.js y npm
- MySQL
- Laragon o XAMPP (opcional, recomendado para desarrollo local en Windows)

## ⚙️ Instalación

Clona el repositorio e ingresa a la carpeta del proyecto, asegurate de ejecutar las siguientes instrucciones desde la terminal:

```bash
composer install
```

```bash
npm install
```

```bash
copy .env.example .env
```

```bash
php artisan key:generate
```

```bash
php artisan migrate
```

## 🏃‍♂️ Uso

Inicia el servidor Laravel+React:

```bash
php artisan serve
```

> _Nota_ : Puedes omitir este paso si usas Laragon/XAMPP como virtual host .

```bash
npm run dev
```

Accede a la aplicación desde la URL que Laragon/XAMPP te asigne, por ejemplo: http://plataformati.test .

## 👥 Contribuidores

[![Contribuidores](https://contrib.rocks/image?repo=josergz/plataformaTI-react)](https://github.com/josergz/plataformaTI-react/graphs/contributors)
