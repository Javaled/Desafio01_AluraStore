# README - Sistema de Análisis de Ventas
## 📊 Descripción
Este script en Python proporciona un conjunto de herramientas para analizar métricas de ventas de múltiples tiendas, incluyendo:

**Ventas totales por tienda**

- Distribución de ventas por categoría
- Calificaciones promedio
- Productos más y menos vendidos
- Costos promedio de envío

## 🛠 Funcionalidades principales
**1. Análisis general por tienda:**
- Cálculo de ventas totales
- Gráfico comparativo entre tiendas

**2. Análisis por categoría:**
- Conteo de ventas por categoría de producto
- Gráficos individuales por tienda

**3. Análisis de productos:**
- Identificación de productos más y menos vendidos
- Visualización comparativa

**4. Métricas adicionales:**
- Calificación promedio de productos
- Costo promedio de envío

## 📋 Requisitos
- Python 3.x
- Bibliotecas:
  - matplotlib
  - pandas (para manejo de datos)

## 🚀 Cómo usar
1. Definir las variables tienda, tienda2, tienda3, tienda4 como DataFrames con las siguientes columnas:
- 'Precio'
- 'Categoría del Producto'
- 'Calificación'
- 'Producto'
- 'Costo de envío'

2. Ejecutar las funciones principales:

```python
mostrar_resultados_total_por_tienda()
mostrar_ventas_categoria_total_por_tienda()
grafico_ventas_categoria_total_por_tienda()
mostrar_calificacion_total_por_tienda()
mostrar_resultados_por_tienda()
mostrar_promedio_envio_por_tienda()
```

## 📈 Salidas
El script genera:
- Reportes textuales en consola
- Gráficos de barras para cada análisis
- Comparativas entre tiendas

## 🎨 Personalización
Puedes modificar:
- Nombres de tiendas en nombres_tienda
- Colores y estilos de los gráficos
- Tamaños de las figuras

## 📝 Notas
Asegúrate de que los DataFrames de las tiendas contengan todas las columnas necesarias para evitar errores.
