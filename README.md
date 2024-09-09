# vue_desafio2
Desafío 2 para la materia 'Aplicaciones para Dispositivos Móviles'
# Te proponemos lo siguiente:

En este desafío te proponemos crear una interfaz que represente una lista de películas basada en las calificaciones que estas posean. Usarán una estructura de datos que contiene información sobre películas, como título, director, año de estreno, género, portada y calificación. Utilizar la directiva `v-for` para recorrer estos datos y mostrarlas en el HTML por medio de interpolaciones. Dependiendo del valor que posean las calificaciones, le agregaremos estilos visuales mediante clases CSS y se mostrarán ciertos textos mediante condicionales.

## Actividad a realizar:

#### 1. Estructura de datos a trabajar:
```js
peliculas: [
  {
    titulo: "Avatar: La leyenda de Aang",
    director: "Denis Villeneuve",
    estreno: 2024,
    genero: ["Fantasía ", "Ciencia ficción"],
    portada: "img/avatar.jpg",
    calificacion: 5
  },
  {
    titulo: "Dune 1",
    director: "Denis Villeneuve",
    estreno: 2023,
    genero: ["Ciencia ficción", "Aventura"],
    portada: "img/dune.jpg",
    calificacion: 8
  },
  {
    titulo: "Godzilla y Kong: El nuevo imperio",
    director: "Adam Wingard",
    estreno: 2024,
    genero: ["Acción", "Ciencia Ficción", "Kaiju"],
    portada: "img/godzilla.jpg",
    calificacion: 8
  },
  {
    titulo: "Cazafantasmas: Imperio helado",
    director: "Gil Kenan",
    estreno: 2024,
    genero: ["Aventura", "Comedia", "Fantasía"],
    portada: "img/cazafantasmas.jpg",
    calificacion: "-"
  },
  {
    titulo: "Shogun",
    director: "James Clavell",
    estreno: 2024,
    genero: ["Aventura", "Drama", "Historia"],
    portada: "img/shogun.jpg",
    calificacion: 6
  }
]
```
#### 2.Implementa la función `data` en la instancia principal de Vue:

Con base en la estructura de datos anterior, deberán implementar la función `data` en la instancia principal de Vue. Esta función debe contener los datos proporcionados y, posteriormente, deben montar la instancia en un contenedor específico dentro del HTML.

#### 3. Revisa el código adjunto:

En la carpeta adjunta al desafío tienen el código HTML necesario para lograr la representación final del ejercicio, el código CSS y las imágenes.

#### 4.Implementa las clases de calificación:

Tener presente que las calificaciones mayores o iguales a 7 deben tener la clase `.calificacion`. Las calificaciones menores o iguales a 6 deben tener la clase `.calificacion_mala`. Estas clases mostrarán la estrella amarilla y la estrella vacía respectivamente. Usarán la directiva `v-bind` con operador ternario. Esto se aplica en el párrafo que se encuentra debajo de la imagen en el documento HTML y posee una interpolación para mostrar el número de la calificación.

#### 5.Evalúa los textos a mostrar según la calificación:

Los párrafos siguientes evaluarán el texto a mostrar en base a su calificación. Si la calificación del ítem es mayor o igual a 7, el texto a mostrar será “Recomendada”. Si la calificación es menor o igual a 6, el texto a mostrar será “Baja calificación”. Si no aplica ninguna de las evaluaciones anteriores, el texto será “Sin Calificar”.

#### 6. Sigue los comentarios en el HTML:

Sigue los comentarios en el HTML para guiarte en el proceso. Analicen el resultado visual final del desafío.
