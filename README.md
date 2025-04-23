# 📊 Análisis de Ventas por Tienda

Este proyecto en Python tiene como finalidad analizar y visualizar información clave sobre el comportamiento de ventas en distintas tiendas, usando archivos CSV como fuente de datos. Cada tienda es analizada por separado para entender mejor sus tendencias, productos populares, y otros factores relevantes de negocio.

---

## 📁 Estructura del Proyecto

Cada archivo `.csv` representa las ventas de una tienda y contiene columnas como:

- `Producto`
- `Fecha de Compra` (formato: `dd/mm/yyyy`)
- `Calificación`
- `Categoría`
- `Costo de Envío`
- `Método de Pago`
- `Precio` o `Total de Venta` *(según el formato del archivo)*

---

## 🛠 Tecnologías Utilizadas

- **Python 3**
- **pandas** para manejo de datos
- **matplotlib** para visualización
- **collections.Counter** para conteos rápidos

---

## 📈 Análisis Realizados

### ✅ 1. **Facturación Total por Tienda**
- Se calcula la suma total de ventas en cada tienda.
- Opción de visualizarlo en gráficos de barras o pastel.

### ✅ 2. **Método de Pago más Utilizado**
- Se agrupa por tipo de pago y se visualiza el método preferido por tienda.

### ✅ 3. **Ventas por Categoría**
- Agrupación por `Categoría` de producto.
- Conteo de ventas por tipo de producto.
- Visualización de las categorías más populares por tienda.

### ✅ 4. **Calificación Promedio por Tienda**
- Se calcula el promedio de calificación de los productos vendidos.
- Se visualiza mediante gráfica tipo `pie`.

### ✅ 5. **Productos Más y Menos Vendidos**
- Uso de `Counter` para identificar productos con más y menos unidades vendidas.
- Visualización con gráfica de barras horizontal.

### ✅ 6. **Costo de Envío Promedio por Tienda**
- Se calcula el costo promedio de envío por tienda.
- Representación clara para identificar qué tienda implica mayor gasto logístico.

### ✅ 7. **Ventas por Año**
- Conversión de fechas y agrupación por año.
- Conteo total de compras por año (2020–2023).
- Visualización mediante gráfica de líneas.

---

## 📊 Ejemplos de Visualizaciones

- Barras horizontales: productos más vs. menos vendidos
- Pastel: calificaciones o categorías
- Líneas: evolución de ventas por año
- Barras agrupadas: categorías más vendidas

---

📊 Conclusión del Análisis
Después de realizar un análisis completo de las tiendas disponibles, evaluando criterios como:

Ventas totales

Cantidad de productos vendidos

Calificación promedio por tienda

Categorías más populares

Gastos promedio de envío

Estabilidad de ventas por año

Métodos de pago más utilizados

Se concluye que la mejor opción es vender la Tienda 4.
Aunque esta tienda representa el menor gasto promedio de envío, también es la que genera menores ingresos totales, con una calificación aceptable pero sin destacar frente a sus competidoras. Además, no sobresale en ninguna métrica clave que justifique conservarla como parte del portafolio.

Por el contrario, las demás tiendas presentan ventajas importantes:

Tienda 1: Mayor volumen de ventas y estabilidad anual.

Tienda 2: Buen equilibrio entre calificación, ventas y costos.

Tienda 3: Mejor calificación promedio del cliente y ventas aceptables.

Con base en este análisis, vender la Tienda 4 permite maximizar el rendimiento general del negocio, conservando aquellas tiendas con mayor potencial de crecimiento y rentabilidad.
