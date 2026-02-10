# Informe de Notas - Chinaeva, Varvara

Hola Varvara,

A continuación se detallan las notas obtenidas en los distintos componentes del curso.

## Resumen de Calificaciones

| Componente | Nota |
|---|---|
| Ejercicios (Media) | 9.6 |
| Participación | - |
| Proyecto Final | 6.6 |
| **NOTA FINAL CURSO** | **8.1** |

> **Cálculo de la Nota Final:**
> La nota final se calcula como el máximo entre:
> - Opción A: 50% Ejercicios + 50% Proyecto Final
> - Opción B: 35% Ejercicios + 15% Participación + 50% Proyecto Final

## Detalle de Ejercicios

La nota de ejercicios corresponde a la media de todos los ejercicios propuestos durante el curso.

### Detalle de Ejercicios

| Ejercicio | Nota | Comentarios |
|---|---|---|
| Ejercicio 1 | 10.0 |  |
| Ejercicio 2 | 10.0 |  |
| Ejercicio 3 | 10.0 |  |
| Ejercicio 4.1 | 10.0 |  |
| Ejercicio 4.2 | 10.0 |  |
| Ejercicio 5 | 6.0 | No obtiene el intervalo en el ejercicio 1 y código mejorable en el ejercicio 2 |
| Ejercicio 7.1 | 10.0 |  |
| Ejercicio 7.2 | 10.0 |  |

## Evaluación del Proyecto Final

**Nota Oficial del Proyecto:** 6.6

A continuación se muestran los comentarios detallados de la evaluación:

---

### Notas por criterio:

| Criterio | Nota | Comentario |
|----------|------|------------|
| **Objetivo y Contexto** | 0.8/1.0 | Objetivo bien definido (prediccion de precios de vivienda en Ames, Iowa). Contexto economico/empresarial adecuado (valoracion para agentes, bancos, compradores). No es especialmente original ya que es un dataset clasico de ML. |
| **Datos** | 0.7/1.0 | Fuente documentada con enlace a Dropbox. Descripcion correcta de las 81 variables. Sin embargo, no hay justificacion profunda de por que este dataset es adecuado mas alla de lo obvio. |
| **Limpieza** | 1.0/1.5 | Limpieza basica correcta: conversion a factores, eliminacion de ID. Identifica los NA pero decide no tratarlos en esta fase (justificado para modelos). La justificacion de las decisiones es aceptable pero no exhaustiva. |
| **Transformacion** | 0.7/1.0 | Transformacion logaritmica del precio justificada por asimetria. Creacion de variable logSalePrice. Sin embargo, no hay transformaciones sofisticadas ni creacion de variables derivadas originales. |
| **EDA** | 1.3/2.0 | EDA completo con multiples visualizaciones: histogramas, scatter plots, boxplots, heatmap de correlaciones. Las interpretaciones son correctas pero algunas son un poco mecanicas ("se observa una clara relacion positiva..."). El analisis de Year Built con la caida en los 40s es un insight interesante. |
| **Modelizacion** | 1.5/2.0 | Buena comparacion de 4 modelos (LM, LASSO, arbol, Random Forest). Tuning con CV bien implementado. Seleccion final del RF bien justificada. Incluye variable importance. Falta comparacion mas profunda de interpretabilidad vs prediccion. |
| **Comunicacion** | 1.1/1.5 | Buena estructura del documento. Conclusiones conectadas con el objetivo. Incluye prediccion de casos concretos con error. Falta reconocimiento explicito de limitaciones. |

### Penalizaciones:
- El codigo usa rutas relativas ("data/housesIowa.csv") lo cual es correcto

### NOTA FINAL: 6.6/10

### Comentarios:
Trabajo solido y bien estructurado. Demuestra comprension de los conceptos de ML supervisado. El flujo de trabajo con tidymodels es correcto. Puntos fuertes: buena comparacion de modelos, uso correcto de CV, interpretacion de variable importance. Puntos debiles: analisis exploratorio algo mecanico en partes, falta de variables derivadas originales, declaracion de uso de IA para el apendice resta originalidad.

---
Puedes consultar la rúbrica de evaluación aplicada en el siguiente enlace: [RÚBRICA DE EVALUACIÓN](RUBRICA_EVALUACION.html)
