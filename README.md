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

Desarrollo Web de [`Laravel`](https://laravel.com/docs/10.x) para taquería la flamita. La solución se enfoca en desarrollar toda la infraestructura web (vistas y `APIs`) para la logica de negocios de `la-flamita`.

Este proyecto esta compuesto por 3 submodulos que cuentan con desarrollos diferentes para cubrir distintos requerimientos del cliente.




## Submodulos 🧩


### [`la-flamita-admin`](https://github.com/InterdataUTJ/la-flamita-admin/tree/laravel-10/) 🌐

En este submodulo se encuentra todo el desarrollo de la plataforma web, tanto la `API` como las vistas para acceder a la infraestructura mediante el navegador.

Esta desarrollado utilizando `Laravel` **10.x**, además integra una base de datos `MySQL`. Para desarrollar las interfaces de usuario empleados [`tailwindcss`](https://tailwindcss.com/) y [`flowbite`](https://flowbite.com/) como libreria de componentes.


### [`la-flamita-cliente`](https://github.com/InterdataUTJ/la-flamita-cliente/tree/laravel-10/) 🌐

En este submodulo se encuentra todo el desarrollo de la plataforma web, tanto la `API` como las vistas para acceder a la infraestructura de cliente mediante el navegador. Este subomdulo permite a los clientes realizar compras mediante la `API` de PayPal.

Esta desarrollado utilizando `Laravel` **10.x**, además integra una base de datos `MySQL`. Para desarrollar las interfaces de usuario empleados [`tailwindcss`](https://tailwindcss.com/) y [`flowbite`](https://flowbite.com/) como libreria de componentes.



### [`la-flamita-iot`](https://github.com/InterdataUTJ/la-flamita-iot/tree/29efeaadeebed584f270e37d516a0606f10f9442/) 💡

Este submodulo integra el desarrollo realizado para IoT, el cual consta de un sensor de temperatura que cada cierto tiempo toma una lectura y la envia a la `API` desarrollada en el submodulo [`la-flamita-admin`](https://github.com/InterdataUTJ/la-flamita-admin/tree/laravel-10/), a pesar de que esta pensado para integrarse con este proyecto, la herramienta de configuración permite configurar el sensor para cualquier `API` que acepte los datos en el formato de envio del sensor.

El sensor esta deasrrollado utilizando un `ESP32` con el `Arduino IDE`, además, utilizamos en sensor `DHT11` para la toma de datos del ambiente, y utilizamos el propio hardware del `ESP32` para enviarlos por `WiFi`.

La herramienta de condiguración esta desarrollada en [`ElectronJS`](https://www.electronjs.org/es/) y emplea la libreria [`SerialPort`](https://serialport.io/) para comuicarse con el sensor y ejecutar los comandos de configuración.



### [`la-flamita-movil`](https://github.com/InterdataUTJ/la-flamita-movil/tree/android-kotlin/) 🤖

Este submodulo desarrolla una App Android utilizando `Kotlin` para permitir a los clientes consultar la información de su cuenta rapidamente, acceder a la lista de productos mediante una `API` servida por [`la-flamita-cliente`](https://github.com/InterdataUTJ/la-flamita-cliente/tree/laravel-10), además de poder realizar compras mediante la `API` de PayPal.




## Equipo 👥

Este proyecto esta desarrollado por el equipo escolar `Interdata`, miembros de la carrera `Tecnico Superior Universitario Tecnologias de la Información Area Desarrollo de Software Multiplataforma`, comunmente abreviado como `TSU DSM`, en la `Universidad Tecnologica de Jalisco` (`UTJ`) en la sede de `Ciudad Creativa DIgital` (`CCD`). 

### Integrantes

1. Cortés Gutiérrez Ismael ([`IsmaCortGtz`](https://github.com/IsmaCortGtz))
2. Fernandez Alonso Luis Geronimo ([`Geronimo1231`](https://github.com/Geronimo1231))
3. Fajardo Salaiza Luis Daniel ([`sudo-louis`](https://github.com/sudo-louis))
4. Gomez Magaña Ivan Martin ([`IvanGn`](https://github.com/IvanGn))
5. Lopez Maldonado Brian Alberto ([`Briansixo`](https://github.com/Briansixo))
6. Zepeda Jimenez Francisco Javier