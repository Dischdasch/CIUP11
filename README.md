# CIUP11
Prototipo de procesamiento de imágenes con un [shader](https://github.com/processing/processing-docs/tree/master/content/examples/Topics/Shaders/Conway)
.
En este trabajo se ha realizado el procesamiento de imágenes con un shader.
Cualquier imagen que se guarde en la carpeta con el nombre image.jpg puede ser procesada con esta aplicación.

El sombreador funciona según el principio de [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), es decir, para cada píxel se determina el color en función del color de los píxeles adyacentes.
Este proceso se controla con el ratón.

Mientras experimentaba, se produjo un efecto interesante:
Si se combina el shader realizado con el control del ratón y cualquier imagen, la imagen parece aparecer poco a poco. Según las reglas del Juego de la Vida, la aparición de la imagen parece una tinta mágica que corre desde la punta del ratón hasta la forma de la imagen.

2022 Dascha Blehm
