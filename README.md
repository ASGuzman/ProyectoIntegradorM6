# Proyecto de Análisis de Atención en Salud - Identificación de Complicaciones Post Biopsia Prostática
## Planteamiento de la Problemática
Hemos sido designados como parte del equipo de ciencia de datos en una consultora de prestigio para abordar un proyecto crítico relacionado con la atención en salud en un importante hospital. La problemática central es comprender las características más relevantes de los pacientes que han experimentado complicaciones infecciosas después de someterse a una biopsia prostática. El objetivo es identificar patrones que puedan prever la necesidad de hospitalización.

## Definición de Casos
* Caso: Paciente sometido a biopsia prostática que, en un plazo máximo de 30 días, presenta fiebre, infección urinaria o sepsis, requiriendo manejo médico ambulatorio u hospitalizado para la resolución de la complicación.

* Control: Paciente sometido a biopsia prostática que no presenta complicaciones infecciosas en el período de 30 días posteriores al procedimiento.

## Contenido del Proyecto
El proyecto está organizado en tres etapas principales, cada una abordada en un notebook específico.

1. ETL (Extract, Transform, Load)
Nombre del Notebook: Proyecto_Integrador_ETL.ipynb
Descripción: Este notebook aborda el proceso de extracción, transformación y carga de datos. Incluye la preparación de los datos relacionados con Antecedentes del paciente, Morbilidad asociada al paciente, Antecedentes relacionados con la toma de la biopsia y Complicaciones infecciosas.
2. EDA (Análisis Exploratorio de Datos)
Nombre del Notebook: Proyecto_Integrador_EDA.ipynb
Descripción: Aquí, realizamos un Análisis Exploratorio de Datos para comprender la distribución, las relaciones y las características clave de los datos. Exploramos visualmente las variables y buscamos patrones que puedan informar nuestro modelo posterior.En este notebook tambien realizamos la codificacion de las variables elegidas para que posteriormente podamos implementar el modelo de Machine Learning
3. Modelo de Machine Learning
Nombre del Notebook: Proyecto_Integrador_3_Modelamiento.ipynb
Descripción: En este notebook, implementamos un modelo de Machine Learning para prever la hospitalización de pacientes después de una biopsia prostática. Utilizamos las variables seleccionadas durante el EDA para entrenar y evaluar el modelo.