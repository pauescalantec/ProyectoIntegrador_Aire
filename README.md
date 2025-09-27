# ProyectoIntegrador_Aire: Visualización Inteligente de la Calidad del Aire con AI y AR
Proyecto de materia de proyecto integrador para maestría MNA, Equipo 56

**Proyecto Integrador | Maestría en Inteligencia Artificial Aplicada**  
**Tecnológico de Monterrey – Grupo 10**  
**Autora:** Paulina Escalante Campbell – A01191962  
**Empresa colaboradora:** Okie Dokie Technologies  

---

## Descripción del Proyecto

**Aire** es una aplicación móvil educativa que combina inteligencia artificial (IA), aprendizaje automático (ML), sensores IoT y realidad aumentada (AR) para visualizar la calidad del aire en tiempo real y de manera predictiva, fomentando la conciencia ambiental y la toma de decisiones informadas en contextos urbanos.

Este repositorio contiene el desarrollo técnico de los modelos de IA y ML del proyecto, alineado con la metodología **CRISP-ML(Q)**. Aquí se incluyen notebooks, experimentos, reportes y scripts que sustentan el sistema de predicción y análisis de datos ambientales.

---

## Objetivos Técnicos

- Implementar modelos supervisados de predicción de calidad del aire utilizando datos históricos y meteorológicos.
- Comparar distintos algoritmos (Regresión, Random Forest, LSTM) para evaluar su precisión y escalabilidad.
- Evaluar el desempeño por región utilizando métricas como MAE, RMSE y R².
- Preparar modelos listos para integración con una app móvil en AR (iOS/visionOS).
- Establecer una arquitectura reproducible de ciencia de datos con trazabilidad y control de versiones.

---

## Estructura del Repositorio
TBD


## Datasets utilizados

Se emplean datasets públicos para modelado y validación:

- [`fedesoriano/air-quality-data-set`](https://www.kaggle.com/datasets/fedesoriano/air-quality-data-set)
- [`waqi786/global-air-quality-dataset`](https://www.kaggle.com/datasets/waqi786/global-air-quality-dataset)
- [`mujtabamatin/air-quality-and-pollution-assessment`](https://www.kaggle.com/datasets/mujtabamatin/air-quality-and-pollution-assessment)

Además, se exploran APIs en tiempo real como:

- [World Air Quality Index API](https://aqicn.org/api/)
- [OpenAQ API](https://docs.openaq.org/)
- [Google Air Quality API](https://developers.google.com/maps/documentation/airquality/overview)

---

## ⚙️ Requisitos

Se recomienda el uso de Python 3.10+ y las siguientes librerías:

```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
tensorflow (opcional para LSTM)
jupyterlab
