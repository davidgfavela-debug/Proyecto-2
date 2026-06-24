# Análisis de Ventas Walmart (Resumen Ejecutivo)

## Descripción
En este proyecto se analizan las ventas por departamento de tiendas Walmart con el objetivo de evaluar el desempeño comercial y generar métricas clave que apoyen la toma de decisiones.

El análisis permite entender cuánto vende cada tienda en relación con su tamaño, así como la participación de cada departamento dentro del total de ventas.

---

## Estructura del Proyecto

El archivo está organizado en diferentes hojas:

- **raw_ventas**: Datos originales de ventas semanales por tienda y departamento  
- **raw_departamento**: Catálogo de departamentos con sus nombres  
- **raw_tiendas**: Información de tiendas (tipo y tamaño en m²)  
- **clean_ventas**: Datos limpios y estandarizados  
- **Pivot**: Tablas dinámicas para análisis  
- **Dashboard**: Visualización de KPIs  
- **Resumen**: Síntesis del análisis realizado  

---

## KPIs Principales

- **Ventas por m²**  
  Permite medir la eficiencia de cada tienda considerando su tamaño  

- **Porcentaje de participación**  
  Mide la contribución de cada departamento al total de ventas  

---

## Metodología

- Limpieza y estandarización de datos  
- Integración de múltiples tablas (ventas, tiendas, departamentos)  
- Creación de métricas calculadas  
- Uso de tablas dinámicas para análisis  
- Generación de dashboard para visualización  

---

## Validaciones (QA)

Se realizaron controles de calidad para asegurar la confiabilidad de los datos:

- Verificación de tiendas sin departamento asignado  
- Detección de ventas negativas o nulas  
- Validación de tamaños de tienda (valores > 0)  

---

## Hallazgos

- Diferencias claras en eficiencia entre tiendas según su tamaño  
- Algunos departamentos concentran mayor porcentaje de ventas  
- Se identificaron inconsistencias menores en los datos originales  

---

## Herramientas

- Google Sheets / Excel  
- Tablas dinámicas  
- Funciones de validación y limpieza  

---

## Resultado

Se desarrolló un modelo estructurado que permite:

- Analizar el rendimiento de ventas por tienda  
- Comparar eficiencia mediante métricas estandarizadas  
- Visualizar información clave mediante dashboards  

