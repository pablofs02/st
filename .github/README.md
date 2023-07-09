# Mi personalizada simple terminal
Mi versión personal de [simple terminal](https://st.suckless.org/) para hacerla más de amigable al incluir las funcionalidades esenciales para cualquier terminal y mantener a su vez su característica simplicidad.

## Montaje
Bajarse el repositorio:

`git clone git@github.com:pablofs02/st`

o

`git clone https://github.com/pablofs02/st`

Acceder al repositorio:

`cd st`

Compilar el programa (se requiere de un compilador de C):

`sudo make install`

## Configuración
Modificar el archivo ***config.h*** con las opciones que más le guste antes de compilar.

## Parches añadidos
- **alpha**                       (modificar la transparencia del fondo)
- **anysize**                     (cambia el tamaño de la ventana en función del de la ventana)
- **bold-is-not-bright**          (distinguir colores brillantes de negrita)
- **copyurl**                     (copia de url que se muestren en terminal)
- **gruvbox-material**            (colores para no cansar la vista)
- **ligatures-alpha-scrollback**  (permite ligaduras en las fuentes)
- **newterm**                     (abre una nueva terminal en el mismo directorio)
- **open_copied_url**             (abre la url copiada en el navegador)
- **scrollback**                  (deslizarse por la terminal)
- **scrollback-mouse**            (deslizarse con el ratón)
- **scrollback-mouse-increment**  (cambiar cuánto se desliza)
- **scrollback-reflow**           (reajuste de salida al cambiar el tamaño)
- **keyboard-select**
- ¿Soportear IME?
