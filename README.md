# 📘 Proyecto: Mantenimiento Predictivo con HMM

Este proyecto implementa un modelo de **Mantenimiento Predictivo** utilizando **Modelos Ocultos de Markov (HMM)**.  
El código está diseñado como un **cuaderno de Google Colab**, lo que permite ejecutar simulaciones, visualizar dashboards y analizar métricas de confiabilidad y costos de manera interactiva.

---

## 🚀 Objetivo
El objetivo principal es simular el comportamiento de una máquina bajo diferentes estados de operación:
- **Estado Normal**
- **Estado de Desgaste**
- **Estado de Falla**

y evaluar métricas clave como:
- **RUL (Remaining Useful Life)** → Tiempo de vida útil restante.  
- **MTBF (Mean Time Between Failures)** → Tiempo medio entre fallas.  
- **Costo de inacción** → Impacto económico de no realizar mantenimiento.  
- **Distribución de estados** → Porcentaje de tiempo en cada estado.

---

## 🛠️ Funcionalidades principales
- **Simulación de máquinas individuales** con secuencia de estados y vibraciones.  
- **Dashboard visual** con evolución de vibraciones y estados.  
- **Análisis de convergencia** para validar estabilidad de métricas en múltiples simulaciones.  
- **Dashboard unificado** que muestra el comportamiento promedio de varias máquinas.  
- **Resumen numérico** con promedios y desviaciones estándar de RUL, MTBF y costos.

---

## 📊 Gráficas generadas
- Evolución del **RUL** con promedio y desviación estándar.  
- Distribución de estados en múltiples simulaciones.  
- Convergencia del **MTBF** y del **costo de inacción**.  
- Dashboard unificado de vibraciones promedio y estados finales.

---

## 📂 Uso en Google Colab
1. Sube el archivo `.ipynb` o copia el código en un cuaderno de Colab.  
2. Asegúrate de tener instaladas las librerías necesarias:
   ```python
   import numpy as np
   import matplotlib.pyplot as plt

