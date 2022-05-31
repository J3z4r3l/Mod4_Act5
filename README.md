# Introducción
Realice un programa en python, para que en su raspberry pueda jugar en una animación de 800x600 pixeles, donde el objeto a animar se desplaza a lo largo y ancho de la pantalla de juego. Deberá cambiar el objeto de animación, es decir, no usar la imagen chimp y sustituirla por otra de 54x79 pixeles. Además debe cambiar los efectos sonoros del juego. Deberá agregar un icono en el escritorio para su acceso usando un script.

La evidencia de esta actividad es un reporte en github con los detalles de la implementación de la actividad.

# Desarrollo 
Este programa fue desarrollado con temática del perrito cheems que se viralizo en internet hace unos años y que sigue vigente todavía. Nuestro programa desplegará un cheems que se moverá aleatoriamente a lo largo de la pantalla mientras el usuario tratará de golpearlo, esto genera dos posibles casos de prueba, el primero donde no acertamos el golpe y sonará un sonido por unos segundos (audio2.wav) y si se alcanza a golpear reproduce un sonido diferente (audio.wav), al mismo tiempo la imagen de cheems girara por lagunos segundos 

[Explicación del código y como se armo para que pudiera hacer eso]

Como punto final, creamos el icono que solicitaba la actividad, este nos permite tener un rapido acceso al programas y automatiza los procesos de ejecucion. 
Para lograr esto necesitamos 2 archivos;

1.- chems_game.sh: Accede al archivo lo ejecuta.
```Bash
cd /home/pi/Desktop/actividad5
python3 actividad5.py &
```
2.- chemsito.desktop: En este archivo configuramos el nombre, comentario, e imagen del icono. tambien le indicamos la ruta del archivo sh que debe ejecutarse al presionar el icono

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
![icono2](https://user-images.githubusercontent.com/100887194/171081796-3d6c52b6-1c7a-4fb2-bf23-fa1bff9356b7.png)
                                                                                                          _Icono_



# Resultados

![image](https://user-images.githubusercontent.com/88802298/171070476-e4dfbb24-dace-48a4-b1da-968cb081a0b3.png)
                                                                                                                                                _Ejecución del código_
                                                                                           
A pesar de que hubo dificultades al programar que el personaje tuviera una posicion aleatoria dentro de la pantalla principal, logramos solucionarlo.
De esta manera logramos que el codigo funcionara exitosamente como se muestra en la imagen anterior, del mismo modo se cumpliron con todas la especificaiones que la tarea demandaba.

# Conclusiones

Angel Ramirez:  Considero que la actividad fue bastante retadora y a la vez muy enriquecedora, pues nos permitio poner en practica varios de los conocimientos adquiridos en en el modulo, y a pesar de las dificultades que se nos pudieron presentar, esta actividad me permitio comprender basicamente como funcionan algunas animaciones y los iconos, que son elementos muy reelevantes y bastante utiles ya que nos ahorran tiempo de buscar archivos y ejecutarlos manualmente.
                                                                                   
Jezarel Sanchez: La actividad nos permitio integrar varios conceptos ya vistos en python, con el plus de que hubo varios nuevos que nos permitían trabajar con las animaciones y sonidos que mejoraban la experiencia del usuario 

Jonathan Josafat: Realizar esta actividad nos permitió comprender un pocomejor el funcionamiento de la libreria pygame, usando un ejemplo con el que podemos tener un programa basico y podemos ampliarlo a un trabajo mucho más realizado.
                                                                                           
