# 👻 Activity 3 - Pacman Game

Este repositorio contiene una versión modificada del juego clásico Pacman, tomado del paquete `freegames` de Grant Jenks. Como parte de la actividad del curso, se realizaron modificaciones al código original para agregar tres nuevas funcionalidades, cumpliendo con el rol de Owner y Fork.

## 📁 Contenido del repositorio

- `pacman.py` — Código fuente del juego con las modificaciones implementadas
- `README.md` — Documentación del proyecto

## 🛠️ Modificaciones realizadas

### Commit 1: Código original
Se incluyó la versión original del juego Pacman del paquete freegames como punto de partida del proyecto.

### Commit 2: Fantasmas más inteligentes (Rol Owner)
Se modificó la lógica de movimiento de los fantasmas para que en lugar de elegir una dirección aleatoria al chocar con una pared, calculen cuál de las opciones válidas los acerca más a Pacman. Esto se logró usando la función `min()` con una expresión lambda que mide la distancia entre cada opción y la posición de Pacman.

### Commit 3: Fantasmas más rápidos (Rol Fork)
Se duplicó la velocidad de los fantasmas cambiando los vectores de movimiento de magnitud 5 a magnitud 10 dentro de la función `move()`. Ahora los fantasmas se desplazan al doble de velocidad por cada iteración del juego.

### Commit 4: Tablero modificado (Rol Fork)
Se modificó la lista `tiles` que define el laberinto del juego, abriendo nuevos pasillos en filas intermedias que originalmente eran paredes cerradas. Esto cambia la estructura del laberinto y la jugabilidad.

## 🎮 Cómo ejecutar el juego

Requiere Python 3 y el paquete `freegames`:

## ⌨️ Controles

- ⬆️ **Flecha arriba** — mover hacia arriba
- ⬇️ **Flecha abajo** — mover hacia abajo
- ⬅️ **Flecha izquierda** — mover hacia la izquierda
- ➡️ **Flecha derecha** — mover hacia la derecha

## 👤 Autor

**Emmanuel Maximiliano Arozqueta Macias**
Matrícula: A01277760
Tecnológico de Monterrey

