###Algoritmo de búsqueda para grafos sin peso

El algoritmo de búsqueda de caminos cortos funciona  cortando la búsqueda en el momento que encuentra la conexión posible, y por definición matemática siempre acabará en el tiempo mas corto, es decir el camino menor.

Aun es ineficiente bajo ciertas circunstancias:

1.-Si queremos ir de un punto del grafo a otro punto que no está conectado de forma directa con el grafo, el algoritmo comprobará el grafo entero para intentar llegar al punto, lo cual es una pérdida de tiempo.

2.-La búsqueda se realiza de forma única, será mas eficiente si añado búsquedas en paralelo (como mínimo una).

To do list:
  -Aumentar la velocidad de búsqueda (x4)
  -Optimizar la búsqueda cuando se intenta ir de un Subgrafo N a un Subgrafo N+1
