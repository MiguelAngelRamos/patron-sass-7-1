# Instalaciones necesarias

```sh
npm install bootstrap
```

```sh
npm install sass
```

## Explicación del Patron

Estructura del Proyecto con Patrón 7-1

El patrón 7-1 implica dividir tu código SASS en 7 carpetas diferentes, más un archivo principal (usualmente llamado `main.scss`) que los importa todos. Aquí está la estructura básica que deberías crear dentro de una carpeta llamada `sass` o `styles`:

```
sass/
|
|– abstracts/
|   |– _variables.scss    # Variables de SASS
|   |– _functions.scss    # Funciones de SASS
|   |– _mixins.scss       # Mixins de SASS
|   |– _placeholders.scss # Placeholders de SASS
|
|– base/
|   |– _reset.scss        # Reset/Normalize
|   |– _typography.scss   # Reglas de tipografía
|
|– components/
|   |– _buttons.scss      # Botones
|   |– _carousel.scss     # Carousel
|   |– _modals.scss       # Modales
|   ...                   # Etc.
|
|– layout/
|   |– _header.scss       # Cabecera
|   |– _footer.scss       # Pie de página
|   |– _nav.scss          # Navegación
|   ...                   # Etc.
|
|– pages/
|   |– _home.scss         # Estilos específicos de la página de inicio
|   |– _contact.scss      # Estilos de la página de contacto
|   ...                   # Etc.
|
|– themes/
|   |– _theme.scss        # Estilos de tema específico
|   |– _admin.scss        # Estilos específicos para la administración
|
|– vendors/
|   |– _bootstrap.scss    # Bootstrap sobreescrito
|   |– _jquery-ui.scss    # jQuery UI personalizado
|
`– main.scss              # Archivo principal de SASS
```

# Ejecución para poder compilar de Sass a Css

```
npm start
```