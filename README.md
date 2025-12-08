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

### Día 2 de proyecto
- Se verifica la ausencia de duplicados
- Se tradujeron las categorias de las siguientes columnas: 

### Día 3 de proyecto
- Análisis de las columnas numéricas
- Análisis estadístico de las columnas númericas.

### Día 4 de proyecto
- Análisis de las columnas categóricas.
- Análisis estadistico de las columnas categóricas.

### Día 5 de proyecto
- Análisis multivariado.
-.Análisis de la correlación entre columnas para un correcto representación de las relaciones.

### Día 6 de proyecto.
- Desarrollo del dashboard del proyecto.

### Día 7 de proyecto.
- Realización de las conclusiones del proyecto en el Readme.

Conclusiones del proyecto:

Interpretación:

Las variables más relacionadas con enfermedad cardíaca son:

Hipertensión (0,4047)

Edad (0,380)

Colesterol total (0,374)

Diabetes (0,338)

Ataque cardíaco previo (0,243)

Variables como género, peso, IMC, fumar o dieta tienen correlaciones muy bajas, lo que indica que en este conjunto de datos no tienen una relación lineal fuerte con la enfermedad cardíaca.

3. Otras observaciones

La hipertensión se correlaciona poco con los hábitos de vida, pero mucho con la enfermedad cardíaca.

La edad es el factor demográfico más importante.

Diabetes, colesterol y antecedentes de ataque cardíaco son indicadores clínicos fuertes.

Algunas correlaciones bajas pueden deberse a limitaciones del dataset o efectos no lineales.

4. Uso práctico

Para predecir enfermedad cardíaca, se podrían priorizar estas variables:

Edad, Hipertensión, Diabetes, Colesterol y Ataque cardíaco previo

Variables como género, peso, IMC, dieta o estrés podrían tener menor peso en modelos lineales.

Tal vez se necesiten modelos no lineales para capturar relaciones más complejas.

## Conclusiones del Análisis de Correlación sobre Enfermedad Cardíaca

1. **Factores más relacionados con la enfermedad cardíaca**:

   * Hipertensión (0,40)
   * Edad (0,38)
   * Colesterol total (0,37)
   * Diabetes (0,34)
   * Antecedentes de ataque cardíaco previo (0,24)

   Estos resultados indican que las condiciones médicas y la edad son los principales indicadores de riesgo en el conjunto de datos analizado.

2. **Factores con baja correlación**:

   * Género, peso, altura, IMC, tabaquismo, consumo de alcohol, dieta, estrés y actividad física muestran correlaciones muy bajas con la enfermedad cardíaca (<0,01).
   * Esto sugiere que, en este dataset, los hábitos de vida y las características demográficas no explican directamente la presencia de enfermedad cardíaca de manera lineal.

3. **Implicaciones para modelado predictivo**:

   * Variables como hipertensión, edad, colesterol, diabetes y antecedentes de ataques cardíacos previos deberían priorizarse al construir modelos predictivos.
   * Variables con baja correlación podrían descartarse o tratarse con modelos no lineales que capturen relaciones más complejas.

4. **Limitaciones**:

   * La correlación solo mide relaciones lineales; factores importantes podrían tener efectos no lineales o interactuar entre sí.
   * Algunas correlaciones sorprendentemente bajas (como tabaquismo y enfermedad cardíaca) podrían deberse a limitaciones en la muestra o el tamaño del dataset.

En resumen, el análisis resalta la importancia de factores clínicos sobre los hábitos de vida en la predicción de enfermedad cardíaca dentro de este conjunto de datos.
