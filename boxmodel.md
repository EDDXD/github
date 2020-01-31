># **BoxModel**
>El BoxModel es un conjunto de propiedades que definen partes de un elemento que ocupa espacio en una **página web**, esto incluye a Padding**(Relleno)** y Margin**(Margen)**.
>
>En términos cortos es un módulo CSS que define **cajas** rectangulares, ya que en cada etiqueta **HTML** se crea una caja rectangular que la engloba, encerrando los contenidos de ese elemento así como en el siguiente Ejemplo:
>
>Ejemplo Etiqueta html|
>----------------------|
>
>Entonces esta caja cuenta con propiedades que son:
>- **Width:** Ancho total de la caja.
>- **Height:** Altura total de la caja
>- **Padding:** Relleno que hay entre el contenido y el bloque.
>- **Border:** Grosor y estilo del borde que rodea el contenido(Dentro de la caja).
>- **Margin:** Espacio del borde interior y exterior del elemento(lo que está fuera de la caja).
>
>![caja-ejemplo](https://miro.medium.com/max/2560/1*nmdxvJbL2GI5NQSXCLOskA.png)
>
>
>Las propiedades Width y Height están definidas de forma predeterminada, para tener el tamaño del contenido, sin embargo mediante el código CSS se puede modificar a como se necesite.
>
>Un ejemplo podría ser:
>
>     <div>hello</div>
>     div {
>        width: 100px;
>        height: 100px;
>        border: 1px solid black;
>      }
>Lo cuál resultaría en lo siguiente:
>
>![imagen2](https://miro.medium.com/max/316/1*KImDGj3FBRbJTP4X3An3Qw.png)
>
>Sin embargo hay muchas más opciones para personalizar las propiedades antes comentadas, utilizando pixeles **(px)**, colores **(por código rgb, Hex y Hsl)**, porcentajes, entre otras más dependiendo de la misma propiedad.
>
>##### Ejemplo Border:
>
>     border-width: 4px;
>     border-style: solid;
>     border-color: rgb(0,0,255)
>     
>##### Ejemplo Paddng:
>     padding: 16px 21px 14px 19px;
>Los px mostrados en el anterior ejemplo, son los espacios de separación que habrá dentro de la caja de la etiqueta y estos van en orden de las manecillas del reloj, siendo el primero de la parte superior, el segundo de la parte derecha, el tercero de la parte inferior y el cuarto de el lado izquierdo.
>
>![padd](https://miro.medium.com/max/572/1*ya9KlObzE3uykfm7f06hzw.png)
>##### Ejemplo Margin:
>     margin : 20px;
>En el código anterior muestra que 20 pixeles será la separación por fuera de la cajita.
![margin-ejemplo](https://miro.medium.com/max/548/1*Uoukvh_d6XHleDheDW8u0g.png)
>
>Sin embargo, se puede especificar a donde queremos poner esos 20 pixeles de separación con las siguientes propiedades individualmente:
>
>       margin-top: Parte superior.
>      margin-right: Lado derecho.
>      margin-bottom: Parte inferior.
>      margin-left: Lado izquierdo.

información recopilada de [MUKTEK](http://blog.muktek.com)
