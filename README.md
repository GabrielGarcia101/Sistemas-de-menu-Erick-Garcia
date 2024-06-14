# Sistemas-de-menu-Erick-Garcia

![PROYECTO - Sistema de Menu jpeg](https://github.com/GabrielGarcia101/Sistemas-de-menu-Erick-Garcia/assets/169222036/a3bcaecc-346a-4c68-9521-4d2b5040dc49)

Explicación del código:

MenuBar y Menús: Se crea una MenuBar (menuBar) y se añaden tres menús principales: "Archivo", "Editar" y "Ayuda".

MenuItems: Dentro de cada menú se añaden varios MenuItem. Además, se utiliza SeparatorMenuItem para agregar separadores entre algunos elementos.

Acciones: Se definen acciones para cada MenuItem utilizando expresiones lambda. Por ejemplo, al seleccionar "Nuevo" se imprime un mensaje en la consola.

Layout: Se utiliza un BorderPane (borderPane) como layout principal. La MenuBar se coloca en la parte superior (setTop) del BorderPane.

Ventana "Acerca de...": Se define un método mostrarAcercaDe() que muestra un Alert cuando se selecciona la opción "Acerca de" del menú Ayuda.

Main y lanzamiento: En el método main, se lanza la aplicación llamando a launch(args).
