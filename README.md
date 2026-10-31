# Análisis de compromiso y satisfacción de empleados

## Descripción del proyecto

Dashboard desarrollado en **Power BI** para analizar el compromiso laboral, la satisfacción de los empleados, el equilibrio entre trabajo y vida personal y las métricas de rendimiento de quienes dejaron la empresa.

El proyecto permite explorar los indicadores generales y analizar los resultados por departamento, período y estado del empleado mediante visualizaciones y filtros interactivos.

## Preguntas de análisis

1. ¿Cuál es el nivel general de compromiso laboral y satisfacción de los empleados?
2. ¿Qué departamentos presentan indicadores por debajo del promedio general de la empresa?
3. ¿Cómo evolucionó el equilibrio entre trabajo y vida personal durante el período analizado?
4. ¿Cuántos empleados dejaron la empresa y cómo se distribuyen sus evaluaciones de rendimiento?

## Principales conclusiones

### 1. Compromiso laboral y satisfacción general

En la vista general del dashboard, sin filtros aplicados, el promedio de compromiso laboral (*Average Engagement*) es del **59 %**, mientras que el promedio de satisfacción (*Average Satisfaction*) alcanza el **60 %**.

Estos indicadores permiten conocer el nivel general de compromiso y satisfacción de los empleados de la empresa.

### 2. Departamentos por debajo del promedio general

Los gráficos de barras permiten comparar los indicadores de cada departamento con el promedio general de la empresa, representado mediante una línea de referencia.

En la vista general, sin filtros de estado aplicados:

- **Compromiso laboral:** Production se encuentra por debajo del promedio general, con un **58 %**.
- **Satisfacción:** Admin Offices se encuentra por debajo del promedio general, con un **50 %**.

### 3. Equilibrio entre trabajo y vida personal

La cantidad de respuestas se mantuvo relativamente estable durante la mayor parte del período, con un mínimo de **212** y un máximo de **273 respuestas mensuales**.

El promedio del indicador de equilibrio entre trabajo y vida personal osciló entre el **57 %**, registrado en diciembre de 2022, y el **63 %**, alcanzado en mayo de 2023. Diciembre fue el mes con el menor promedio y mayo presentó el valor más alto del período analizado.

### 4. Empleados que dejaron la empresa y métricas de rendimiento

Al seleccionar los estados *Terminated for Cause* y *Voluntarily Terminated* en el filtro `EmployeeStatus`, se identifican **387 empleados**.

En esta vista filtrada, el promedio de compromiso laboral del grupo es del **58 %** y el promedio de satisfacción es del **62 %**. En comparación con los valores generales de la empresa —59 % de compromiso y 60 % de satisfacción—, el grupo presenta un compromiso ligeramente inferior y una satisfacción superior al promedio general.

El gráfico de anillos muestra la distribución de las categorías de evaluación de desempeño (*Performance Score*) de los empleados seleccionados.

## Herramientas y funcionalidades

- **Power BI:** creación del dashboard y visualización de indicadores.
- **Filtros interactivos:** exploración de resultados por estado del empleado.
- **Gráficos de barras con líneas de referencia:** comparación de departamentos con los promedios generales.
- **Gráfico de líneas:** análisis mensual del equilibrio entre trabajo y vida personal.
- **Gráfico de anillos:** distribución de las evaluaciones de desempeño.

## Nota sobre la interpretación

Los indicadores cambian según los filtros aplicados. Las conclusiones generales se obtuvieron con el dashboard sin filtros de estado; el análisis de empleados que dejaron la empresa corresponde a la vista filtrada por los dos estados indicados.

---

Proyecto realizado como parte de mi formación en **Análisis de Datos**.
