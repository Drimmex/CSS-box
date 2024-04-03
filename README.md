# CSS-box
 
* ¿Qué es el box-model?
Cada objeto dentro de una pagina y/o aplicación web puede ser visto como una caja, con todo lo que esto implica

# Conceptos básicos del modelo de cajas (Box-model)

* Características una caja en el box-model.
Existen tres caracteriscas fundamentales a tener en cuenta en el box-model:
Padding, margin y border, cada uno de los cuales le da una característica diferente a las cajas que mencionamos anteriormente.

    * padding: aumenta el espacio entre el borde de un cuadro y el contenido del cuadro.
    * margin: marginaumenta el espacio entre los bordes de un cuadro y los bordes de cuadros adyacentes.
    * border: agrega espacio (incluso si es solo uno o dos píxeles) entre el margen y el relleno.

* Propiedades
Las propiedades de las cajas permiten ajustar y darle un determinado formato a las mismas, las propiedades son cruciales a la hora de diseñar y maquetar paginas y/o aplicaciones web, puesto que permiten modificar y ajustar cada aspecto de las cajas.

    * box-sizing: esta propiedad cuenta con dos opciones, content-box y border-box
        *content-box: separa el el tamaño real de contenido de la caja del resto de propiedades, por ejemplo, si tienes un div de 10px por 10px, este div se mantendrá igual, solo cambiarán los valores de las propiedades.
        *border-box: Une los valores del tamaño real de contenido con las del resto de las propiedades, por ejemplo, si tienes un div de 240px por 440px y a este le das un padding de 40px, lo que pasará es que el paddind tomara parte del valor tamaño real del contenido reduciéndolo, manteniendo el div del mismo tamaño, sin embargo dándole la propiedad que declaraste anteriormente.


