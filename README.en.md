<h1 align="center">
  <img src="./la-flamita.svg" alt="la-flamita-web" width="200">
  <br>
  La Flamita
  <br>
  <br>
</h1>

<p align="center">
  <!-- Web -->
  <a href="https://laravel.com/"><img src="https://img.shields.io/badge/Built_using-Laravel-red.svg?logo=laravel" alt="laravel"></a>
  <a href="https://laravel.com/docs/10.x"><img src="https://img.shields.io/badge/Laravel-10.x-red.svg?logo=laravel" alt="laravel-version"></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Made_with-Tailwind-blue.svg?logo=tailwindcss" alt="tailwindcss"></a>
  <a href="https://flowbite.com/"><img src="https://img.shields.io/badge/Using-Flowbite-blue.svg" alt="flowbite"></a>
  <!-- IoT -->
  <a href="https://www.arduino.cc/"><img src="https://img.shields.io/badge/Built_using-Arduino-lightgray.svg?logo=arduino" alt="arduino"></a>
  <a href="https://www.espressif.com/en/products/socs/esp32"><img src="https://img.shields.io/badge/Made_for-ESP32-orangered.svg?logo=espressif" alt="esp32"></a>
  <a href="https://www.electronjs.org/es/"><img src="https://img.shields.io/badge/Tool-ElectronJS-royalblue.svg?logo=electron" alt="electronjs"></a>
</p>

[`Laravel`](https://laravel.com/docs/10.x) web development for La Flamita taqueria. The solution focuses on developing the entire web infrastructure (views and `APIs`) for La Flamita's business logic.

This project is composed of three submodules with different developments to meet different client requirements.

## Submodules 🧩

### [`la-flamita-admin`](https://github.com/InterdataUTJ/la-flamita-admin/tree/laravel-10/) 🌐

This submodule contains all the development work for the web platform, including both the API and the views for accessing the infrastructure through the browser.

It is developed using Laravel 10.x and integrates a MySQL database. [`Tailwindcss`](https://tailwindcss.com/) and [`flowbite`](https://flowbite.com/) are used as component libraries to develop the user interfaces.

### [`la-flamita-cliente`](https://github.com/InterdataUTJ/la-flamita-cliente/tree/laravel-10/) 🌐

This submodule contains all the development work for the web platform, including both the API and the views for accessing the client infrastructure through the browser. This submodule allows customers to make purchases using the PayPal API.

It is developed using Laravel 10.x and integrates a MySQL database. [`Tailwindcss`](https://tailwindcss.com/) and [`flowbite`](https://flowbite.com/) are used as component libraries to develop the user interfaces.

### [`la-flamita-iot`](https://github.com/InterdataUTJ/la-flamita-iot/tree/29efeaadeebed584f270e37d516a0606f10f9442/) 💡

This submodule integrates the development carried out for IoT, which consists of a temperature sensor that periodically takes a reading and sends it to the API developed in the [`la-flamita-admin`](https://github.com/InterdataUTJ/la-flamita-admin/tree/laravel-10/) submodule. Although it is designed to integrate with this project, the configuration tool allows the sensor to be configured for any API that accepts data in the sensor's transmission format.

The sensor is developed using an ESP32 with the Arduino IDE. We also use the DHT11 sensor to collect ambient data, and we use the ESP32's own hardware to send it over WiFi.

The configuration tool is developed in [`ElectronJS`](https://www.electronjs.org/es/) and uses the [`SerialPort`](https://serialport.io/) library to communicate with the sensor and execute the configuration commands.

### [`la-flamita-movil`](https://github.com/InterdataUTJ/la-flamita-movil/tree/android-kotlin/) 🤖

This submodule develops an Android App using `Kotlin` to allow customers to quickly consult their account information, access the list of products through an `API` served by [`la-flamita-cliente`](https://github.com/InterdataUTJ/la-flamita-cliente/tree/laravel-10), and also be able to make purchases through the PayPal `API`.

## Team 👥

This project is developed by the school team `Interdata`, members of the career `Tecnico Superior Universitario Tecnologias de la Información Area Desarrollo de Software Multiplataforma`, commonly abbreviated as `TSU DSM`, at the `Universidad Tecnologica de Jalisco` (`UTJ`) at the headquarters of `Ciudad Creativa DIgital` (`CCD`).

### People

1. Cortés Gutiérrez Ismael ([`IsmaCortGtz`](https://github.com/IsmaCortGtz))
2. Fernandez Alonso Luis Geronimo ([`Geronimo1231`](https://github.com/Geronimo1231))
3. Fajardo Salaiza Luis Daniel ([`sudo-louis`](https://github.com/sudo-louis))
4. Gomez Magaña Ivan Martin ([`IvanGn`](https://github.com/IvanGn))
5. Lopez Maldonado Brian Alberto ([`Briansixo`](https://github.com/Briansixo))
6. Zepeda Jimenez Francisco Javier
