# Análisis del modelo K-Means

### Descripción de los Datos
El dataset contiene información sobre 200 clientes, con las siguientes características:

- CustomerID: Un identificador único para cada cliente.
- Gender: El género del cliente (Male o Female).
- Age: La edad del cliente.
- Annual Income: El ingreso anual del cliente en miles de dólares.
- Spending Score (1-100): Una puntuación asignada por el centro comercial en función del comportamiento de gasto del cliente.

### Exploración de los Datos
- El dataset no tiene valores faltantes.
- La distribución de género muestra que hay 112 mujeres y 88 hombres.
- La edad de los clientes varía entre 18 y 70 años.
- El ingreso anual oscila entre 15k y 137k dólares.
- La puntuación de gasto varía entre 1 y 99.

### Clustering K-Means
El algoritmo K-Means se aplicó utilizando 3 clusters. Los resultados del clustering fueron evaluados con las siguientes métricas:

Silhouette Score: 0.467
Calinski-Harabasz Index: 151.34