# toktik

Es un proyecto que te permite visualizar videos, y deslizar para cambiarlos.

## Caracteristicas
En este proyecto tienes distintas caracteristicas que se visualizan mientras se reproduce el video.

 ![Lab: Write your first Flutter app](assets/readme/inicio.jpeg.jpg)

1.  El titulo del video
2.  Cantidad de me gustan
3.  Cantidad de visualizaciones
4.  Gira mientras el video se visualiza
5.  El video como tal

### Transición del video
Adicional se tiene la transicion entre videos, por lo que se muestra el proximo video mientras se sale del video actual.

![Cookbook: Useful Flutter samples](assets/readme/transicion.jpg)

Carga del video se muestra un circular load mientras se espera que el video aparesca

![Carga](assets/readme/carga.png)


##Tecnologia
Esta desarrollado con flutter, la aplicacion contiene videos pregrabados simulando un receptor de videos.

Utiliza un VideoPlayerController para la reproduccion de videos, asi como GestureDetector para pausar o continuar la reproduccion