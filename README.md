# Busqueda_grafos_1

Este proyecto abarca los algoritmos de búsqueda no informados: a lo ancho, costo uniforme, a lo profundo, profundidad limitada, profundidad iterativa, y bidireccional.

Grafo

Se usará el grafo unidireccional contenido en el archivo "1erParcialGrafoUnidireccional.kmz". Para abrir el archivo kmz, se recomienda usar la página web de Google Earth: https://earth.google.com/web/@24.14771269,-101.93346641,1777.0598936a,3194509.63612531d,30.0011098y,0h,0t,0r

Una vez ahí, cargar el archivo en la página en la barra lateral/proyectos/nuevo proyecto/importar archivo kml del ordenador. Se recomienda quitar toda leyenda en barra latera/estilo del mapa/simplificado.

Las ciudades a utilizar están localizadas con un marcador; mientras que sus conexiones y sus pesos se encuentran en la linea recta (ruta) entre las ciudades. Al hacer click sobre cualquier línea de conexión/ruta, se despliega un cuadro de diálogo con el peso correspondiente.

El grafo será transformado en un grafo dirigido iniciando con la ciudad de Cancún con dirección hacia la izquierda del mapa.

Código

Las implementaciones de los algoritmos son propias; esto es, sin utilizar librerías para realizar la búsqueda. El código abarca lo siguiente:

Entrada:

Se pide al usuario los siguiente: nodo de inicio, nodo final, y límite de profundidad.
El código acepta y procesa el grafo de búsqueda anexado con pesos diferentes en cada acción y otra versión del mismo grafo con pesos iguales en cada acción.

Proceso interno:

El código estandariza los nombres de los nodos para ser procesados independientemente si se escriben en mayúsculas o minúsculas o una combinación de ambos.
El código verifica que el nodo de inicio y objetivo sean válidos.
El código primeramente ejecuta la búsqueda por anchura y determina si los pesos en todas las acciones del árbol de búsqueda son iguales o no. Si los pesos son iguales, entonces imprime en pantalla como resultado el camino del nodo inicio al nodo final junto con el tiempo de ejecución del algoritmo (pared o procesador) y finaliza la ejecución.
Si los pesos de las acciones en el árbol de búsqueda son diferentes, entonces ejecuta los siguientes algoritmos de búsqueda, en cualquier orden: Costo uniforme, profundidad, profundidad limitada, profundidad iterativa y bidireccional (con un algoritmo de búsqueda no informado de elección del equipo).
Una vez finalizada la ejecución de todos los algoritmos; los tiempos de ejecución de cada búsqueda son comparados y se identifica aquella búsqueda con el menor tiempo

Salida:

El código muestra en pantalla el grafo procesado/árbol de búsqueda.
El resultado de la búsqueda; en forma de camino o de mensaje de error.
El costo del camino recorrido; de ser pertinente.
El nivel de profundidad en la que se encontró la respuesta/camino o en la que se detuvo la búsqueda; de ser pertinente.
El tiempo total de ejecución de cada algoritmo de búsqueda.
La búsqueda con el menor tiempo de ejecución.

