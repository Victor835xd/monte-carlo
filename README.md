# El método de Monte Carlo
El concepto de MonteCarlo radica en utilizar la aleatoriedad para resolver problemas complejos deterministicos.

Los pasos para aplicarlo son los siguientes:
1. Define un dominio de entradas
2. Genera entradas aleatorias del dominio de las entradas, usando una distribución de probabilidad
3. Realiza una computación deterministacia a las entradas
4. Junta los resultados


Toma en cuenta estas consideraciones:
1. Si las entradas no están uniformemente distribuidas, la aproximación al resultado puede ser incorrectos
2. Si hay pocas entradas, la variación sera muy grande y podrás tener resultados incorrectos

Elige el lenguaje de programación que desees para resolver las siguientes simulaciones. No te olvides de hacer commit y push para enviar tu código.

Nota: No realizes el "merge pull request", dejala abierta para poder recibir la retroalimentaicon.
## Pi
Imaginemos que en un plano de coordenadas tenemos un cuadrado con lado "a", y adentro de el un circulo con radio "a".

Genera una serie de puntos aleatorios dentro de ese cuadrado y calcula cuantos de ellos entran en el circulo y cuantos no.

Después divide el numero de puntos que entraron en el circulo entre el numero total de puntos generados.

Finalmente, multiplica tu resultado por 4.
## Juego
Se te presenta un juego el cual tiene una probabilidad de ganar de "p", es decir P(ganar) = p.
El juego termina cuando pierdas dos veces seguidas. Utiliza el método de MonteCarlo para determinar cual es el valor medio de partidas jugadas, dado para p = 1/2, 1/4 y 6/8.

## Monty Hall
Se te presenta otro juego. Esta vez el administrador del juego te da a elegir entre 3 posibles puertas. En ellas, una puerta esconde $1,000,000 de dolares, y las otras dos contiene una cabra.

Después de elegir tu puerta, el administrador abrirá una de las otras 2 puertas que no elegiste, siempre revelando una cabra. Utiliza el método de MonteCarlo para determinar si hay diferencias de probabilidad de ganar entre estas dos estrategias:
1. Stick to your guns: Te mantienes en la primera puerta que elegiste
2. Move: Descartas tu puerta inicial, y decides tomar la otra puerta restante.


## Conclusiones
Ademas de enviar tu código, anota tus análisis y resultados en un archivo llamado "conclusiones.md"