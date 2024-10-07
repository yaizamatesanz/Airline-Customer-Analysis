# Análisis del Comportamiento de Clientes de una Aerolínea ✈️📊

Bienvenido a este repositorio, donde encontrarás un análisis detallado sobre la actividad de los clientes de un programa de lealtad de una aerolínea. A lo largo del proyecto, exploré y visualicé datos sobre la cantidad de vuelos reservados, puntos acumulados y redimidos, así como información demográfica de los clientes.

## Estructura del Proyecto 🔍

### 1. Exploración y Limpieza de Datos 🧼

**Análisis Inicial:**  
En esta primera etapa, me enfoqué en revisar la calidad de los datos, identificando valores nulos, registros atípicos y posibles inconsistencias. Utilicé herramientas de Pandas para obtener una visión general del dataset, como la estructura y las estadísticas clave de las columnas.

**Limpieza:**  
Lidié con valores nulos y problemas de coherencia en los datos, asegurando que estuvieran listos para el análisis posterior. También realicé ajustes en los tipos de datos y uní las dos tablas usando el identificador único de clientes (`Loyalty Number`).

### 2. Visualización de Datos 📊

La visualización de datos es clave para responder preguntas críticas relacionadas con el comportamiento de los clientes. Las visualizaciones que realicé incluyen:

- **Vuelos Reservados por Mes:**  
  Analicé las reservas de vuelos mensuales para identificar picos y patrones estacionales en la actividad de los clientes.

- **Relación entre Distancia y Puntos:**  
  Exploré si existe una correlación entre la distancia recorrida y los puntos acumulados por los clientes en el programa de lealtad.

- **Distribución Geográfica de Clientes:**  
  Mapeé la ubicación de los clientes para ver la distribución por provincia/estado, identificando áreas con mayor número de clientes activos.

- **Comparación de Salarios según Nivel Educativo:**  
  Comparé el salario promedio de los clientes según su nivel educativo, observando posibles diferencias salariales.

- **Tipos de Tarjetas de Lealtad:**  
  Visualicé la proporción de clientes que tienen diferentes tipos de tarjetas de lealtad, lo cual indica cómo están segmentados los usuarios del programa.

- **Distribución según Estado Civil y Género:**  
  Analicé cómo se distribuyen los clientes de acuerdo con su estado civil y género para obtener insights demográficos.

### 3. Análisis de Diferencias en Reservas de Vuelos por Nivel Educativo 🎓

En esta sección, investigué si el nivel educativo de los clientes afecta la cantidad de vuelos que reservan.

1. **Preparación de Datos:**  
   Seleccioné las columnas clave 'Flights Booked' y 'Education' para realizar el análisis correspondiente.

2. **Análisis Descriptivo:**  
   Agrupé los datos por nivel educativo, calculando estadísticas como promedio, desviación estándar y percentiles para obtener una descripción completa de las reservas de vuelos por grupo educativo.

3. **Prueba de Hipótesis:**  
   Apliqué una prueba estadística A/B para evaluar si existen diferencias significativas en las reservas de vuelos entre los distintos niveles educativos.

## Archivos de Datos 📁

- **Customer Loyalty History.csv:**  
  Contiene datos demográficos y del perfil de lealtad de los clientes, como su ubicación, estado civil, nivel educativo y tipo de tarjeta.

- **Customer Flight Activity.csv:**  
  Registra la actividad de vuelo de los clientes, incluyendo vuelos reservados, puntos acumulados y redimidos, y otros aspectos relevantes de su comportamiento en el programa de lealtad.

---

### Conclusión 🚀

Este proyecto ofrece una visión integral sobre cómo los clientes interactúan con el programa de lealtad de la aerolínea, a través de la exploración, visualización y análisis de datos. ¡Espero que disfrutes de esta investigación!
