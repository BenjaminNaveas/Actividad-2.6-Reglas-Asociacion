# 🔬 Actividad 2.6 — Laboratorio: Implementación de Reglas de Asociación

**Asignatura:** IEI097 · Minería de Datos  
**Institución:** Instituto Profesional Santo Tomás - Sede Arica  
**Estudiante:** Benjamín Eduardo Naveas Molina  

## 📋 Descripción del Proyecto
Este repositorio contiene el desarrollo del laboratorio de Reglas de Asociación (Market Basket Analysis). El objetivo principal es extraer patrones de compra ocultos en un entorno de retail mediante el **algoritmo Apriori**. 

A través del procesamiento de un dataset transaccional con casi 15,000 registros, el notebook documenta todo el ciclo analítico:
1. Conexión automatizada mediante la API de Kaggle (`kagglehub`).
2. Limpieza y transformación de datos a una matriz binaria (One-Hot Encoding).
3. Generación de itemsets frecuentes.
4. Extracción y comparación de reglas de asociación utilizando diferentes métricas de evaluación (Soporte, Confianza y Lift).
5. Interpretación final de los resultados en lenguaje de negocio para la toma de decisiones estratégicas.

## 🛠️ Tecnologías Utilizadas
* **Entorno:** Google Colab
* **Lenguaje:** Python 3
* **Librerías principales:** `pandas`, `mlxtend` (para *TransactionEncoder*, *apriori* y *association_rules*), `kagglehub`.

## 📊 Dataset
Se utilizó el conjunto de datos público **Groceries Dataset** proporcionado por el autor *heeraldedhia* a través de Kaggle. Contiene el historial de compras de un supermercado, permitiendo analizar qué productos tienden a comprarse juntos de forma natural.

---
*Este proyecto fue desarrollado como parte de las evaluaciones formativas de la Unidad II de la asignatura Minería de Datos.*
