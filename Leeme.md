Fundamentos del RWD:

1.- Tener en cuenta el "ViewPort (VP)": Es una "meta-etiqueta" que se coloca dentro del head del documento HTML. Es el espacio disponible en donde se mostrará la web.
    <meta name='viewport' content='width=device-width, user-scalable=no, initial-scale=1, maximum-scale=1' />

2.- Tener en cuenta las "Media Queries (MQ)" o "BreakPoints": Son una especie de condicionales en CSS, es como utilizar las condicionales "if" de Programación.
    Consejos:
        a. Comenzar primeramente con las características para medidas pequeñas.

3.- Tener en cuenta el "Modelo de caja": Una caja posee las caracteristicas de margen, borde, padding y su contenido.

4.- Tener en cuenta las "Unidades de Medidas relativas (%, rem, em)":

    * rem: El tamaño que adopta o adquiere es igual al tamaño de fuente del documento.
    * em: El tamaño que adopta o adquiere es dependiente o relativa al tamaño que posea el contenedor padre, no es relativa al contenedor sino al padre.

5.- Tener en cuenta las imagenes y sus tamaños: Lo ideal es mostrar una imagen diferente según el tamaño de pantalla. A diferente me refiero a su peso y tamaño.

6.- High Density Pixel: Es muy recomendable en RWD usar imagenes con el doble de tamaño pensado y solamente escalarlas con CSS a la mitad.
    P.e: Usar un icono que quieres que sus medidas sean 100x100, entonces, en tamaño original hacerla de 200x200 y luego, con CSS, escalarla 100x100 - width 100px / height 100px. 