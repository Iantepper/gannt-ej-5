# gannt-ej-5

| Nombre                                                  | Duración | Inicio         | Terminado       | Predecesores |
|---------------------------------------------------------|----------|----------------|------------------|--------------|
| A- Determinar pantallas e informes del prototipo general | 2 days   | 12/06/2024 08:00 | 13/06/2024 17:00 | Ninguno      |
| B- Determinar contenidos de informes y pantallas        | 4 days   | 14/06/2024 08:00 | 19/06/2024 17:00 | A            |
| C- Crear prototipos de los informes                     | 3 days   | 20/06/2024 08:00 | 24/06/2024 17:00 | B            |
| D- Crear prototipos de las pantallas                   | 4 days   | 20/06/2024 08:00 | 25/06/2024 17:00 | B            |
| E- Obtener retroalimentación de los prototipos de los informes | 1 day   | 26/06/2024 08:00 | 26/06/2024 17:00 | C            |
| F- Obtener retroalimentación de los prototipos de las pantallas   | 2 days   | 27/06/2024 08:00 | 28/06/2024 17:00 | D            |
| G- Modificar los prototipos de los informes             | 2 days   | 29/06/2024 08:00 | 30/06/2024 17:00 | E            |
| H- Modificar los prototipos de las pantallas           | 4 days   | 01/07/2024 08:00 | 04/07/2024 17:00 | F            |
| I- Obtener la aprobación final                          | 2 days   | 05/07/2024 08:00 | 06/07/2024 17:00 | G;H          |

```mermaid
gantt
    title Proyecto de Generación de Informes - Weber Consultores
    dateFormat  DD/MM/YYYY
    axisFormat  %d/%m/%Y
    section Generación de Informes
    A- Determinar pantallas e informes del prototipo general    :a1, 12/06/2024, 2d
    B- Determinar contenidos de informes y pantallas           :after a1, 4d
    C- Crear prototipos de los informes                          :after a1, 3d
    D- Crear prototipos de las pantallas                        :after a1, 4d
    E- Obtener retroalimentación de los prototipos de los informes :after C, 1d
    F- Obtener retroalimentación de los prototipos de las pantallas   :after D, 2d
    G- Modificar los prototipos de los informes                  :after E, 2d
    H- Modificar los prototipos de las pantallas                :after F, 4d
    I- Obtener la aprobación final                               :after G, 2d

