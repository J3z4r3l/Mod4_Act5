# Introducción
Realice un programa en python, para que en su raspberry pueda jugar en una animación de 800x600 pixeles, donde el objeto a animar se desplaza a lo largo y ancho de la pantalla de juego. Deberá cambiar el objeto de animación, es decir, no usar la imagen chimp y sustituirla por otra de 54x79 pixeles. Además debe cambiar los efectos sonoros del juego. Deberá agregar un icono en el escritorio para su acceso usando un script.

La evidencia de esta actividad es un reporte en github con los detalles de la implementación de la actividad.

# Desarrollo 
Este programa fue desarrollado con temática del perrito cheems que se viralizo en internet hace unos años y que sigue vigente todavía. Nuestro programa desplegará un cheems que se moverá aleatoriamente a lo largo de la pantalla mientras el usuario tratará de golpearlo, esto genera dos posibles casos de prueba, el primero donde no acertamos el golpe y sonará un sonido por unos segundos (audio2.wav) y si se alcanza a golpear reproduce un sonido diferente (audio.wav), al mismo tiempo la imagen de cheems girara por lagunos segundos 

[Explicación del código y como se armo para que pudiera hacer eso]

Como punto final, creamos el icono que solicitaba la actividad, este nos permite tener un rapido acceso al programas y automatiza los procesos de ejecucion. 
Para lograr esto necesitamos 2 archivos;




```desktop
[Desktop Entry]
Name=Chemsito
Comment=Bonk
Icon=/home/pi/Desktop/actividad5/icono.jpeg
Exec=/home/pi/chems_game.sh
Type=Application
Encoding=UTF-8
Terminal=false
```


![image](https://user-images.githubusercontent.com/88802298/171071443-666dea7b-fa2e-4a62-981b-ee7920798365.png)

# Resultados

![image](https://user-images.githubusercontent.com/88802298/171070476-e4dfbb24-dace-48a4-b1da-968cb081a0b3.png)
