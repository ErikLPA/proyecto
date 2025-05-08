#🗓️ Reserva de habitacion de hotel


la we  es una aplicación web sencilla desarrollada en PHP con base de datos en MySQL, que permite registrar y gestionar habitacione o reservas ingresando los siguientes datos: Fecha De Ingreso ,fecha salida,Tipo De Adulto, tipo de Niño ,numero De habitacion

#📌 Características
Registro de reservas mediante formulario.

Almacenamiento en base de datos MySQL.

Validación básica de campos requeridos.

Interfaz sencilla y funcional.

🛠️ Requisitos
Servidor web (como Apache o Xampp)

PHP 8.x o superior

MySQL 5.x o superior

Navegador web

🚀 Instalación
Clona el repositorio o copia los archivos del proyecto en tu servidor local:

bash
Copiar
Editar
git clone https://github.com/tuusuario/mini-agenda-turnos.git
Crea una base de datos en MySQL, por ejemplo:

sql
Copiar
Editar
CREATE DATABASE hotel_booking;
Importa la estructura de la base de datos con el siguiente SQL:

sql
Copiar
Editar
CREATE TABLE `reservas` (
  id int(11) NOT NULL,
  arrival_date datetime NOT NULL,
  departure_date datetime NOT NULL,
  adult_type varchar(50) NOT NULL,
  child_type varchar(50) NOT NULL,
  number_of_rooms varchar(50) NOT NULL,
  created_at timestamp NOT NULL DEFAULT current_timestamp()

Configura la conexión a la base de datos en tu archivo PHP (por ejemplo config.php):

php
Copiar
Editar
Abre el proyecto en tu navegador (por ejemplo, http://localhost/royal-master/) y comienza a registrar turnos.

🧾 Estructura del formulario
Los campos que se deben ingresar son:
rut	 (text)
Fecha Ingreso	(Fecha y hora)
Fecha Salida (Fecha y hora)
Tipo Adulto
Tipo Niño	
Número de Habitaciones

Número de Habitaciones

Nombre (Texto)

Correo (Correo electrónico)

Habitación (Texto o número)

Fecha de ingreso (Fecha)

Fecha de salida (Fecha)


📄 Licencia
Este proyecto es de uso libre y puede ser modificado o reutilizado según tus necesidades.
