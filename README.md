# 🤖 Juego de IA: Gato vs. Ratón con Minimax

Este proyecto es una aplicación de consola en Python que implementa un juego de estrategia por turnos. El usuario (jugador "MAX") controla al Ratón (`R`) y la Inteligencia Artificial (jugador "MIN") controla al Gato (`G`).

El objetivo del Ratón es llegar al Queso (`Q`), mientras que el objetivo del Gato es atrapar al Ratón.

Este fue el primer challenge de la etapa "The Dive" del bootcamp CodePro, enfocado en fundamentos de Inteligencia Artificial.

---

## 🛠️ Conceptos Técnicos Implementados

Este proyecto no utiliza librerías externas de IA; el foco fue construir los algoritmos fundamentales desde cero.

* **Algoritmo Minimax:** Es el cerebro de la IA (Gato). Implementé el algoritmo Minimax de forma recursiva para explorar el "árbol" de posibles movimientos futuros.
* **Búsqueda con Profundidad Limitada:** Para evitar que la IA "piense" indefinidamente y asegurar una respuesta rápida, la recursión de Minimax está limitada a una `profundidad` predefinida.
* **Función Heurística:** Cuando la IA no puede ver el final del juego (debido al límite de profundidad), utiliza una función heurística para "puntuar" la ventaja de una posición. La heurística está basada en la **distancia de Manhattan** entre el gato, el ratón y el queso.
* **Lógica de Juego en 2D:** Todo el estado del juego se gestiona en una matriz (lista de listas) de Python, validando movimientos, colisiones y condiciones de victoria/derrota.

---

## 🚀 Cómo Ejecutarlo

1.  Clona este repositorio:
    ```bash
    git clone [Pega-la-URL-de-tu-repositorio-aquí]
    ```

2.  Navega al directorio del proyecto:
    ```bash
    cd [Nombre-de-tu-repositorio]
    ```

3.  Ejecuta el script de Python:
    ```bash
    python minimax_lab.py
    ```

4.  Sigue las instrucciones en la consola. Deberás usar las teclas `w` (arriba), `a` (izquierda), `s` (abajo) y `d` (derecha) para mover al ratón.
