# Optimizacion
Analizar y optimizar el código proporcionado para mejorar su eficiencia en términos de tiempo y espacio.
## Explicación Paso a Paso

1. **Importación del módulo `random`:**
   - Utilizamos `import random` para importar el módulo `random`, que nos proporciona funciones para generar números aleatorios.

2. **Generación de la lista de números aleatorios:**
   - Utilizamos una lista de comprensión para generar una lista llamada `numbers` que contiene 1000 números enteros aleatorios entre 1 y 100.
   - `random.randint(1, 100)` genera un número aleatorio entre 1 y 100.
   - `for _ in range(1000)` itera 1000 veces para crear una lista con 1000 elementos.

3. **Impresión de la lista y cálculo del máximo y la suma:**
   - Usamos `print(numbers)` para mostrar la lista de números generada.
   - Utilizamos una tupla `(print(max(numbers)), print(sum(numbers)))` para agrupar las operaciones de calcular y mostrar el máximo y la suma de los números.
   - `max(numbers)` calcula el valor máximo en la lista de números.
   - `sum(numbers)` calcula la suma de todos los números en la lista.

---

