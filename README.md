# Mi personalizada simple terminal
Unas ligeras modificaciones y añadiduras a la [simple terminal](https://st.suckless.org/) para hacerla más de mi agrado al incluir las funcionalidades esenciales para cualquier terminal y mantener a su vez su característica simplicidad.

## Montaje
Bajarse el repositorio:

`git clone git@github.com:pablofs02/st`

Acceder al repositorio:

`cd st`

Compilar el programa (se requiere de un compilador de C):

`sudo make clean install`

## Configuración
Modificar el archivo ***config.def.h*** con las opciones que más guste antes de compilar, borrar ***config.h*** y recompilar.

## Parches añadidos
- **alpha**                       (modificar la transparencia del fondo)
- **bold-is-not-bright**          (distinguir colores brillantes de negrita)
- **gruvbox-material**            (colores para no cansar la vista)
- **ligatures-alpha-scrollback**  (permite ligaduras en las fuentes)
- **scrollback**                  (deslizarse por la terminal)
- **scrollback-mouse**            (deslizarse con el ratón)
- **scrollback-mouse-increment**  (cambiar cuánto se desliza)
- **scrollback-reflow**           (reajuste de salida al cambiar el tamaño)
- **copyurl**                     (copia de url que se muestren en terminal)
