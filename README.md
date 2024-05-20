# Pasos para correr el proyecto
## !importate: debe tener instalado algun servidor de apache php, como Xamp, Laragon o Wamp, sino lo tiene instalelo y clone en la capeta www o htdocs
## Busque los scrips para generar la base de datos


1. Clona el repositorio de github
2. abre una terminal con la ruta del proyecto y escriba el comando: composer install
3. ejecute el comando: npm install
4. Duplica el archivo .env.example y renómbralo a .env 
    Edita el archivo .env e incluye los datos de conexión de la base de datos (por ejemplo, host, base de datos, usuario y contraseña).
5. Ejecua el comando: php artisan key:generate
6. ejecuta el comando: php artisan migrate
7. ejecuta el comando: php artisan serve

## Abre la dirección localhost:8000 en tu navegador para ver el proyecto de Laravel en funcionamiento.
