# 🚀 Automated ETL Pipeline for Data Cleaning & Reporting

Este proyecto nace de una necesidad crítica en las áreas de analítica y operaciones: el tiempo que se pierde limpiando datos a mano antes de poder generar informes ejecutivos. 

Para resolver este cuello de botella, desarrollé de forma autónoma un **Pipeline ETL en Python** que automatiza la ingesta de datos crudos (estructuras complejas como JSON), realiza una limpieza rigurosa y exporta reportes visuales listos para la toma de decisiones.

## 🛠️ Arquitectura del Proyecto (4 Bloques)

El código fue diseñado bajo un enfoque **modular y reutilizable**, asegurando que el sistema sea escalable y fácil de adaptar si cambian las fuentes de datos o los servidores:

1. **Arranque:** Bloque encargado de la parametrización inicial, definición de rutas y preparación del entorno de ejecución.
2. **Materia Prima:** Ingesta y lectura automatizada de los datos crudos desde el servidor.
3. **Transformación:** Fase donde se ejecuta la lógica de negocio; limpieza de datos, tipado correcto y filtrado de anomalías empleando **Pandas**.
4. **Reporte:** Exportación y generación automatizada de reportes visuales ejecutivos.

## 📈 Impacto
* **Eficiencia Operativa:** Automatiza tareas repetitivas de manipulación de datos, ahorrando muchísimo tiempo en el procesamiento diario.
* **Mantenibilidad:** Al estar estructurado por bloques independientes, no es necesario reescribir el código desde cero para adaptarlo a nuevos formatos; basta con ajustar el bloque requerido.

## 🧰 Tecnologías Utilizadas
* **Python** 
* **Pandas** (Procesamiento y limpieza de datos)
* **JSON** (Manipulación de estructuras de datos crudas)
