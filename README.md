# Laravel 5x Lang Esp

Este repositorio contiene traducciones en Español para Laravel 5.x.

# Versiones

Estos ficheros con traducciones para validación, contraseñas, paginación y autenticación. <br/>
Adicionalmente incluye internacionalización un fichero de ``.json``

# Instrucciones

Para configurar y cambiar idioma de Laravel 5.x sigue estas instrucciones:

- Paso 1) 

Copiar el directorio ``es`` y el archivo ``es.json`` en la ruta de ``/resources/lang``

- Paso 2)  

Modificar el archivo ``/config/app.php `` 

```php 
    /*
    |--------------------------------------------------------------------------
    | Application Locale Configuration
    |--------------------------------------------------------------------------
    |
    | The application locale determines the default locale that will be used
    | by the translation service provider. You are free to set this value
    | to any of the locales which will be supported by the application.
    |
    */

    'locale' => 'es',
```
