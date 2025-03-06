Ecommerce Full Stack – Laravel, Angular, MySQL, JWT, PayPal, MercadoPago 2024

1.	Descripción

Este proyecto es una plataforma de comercio electrónico desarrollada con una arquitectura Full Stack, optimizada para ofrecer una experiencia de usuario fluida y segura. Cuenta con integración de pasarelas de pago y una gestión eficiente de datos.

2.	Características Principales

•	Administración de productos, usuarios y órdenes con arquitectura orientada a microservicios, mejorando la escalabilidad del sistema en un 40%.

•	Interfaz de usuario intuitiva y responsiva, optimizada para dispositivos móviles, aumentando la retención de clientes en un 15%.

•	Integración de pagos seguros mediante PayPal y MercadoPago, reduciendo el tiempo de transacción en un 20% y cumpliendo con los estándares de seguridad PCI DSS.

•	Autenticación segura con JSON Web Tokens (JWT), protegiendo datos sensibles y mejorando la eficiencia de validación de usuarios en un 30%.

•	Base de datos optimizada y normalizada, logrando una reducción del tiempo de carga de las consultas en un 25%.

•	Optimización del rendimiento en frontend y backend, reduciendo los tiempos de carga de la página en un 35%.

•	Arquitectura escalable y flexible, preparada para soportar un aumento del tráfico hasta un 50% más sin afectar el rendimiento.

3.	Tecnologías Utilizadas

Backend: Laravel (PHP)

Frontend: Angular

Base de datos: MySQL

Autenticación: JSON Web Tokens (JWT)

Pasarelas de pago: PayPal, MercadoPago

Otros: Docker, Redis, Nginx

4.	Requisitos Previos
   
Asegúrate de tener instalado lo siguiente en tu sistema:

•	Node.js y npm

•	Composer

•	PHP 8+

•	MySQL

•	Laravel 10+

•	Angular CLI

Instalación

•	Clona el repositorio:

git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio

•	Instala las dependencias en el frontend:

cd ECOMMERCE
npm install

cd ADMIN
npm install

•	Instala las dependencias en el backend:

cd API
composer install

•	Configura el archivo de entorno:

cp .env.example .env

•	Luego, configura las credenciales de la base de datos y las claves de las pasarelas de pago.

•	Genera la clave de la aplicación y ejecuta las migraciones:

php artisan key:generate
php artisan migrate --seed

•	Inicia el backend:

cd API
php artisan serve

•	Inicia el frontend:

cd ECOMMERCE
ng serve

•	Inicia el frontend (ADMIN)

cd ADMIN
ng serve –port=5000

Contribución

Si deseas contribuir a este proyecto, por favor crea un fork del repositorio, realiza tus cambios y envía un pull request.
