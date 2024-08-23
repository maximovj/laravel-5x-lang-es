# laravel-5x-lang-es

Este repositorio contiene traducciones en Español para Laravel 5.x.

# Versiones

Este paquete proporciona los siguientes archivos de traducción:

- Traducciones para validación.
- Traducciones para contraseñas.
- Traducciones para paginación.
- Traducciones para autenticación.
- Archivo de internacionalización en Español en formato `.json`.

# Instrucciones

Para configurar el idioma español en tu aplicación Laravel 5.x, sigue estos pasos:

- Paso 1) 

 Verifica que el directorio `/resources/lang` exista. Si no está creado, créalo.

- Paso 2) 

Copia el directorio ``es`` y el archivo ``es.json`` en la ruta de ``/resources/lang``.

- Paso 3)  

Modifica el archivo de configuración ``/config/app.php`` para establecer el idioma predeterminado en español:

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
