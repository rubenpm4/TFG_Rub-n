<<<<<<< HEAD
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
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

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
=======
# Kizuma: Red Social para Conectar Personas

## 🧠 Introducción

Las redes sociales actuales suelen priorizar algoritmos complejos, monetización agresiva y funcionalidades que muchas veces desvían del propósito original: conectar personas.  
**Kizuma** (inspirado en *Kizuna*, "lazo" en japonés) es una red social minimalista centrada en la conexión humana real.

La aplicación permitirá a los usuarios:
- Registrarse y crear perfiles personales.
- Agregar amigos y gestionar una lista de contactos.
- Publicar actualizaciones (texto, imágenes) y comentar publicaciones de otros.
- Interactuar sin algoritmos ni distracciones.

---

## 🎯 Finalidad

Desarrollar una red social **básica pero funcional** utilizando Laravel, enfocada en la simplicidad, privacidad y usabilidad.

---

## 🎯 Objetivos

### Objetivo principal
- Crear una red social funcional con perfiles, amistades, publicaciones y comentarios usando Laravel.

### Objetivos específicos
1. Autenticación segura (registro, login, recuperación de contraseña).
2. Sistema de amistad: solicitudes, aceptación/rechazo, lista de contactos.
3. Publicaciones y comentarios: CRUD completo.
4. Perfiles personalizables: nombre, biografía, foto de perfil.
5. Feed principal con publicaciones de amigos en orden cronológico.
6. Interfaz moderna, ligera y responsiva.

---

## 🛠️ Medios y Recursos

### Tecnologías
- **Backend:** Laravel 10 (PHP)
- **Frontend:** Blade o Livewire
- **Base de datos:** MySQL
- **Autenticación:** Laravel Breeze o Jetstream
- **Diseño:** Tailwind CSS (preferido) o Bootstrap
- **Hosting:** Laravel Forge, Vercel (adaptado), o servidor compartido

### APIs opcionales
- **Cloudinary** para imágenes.
- **Pusher** para notificaciones en tiempo real.

### Conocimientos requeridos
- Laravel Eloquent y relaciones (User -> Friends, Post -> Comments).
- Patrón MVC.
- Migraciones y bases de datos relacionales.
- Diseño de interfaces con Tailwind CSS.

---

## 🗓️ Planificación Estimada

| Fase                 | Descripción                                                   | Duración     |
|----------------------|---------------------------------------------------------------|--------------|
| **Fase 1 - Análisis** | Definir requisitos y arquitectura del sistema                 | 1-2 semanas  |
| **Fase 2 - Diseño**   | Prototipos en Figma, estructura de datos e interfaz           | 2 semanas    |
| **Fase 3 - Desarrollo**| Implementación del backend y frontend                        | 4-6 semanas  |
| **Fase 4 - Pruebas y Lanzamiento** | Testing manual, optimización, correcciones   | 3 semanas    |

---

## 📚 Bibliografía y Referencias

- [Documentación Oficial de Laravel 10](https://laravel.com/docs/10.x)
- [Laravel Breeze (Autenticación simple)](https://laravel.com/docs/10.x/starter-kits#laravel-breeze)
- [Eloquent Relationships](https://laravel.com/docs/10.x/eloquent-relationships)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [Refactoring UI](https://refactoringui.com/book/)

---

## 📌 Diferencial del Proyecto

✔ Interfaz limpia y ligera  
✔ Sin algoritmos manipulando el feed  
✔ Sin publicidad invasiva  
✔ Proyecto open-source (potencialmente)

---

## 🚀 Estado actual del desarrollo

**[Por iniciar]** – Estructura del proyecto y entorno de desarrollo pendiente de configurar.

---

>>>>>>> 6f7d7f8cb835ea5f621e903d289eede6d48e8f3b
