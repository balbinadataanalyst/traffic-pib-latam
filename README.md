# Proyectos de Análisis de Datos - Balbina

## 1. Análisis de Correlación: Tráfico vs PIB en LATAM
**Problema:** ¿Las ciudades con mayor PIB sufren más congestión?
**Fuente:** TomTom Traffic Index 2023, Banco Mundial
**Ciudades:** CDMX, Bogotá, Lima, Santiago, etc.

## 2. Proyecto 6 - ConnectaTel (NUEVO - Sprint 7)
**Objetivo:** Analizar y segmentar a los usuarios de ConnectaTel por edad y nivel de uso.

**Datasets:**
- user_profile con ~3800 usuarios
- Columnas: llamadas, mensajes, edad

**Etapas realizadas:**
1. Limpieza de datos: tratamiento de nulos y duplicados
2. EDA y detección de outliers en duración de llamadas
3. Creación de segmentos: grupo_uso (Bajo, Medio, Alto) y grupo_edad (Joven, Adulto, Adulto Mayor)
4. Visualización con countplot y boxplot
5. Insight ejecutivo

**Hallazgo Principal:**
El 78% de los usuarios son de Uso Medio y la mayoría son Adultos (30-59). La base es estable pero dependiente de un solo perfil. Recomendación: Crear plan Premium para migrar a Alto uso y plan Redes para captar jóvenes.

**Cómo ejecutar:**
- Abrir `S7 Version-Estudiante-Project-ConnectaTel.ipynb` en Google Colab
- Ejecutar todas las celdas

## Tecnologías
Python, Pandas, Seaborn, Matplotlib, GitHub
