# Informe de Notas - Sprauten, Sina

Hola Sina,

A continuación se detallan las notas obtenidas en los distintos componentes del curso.

## Resumen de Calificaciones

| Componente | Nota |
|---|---|
| Ejercicios (Media) | 9.2 |
| Participación | - |
| Proyecto Final | 8.7 |
| **NOTA FINAL CURSO** | **9.0** |

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
| Ejercicio 7.1 | 7.0 | No interpreta los resultados de las métricas en los apartados b y c |
| Ejercicio 7.2 | 10.0 |  |

## Evaluación del Proyecto Final

**Nota Oficial del Proyecto:** 8.7

A continuación se muestran los comentarios detallados de la evaluación:

---

### Identificacion
- **DNI/ID:** CCC630147
- **Nombre:** Sina Sprauten

### Evaluacion por Criterios

| Criterio | Puntuacion | Maximo |
|----------|------------|--------|
| 1. Objetivo y Contexto | 0.9 | 1.0 |
| 2. Datos: Extraccion, Fuentes y Documentacion | 0.8 | 1.0 |
| 3. Limpieza de Datos | 1.3 | 1.5 |
| 4. Transformacion e Integracion | 0.9 | 1.0 |
| 5. Analisis Exploratorio (EDA) | 1.7 | 2.0 |
| 6. Modelizacion | 1.8 | 2.0 |
| 7. Comunicacion y Conclusiones | 1.3 | 1.5 |

**SUMA CRITERIOS:** 8.7 / 10

### Penalizaciones Aplicadas
- Ninguna penalizacion significativa. El trabajo muestra comprension genuina y voz propia.

### NOTA FINAL: 8.7 / 10

### Comentarios Justificativos

**Puntos Fuertes:**

1. **Objetivo excelente (0.9/1.0):** Define claramente el problema de clasificacion de clientes high-value (top 10%). Justifica la relevancia empresarial (marketing, segmentacion). Reconoce explicitamente las limitaciones del contexto (datos de Black Friday vs comportamiento normal). Muestra pensamiento critico real.

2. **Limpieza exhaustiva (1.3/1.5):** Verifica inconsistencias de texto, whitespace, duplicados. Convierte variables a factores con justificacion clara. Detecta que `product_category_2` y `product_category_3` tienen NAs pero justifica por que no afectan su analisis. Verifica consistencia de datos demograficos por usuario antes de agregar.

3. **EDA con insights genuinos (1.7/2.0):** No se limita a describir graficos. Descubre que los high-value customers tienen mas transacciones pero NO cestas mas grandes (insight no obvio). Analiza el "average basket" para distinguir entre compradores frecuentes vs compradores de grandes cantidades. Investiga por que City C tiene menos high-value customers (descarta que sea por composicion demografica). El 10% de clientes genera 36.1% de ingresos - conexion directa con objetivo empresarial.

4. **Modelizacion completa (1.8/2.0):** Compara tres modelos (LASSO, Decision Tree, Random Forest). Reconoce el problema del threshold 0.5 con datos desbalanceados y propone soluciones (top 10% cutoff, Youden's index). Evalua modelos con y sin `n_transactions` para escenarios realistas. Discute trade-offs de cada threshold segun el objetivo empresarial. Variable importance coherente con EDA.

5. **Comunicacion clara (1.3/1.5):** Conclusiones conectadas con el objetivo empresarial. Reconoce limitaciones (datos solo de Black Friday, demograficos insuficientes). Proporciona recomendaciones practicas diferenciadas segun disponibilidad de datos.

**Puntos Debiles:**

1. **Datos (0.8/1.0):** Menciona que es un dataset de hackathon anonimizado, pero la documentacion de la fuente original es limitada. No hay enlace directo a la fuente original ni justificacion profunda de por que estos datos son adecuados para el objetivo.

2. **Algunas interpretaciones podrian ser mas profundas:** Por ejemplo, podria discutir mas las implicaciones economicas de los hallazgos sobre City C.

3. **EDA:** Aunque excelente, podria haber explorado interacciones entre variables categoricas de forma mas sistematica.

---
Puedes consultar la rúbrica de evaluación aplicada en el siguiente enlace: [RÚBRICA DE EVALUACIÓN](RUBRICA_EVALUACION.html)
