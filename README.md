# gannt-ej-5

| Nombre                                                  | Duración | Inicio         | Terminado       | Predecesores |
|---------------------------------------------------------|----------|----------------|------------------|--------------|
| A- Determinar pantallas e informes del prototipo general | 2 days   | 01/01/2024 08:00 | 02/01/2024 17:00 | Ninguno      |
| B- Determinar contenidos de informes y pantallas        | 4 days   | 03/01/2024 08:00 | 08/01/2024 17:00 | A            |
| C- Crear prototipos de los informes                     | 3 days   | 09/01/2024 08:00 | 11/01/2024 17:00 | B            |
| D- Crear prototipos de las pantallas                   | 4 days   | 09/01/2024 08:00 | 14/01/2024 17:00 | B            |
| E- Obtener retroalimentación de los prototipos de los informes | 1 day   | 15/01/2024 08:00 | 15/01/2024 17:00 | C            |
| F- Obtener retroalimentación de los prototipos de las pantallas   | 2 days   | 16/01/2024 08:00 | 17/01/2024 17:00 | D            |
| G- Modificar los prototipos de los informes             | 2 days   | 18/01/2024 08:00 | 19/01/2024 17:00 | E            |
| H- Modificar los prototipos de las pantallas           | 4 days   | 20/01/2024 08:00 | 25/01/2024 17:00 | F            |
| I- Obtener la aprobación final                          | 2 days   | 26/01/2024 08:00 | 27/01/2024 17:00 | G;H          |

```mermaid
gantt
    title Proyecto de Generación de Informes - Weber Consultores
    dateFormat  DD/MM/YYYY
    axisFormat  %d/%m/%Y
    section Generación de Informes
    A- Determinar pantallas e informes del prototipo general    :a1, 01/01/2024, 2d
    B- Determinar contenidos de informes y pantallas           :after a1, 4d
    C- Crear prototipos de los informes                          :after a1, 3d
    D- Crear prototipos de las pantallas                        :after a1, 4d
    E- Obtener retroalimentación de los prototipos de los informes :after C, 1d
    F- Obtener retroalimentación de los prototipos de las pantallas   :after D, 2d
    G- Modificar los prototipos de los informes                  :after E, 2d
    H- Modificar los prototipos de las pantallas                :after F, 4d
    I- Obtener la aprobación final                               :after G, 2d
