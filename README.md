Paso a paso para instalar e iniciar proyecto
Se debe tener xampp, php 8 y laravel 9
-------------------------------------- 
Clonar proyecto
1. cuando se tenga clonado agregar el archivo .env y el nombre de DB *inclod* 
2. correr *composer install*
3. correr *npm install*
4. crear el .env con referencia del .env.example 
5. correr *php artisan key:generate* 

-------------------------------------
Correr migraciones
1. crear la DB con el nombre inclod
2. correr *php artisan migrate --seed*
-------------------------------------
Encender proyecto
1. correr *php artisan serve*
2. correr *npm run dev*
3. ir a la ruta del login http://127.0.0.1:8000/login

------------------------------
Usuario para iniciar sesión 
  * email = admin@email.com
  * password = 1234567890


Rutas
3. Para crear documentos http://127.0.0.1:8000/doc-document
 