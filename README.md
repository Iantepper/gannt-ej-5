# gannt-ej-5

| Nombre                                                  | Duración | Inicio         | Terminado       | Predecesores |
|---------------------------------------------------------|----------|----------------|------------------|--------------|
| A- Determinar pantallas e informes del prototipo general | 2 days   | 04/11/2024 08:00 | 05/11/2024 17:00 | Ninguno      |
| B- Determinar contenidos de informes y pantallas        | 4 days   | 06/11/2024 08:00 | 11/11/2024 17:00 | A            |
| C- Crear prototipos de los informes                     | 3 days   | 12/11/2024 08:00 | 14/11/2024 17:00 | B            |
| D- Crear prototipos de las pantallas                   | 4 days   | 12/11/2024 08:00 | 17/11/2024 17:00 | B            |
| E- Obtener retroalimentación de los prototipos de los informes | 1 day   | 18/11/2024 08:00 | 18/11/2024 17:00 | C            |
| F- Obtener retroalimentación de los prototipos de las pantallas   | 2 days   | 19/11/2024 08:00 | 20/11/2024 17:00 | D            |
| G- Modificar los prototipos de los informes             | 2 days   | 21/11/2024 08:00 | 22/11/2024 17:00 | E            |
| H- Modificar los prototipos de las pantallas           | 4 days   | 23/11/2024 08:00 | 28/11/2024 17:00 | F            |
| I- Obtener la aprobación final                          | 2 days   | 29/11/2024 08:00 | 30/11/2024 17:00 | G;H          |




```mermaid
gantt
    title Proyecto de Desarrollo
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m/%Y
    section Planificación
    A. Dibujar el flujo de datos       :task1, 2024-01-01, 35d
    B. Dibujar árbol de decisiones     :task2, after task1, 28d
    C. Organizar diccionario de datos  :task5, after task1, 49d
    D. Realizar prototipo de salida    :task6, 2024-01-01, 14d
    E. Escribir casos de uso           :task8, 2024-01-01, 70d
    section Revisión y Modificación
    F. Revisar árbol                   :task3, after task2, 70d
    G. Escribir proyecto               :task4, after task3, 28d
    H. Realizar diseño de salida       :task7, after task6, 63d
    I. Diseñar base de datos           :task9, after task5, after task7, after task8, 56d







