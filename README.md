# reto2
Reto 2 curso Desarrollo Frontend

El reto de curso de desarrollo frontend se compone de dos archivos:

+ notfound.html
+ styles.css

notfound.html: contiene la estructura html, donde cada bloque de la pagina se nombro con la metodologia BEM.

styles.css: contine los estilos css que estilizan la estructura html.

Animacion:

@keyframes latidos {
    from { transform: none; }
    50% { transform: scale(1.4); }
    to { transform: none; }
}

Posteriormente latidos se usa en:
.notfound__content--title {
      margin: 0px;
      font-size: 100px;
      color: white;
      animation: latidos .5s infinite;
  }

