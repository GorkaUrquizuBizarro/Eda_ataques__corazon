# Eda_ataques__corazon

## Contexto

Las enfermedades cardiovasculares representan una de las principales causas de morbilidad y mortalidad a nivel mundial. Entre ellas, el infarto agudo de miocardio y otros tipos de ataques al corazón son especialmente críticos debido a su alta prevalencia y al impacto que generan tanto en la calidad de vida de los pacientes como en los sistemas de salud.

En el ámbito del análisis de datos, existen numerosos conjuntos de datos clínicos que recogen información biométrica, hábitos de vida, parámetros médicos y antecedentes de salud. Estos datos permiten realizar estudios exploratorios que ayuden a comprender mejor los factores que influyen en la aparición de eventos cardíacos.

Este proyecto se enmarca dentro de esa necesidad: analizar datos relacionados con ataques al corazón mediante técnicas de Exploratory Data Analysis (EDA).

## Problema actual

A pesar del volumen de datos disponibles sobre la salud cardíaca, muchas veces estos:

No han sido explorados adecuadamente.

Contienen información ruidosa, incompleta o desbalanceada.

No están acompañados de análisis visuales que faciliten la comprensión.

Son subutilizados para identificar patrones, correlaciones o factores de riesgo relevantes.

Esta falta de análisis dificulta la toma de decisiones informada tanto para investigadores como para profesionales sanitarios. Además, la ausencia de una exploración sistemática limita la capacidad para detectar relaciones clave que podrían influir en el diseño de modelos predictivos o estrategias de prevención.

## Objetivo principal del proyecto

El objetivo principal de este proyecto es realizar un Análisis Exploratorio de Datos (EDA) sobre un dataset de ataques al corazón con el fin de:

Comprender la estructura y calidad del conjunto de datos.

Identificar patrones, tendencias y relaciones entre variables clínicas.

Detectar posibles factores que puedan influir en el riesgo de sufrir un ataque cardíaco.

Generar visualizaciones que permitan interpretar la información de manera intuitiva.

Proporcionar una base sólida para futuros análisis predictivos o estudios más avanzados.

En resumen, el proyecto busca transformar un conjunto de datos clínicos en conocimiento útil mediante métodos estadísticos y visuales.

## Estructura del repo

```bash
|--- Datos
    |---synthetic_heart_disease_dataset.csv #datos originales
```

## Información de las columnas del conjunto de datos

📘 Diccionario de Datos (Data Dictionary)

A continuación se describen las columnas del conjunto de datos utilizado para el análisis de factores asociados a los ataques cardíacos:

| **Columna**                     | **Descripción**                                                                    |
| ------------------------------- | ---------------------------------------------------------------------------------- |
| **Edad**                        | Edad del paciente en años.                                                         |
| **Id**                          | Identificador único asignado a cada registro.                                      |
| **Genero**                      | Sexo del paciente (Masculino / Femenino).                                          |
| **Peso**                        | Peso corporal en kilogramos.                                                       |
| **Altura**                      | Altura del paciente en centímetros.                                                |
| **IMC**                         | Índice de Masa Corporal (calculado a partir del peso y la altura).                 |
| **Fumador**                     | Hábito de consumo de tabaco (Nunca / Ocasional / Regular).                         |
| **Alcohol**                     | Nivel de consumo de alcohol (Ninguno / Bajo / Moderado / Alto).                    |
| **Actividad_física**            | Nivel general de actividad física del paciente (Sedentario / Moderado / Activo).   |
| **Diesta** *(Dieta)*            | Calidad de la dieta (Saludable / Promedio / No saludable).                         |
| **Nivel_Stress**                | Nivel de estrés percibido (Bajo / Medio / Alto).                                   |
| **Hypertension**                | Indica si el paciente presenta hipertensión (Sí / No).                             |
| **Diabetes**                    | Indica si el paciente padece diabetes (Sí / No).                                   |
| **Hyperlipidemia**              | Presencia de niveles elevados de lípidos en sangre (Sí / No).                      |
| **Historial_familiar**          | Presencia de antecedentes familiares de enfermedades cardíacas.                    |
| **Antecedentes_ataque_corazon** | Indica si el paciente ha sufrido previamente un ataque cardíaco.                   |
| **Systolic_BP**                 | Presión arterial sistólica (mmHg).                                                 |
| **Diastolic_BP**                | Presión arterial diastólica (mmHg).                                                |
| **Pulsaciones**                 | Frecuencia cardíaca (latidos por minuto).                                          |
| **Azucar_sangre**               | Nivel de glucosa en sangre.                                                        |
| **Colesterol**                  | Nivel total de colesterol en sangre.                                               |
| **Ataque_corazón**              | Variable objetivo que indica si el paciente presenta un ataque cardíaco (Sí / No). |




## Recap proyecto


### Día 1 de proyecto
- Creación de repositorio
- Generación de archivo Readme y sistema de carpetas
- Lectura de datos del archivo excel con los datos del proyecto a analizar.
- Añadir conjunto de datos original "synthetic_heart_disease_dataset.csv"

