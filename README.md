# Two Factor Auth

Pequeño proyecto en Laravel de implementación de Autenticación de Dos factores.

## Authors

-   [Joan Zabala](https://www.github.com/jmjzabala)

## Installation

Una vez que clone el proyecto a local entre a la carpeta del mismo.

```bash
    cd two-factor-auth
```

-   Cree una base de datos de nombre: 2fa
-   Renombre el archivo de variables de entorno .env.example a .env
-   Coloque las credenciales de la base de datos en el archivo ".env"
-   Ejecute los siguientes comandos.

```bash
    composer install
    npm install
    php artisan migrate
    npm run dev
    php artisan serve
```

-   Registre un usuario en: [http://127.0.0.1:8000/register](http://127.0.0.1:8000/register)
-   Una vez registrado, inicie sesión y en el lado superior derecho, seleccione del menu desplegable la opción _Profile_.
-   En la sección _Autenticación Two Factor_, habilite la opción.
-   Escanee el código QR con la aplicación _Google Autenticador_ y guarde las claves generadas por prevención.
-   Cierre sesión y vuelva a iniciar.
