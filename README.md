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
    title Proyecto de Generación de Informes - Weber Consultores
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m/%Y
    section Generación de Informes
    A- Determinar pantallas e informes del prototipo general :task1, 2024-11-04, 2d
    B- Determinar contenidos de informes y pantallas         :task2, after task1, 4d
    C- Crear prototipos de los informes                      :task3, after task2, 3d
    D- Crear prototipos de las pantallas                    :task4, after task2, 4d
    E- Obtener retroalimentación de los prototipos de los informes :task5, after task3, 1d
    F- Obtener retroalimentación de los prototipos de las pantallas   :task6, after task4, 2d
    G- Modificar los prototipos de los informes              :task7, after task5, 2d
    H- Modificar los prototipos de las pantallas            :task8, after task6, 4d
    I- Obtener la aprobación final                           :task9, after task7, 2d






