## Título
Crear la estructura básica de pantallas de un theme para stepmania 5.0.12


## Descripción general
Requiero los archivos principales de un theme, en los cuales cada uno tenga al menos un color de fondo y un título. En el repositorio nigue/gdbg-2020


## Indicaciones generales
- Crear la configuración general del theme en el archivo `metrics.ini`.
- Crear el código LUA para las clases de stepmania ScreenLogo, ScreenTitleMenu, ScreenSelectStyle, ScreenSelectMode, ScreenSelectSong
- Crear código LUA para cada una de las 5 capas de cada clase, este código debe estar dentro de BGAnimations/
- Usar el sistema de capas de stepmania: Underlay, Background, Main, Overlay, Topmost


## Indicaciones particulares
- En la clase ScreenLogo usar un fondo con el color #545350 en la capa Underlay y un texto al medio en la parte superior: `Screen Logo`.  Este texto debe estar en la capa Overlay.
- En la clase ScreenTitleMenu usar un fondo con el color #e0ded7 en la capa Underlay y un texto al medio en la parte superior: `Screen Title Menu`. Este texto debe estar en la capa Overlay.
- En la clase ScreenSelectStyle usar un fondo con el color #bfbeb8 en la capa Underlay y un texto al medio en la parte superior: `Screen Select Style`. Este texto debe estar en la capa Overlay.
- En la clase ScreenSelectMode usar un fondo con el color #94938f en la capa Underlay y un texto al medio en la parte superior: `Screen Select Mode`. Este texto debe estar en la capa Overlay.
- En la clase ScreenSelectSong usar un fondo con el color #6e6d6a en la capa Underlay y un texto al medio en la parte superior: `Screen Select Song`. Este texto debe estar en la capa Overlay.
- Si es posible agregar en las otras capas de cada clase un objeto simple de color vivo, ya sea un cuadrado, rombo, triangulo o circulo. Creadas a partir de código LUA. Este objeto debe estar en la capa Background de cada clase
- Agregar al inicio de cada archivo un comentario que indique el nombre de la clase y la capa stepmania que representa, por ejemplo: Screen Select Mode - Overlay`
- Indicarme la ruta en donde debo incorporar cada archivo.


## Restricciones
- No usar la declarativa para sobreescribir el theme default


## Recursos útiles
- [codigo stepmania 5](https://github.com/stepmania/stepmania)
- [Theme Simply Love](https://github.com/Simply-Love/Simply-Love-SM5)
- [Theme Lambda](https://github.com/ListenerJubatus/smtheme-fiftyOne)
- [Theme Ultraligth](https://github.com/freem/ultralight)
- [Theme ddr2014](https://github.com/leeium/DDR-2014)


---


## Notas adicionales para Copilot
- Si tienes dudas sobre alguna cosa, pregúntame antes de avanzar.
- Indica los archivos modificados con su ruta.

