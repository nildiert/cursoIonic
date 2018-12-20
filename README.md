# cursoIonic

## ¿Que es?

Framework basado en Angular que permite crear aplicaciones hibridas 

## Contenido

1. Introducción y setup del entorno
2. Aspectos básicos de Ionic
3. Navegación
4. Temas(estilo)
5. CRUD en ionic y Firebase
6. Deployment
7. Conclusión


## Prerequisitos

* Javascript
* Html
* Css
* Api Rest
* Adicionales
  - Typescript
  - Angular
  - Desarrollo movil en cualquier plataforma
  
  ## Herramientas usadas
  * Navegador web
  * Editor de texto
  * Node JS (*npm*)
  * Ionic CLI
  
  ## Ionic CLI
  
  Ionic CLI nos permite:
  
  * Crear proyectos 
  * Generar
    - Componentes
    - Rutas
    - Servicios
    - Pipes
    - Etc
  * Correr app localmente
  * Hacer testing 
  * Preparar app para producción
  * Compilar app nativa
  
  ## Instalar ionic CLI 

  npm install -g ionic
  *Instalamos globalmente ionic y ya 
  
  ## Crear nueva app
  
  *Para crear una app 
  ionic start geocaching blank
  (No instalar la versión de ionic 4)
  
  ## Ejecutar servidor
  ionic serve
  
  ## Estructura de archivos
 Node modules :  Guarda dependencias
 src : Guarda los archivos donde hacemos el desarrollo
  - app : Guarda los componentes
 assets: Plantillas, imagenes
 Theme: Información de estilo
 www: Guarda todo lo qwue vemos en el navegador
 
 ## Estructura básica de pagina en Ionic
 * src/pages/home/home.html: Guarda la información de la vista principal
 
## Generar componentes

ionic generate --help (component, page, directive, page, pipe, provider, tabs)

ionic generate page Lugar

## Navegar a una pagina

Agregar en appModule

declarations: [
    LugarPage
],
entryComponents: [
LugarPage
]


  
  
    


