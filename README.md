# 🛒 Análisis Comparativo de Tiendas - Challenge Data Science LATAM

Este proyecto presenta un análisis exploratorio y comparativo de datos de ventas provenientes de **cuatro tiendas diferentes**, como parte del Challenge de Ciencia de Datos de Alura LATAM. Cada tienda está representada por un archivo CSV individual y es tratada como una **entidad independiente**.

---

## 📁 Fuentes de Datos

Los datos han sido extraídos directamente desde GitHub:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene la siguiente información para cada venta:

- Producto
- Categoría
- Precio
- Costo de envío
- Fecha de compra
- Vendedor
- Lugar de compra
- Calificación
- Método de pago
- Cuotas
- Latitud y Longitud

---

## 📊 Análisis Realizados

### 1. 💵 Ingresos Totales por Tienda

Se calcularon los ingresos brutos por tienda y se representaron en un gráfico de barras, con etiquetas formateadas y escaladas en millones para mayor claridad.

### 2. 📦 Ingresos por Categoría de Producto

Se analizó la cantidad de productos vendidos por categoría en cada tienda. Esto permite identificar qué categorías tienen mayor rotación por tienda.

### 3. 🌟 Calificación Promedio

Se evaluó la satisfacción del cliente a través del promedio de calificaciones por tienda, visualizado con un gráfico de barras ajustado dinámicamente para destacar las diferencias.

### 4. 🔝 Productos Más y Menos Vendidos

Se identificaron los productos con mayor y menor cantidad de ventas por tienda, permitiendo observar tanto los líderes en ventas como aquellos con menor movimiento comercial.

### 5. 🚚 Costos Promedios de Envío

Se calculó el costo de envío promedio por tienda, representado con un gráfico de torta para visualizar la participación relativa de cada tienda en los costos de despacho.

### 6. 📌 Análisis Geográfico

Se utilizó la información de latitud y longitud para:

- Generar **mapas de calor (Seaborn KDE)** por tienda.
- Crear un **mapa interactivo (Folium)** con capas por tienda para observar la distribución de ventas en el territorio.

---

## 🗺️ Ejemplo de Visualización Geográfica

- Se comprobó que las tiendas operan en el mismo rango geográfico (misma región), aunque con ligeras diferencias en la densidad y distribución de los puntos de venta.
- Los mapas de calor permitieron identificar zonas de mayor concentración de actividad comercial.

---

## 🧠 Herramientas Utilizadas

- **Pandas**: Carga y manipulación de datos
- **Matplotlib / Seaborn**: Visualización de datos
- **Folium**: Mapas interactivos con capas geográficas
- **Python 3.10+**

---

## 📌 Conclusión

Este análisis permite comparar el rendimiento comercial de cada tienda desde múltiples dimensiones: ventas, satisfacción del cliente, logística de envío y distribución territorial. Las visualizaciones permiten extraer insights clave para la toma de decisiones estratégicas.

---

## 📎 Autor

Análisis desarrollado como parte del **Challenge Data Science LATAM** — Alura + Oracle

