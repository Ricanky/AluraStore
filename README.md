# Análisis de Ventas y Desempeño de Alura Store

## Descripción

Este desafío tiene como objetivo ayudar al Sr. Juan a decidir cuál de las cuatro tiendas de su cadena **Alura Store** debería vender para iniciar un nuevo emprendimiento. Para ello, se analizan datos de ventas, rendimiento y reseñas de las 4 tiendas. El objetivo es identificar la tienda menos eficiente y ofrecer una recomendación basada en los datos analizados.

### Objetivos

1. **Evaluar los ingresos** generados por cada tienda.
2. **Analizar las categorías de productos más vendidas**.
3. **Evaluar las reseñas de los clientes** (calificaciones).
4. **Estudiar el rendimiento de ventas y ubicación geográfica** de cada tienda.
5. **Visualizar los resultados** mediante gráficos.
6. **Proponer una recomendación final** basada en el análisis de datos.

---

## Estructura de los Datos

El conjunto de datos utilizado incluye información sobre:

- **Producto y Categoría**: Artículos vendidos y sus calificaciones.
- **Precio y Envío**: Valores de venta y costos asociados al envío.
- **Fecha y Ubicación de Compra**: Información temporal y geográfica de cada transacción.
- **Evaluación de Compra**: Comentarios y calificaciones de los clientes.
- **Tipo de Pago y Cuotas**: Métodos de pago utilizados por los clientes.
- **Coordenadas Geográficas**: Ubicación de las transacciones (Latitud y Longitud).

---

## Análisis Realizado

1. **Carga y unificación de datos** de las 4 tiendas.
2. **Análisis de ingresos totales** por tienda.
3. **Visualización gráfica** de ingresos por tienda (gráfico de barras).
4. **Análisis de calificaciones promedio** por tienda.
5. **Distribución geográfica de ventas** mediante un gráfico de dispersión y mapa de calor.
6. **Análisis de rendimiento promedio** por tienda, utilizando coordenadas geográficas.

---

## Recomendación Final

Basado en el análisis de los datos de ingresos, reseñas y rendimiento de ventas, se realizó una recomendación.

## Requisitos

Este análisis se realizó utilizando **Google Colab**, por lo que no es necesario tener Jupyter instalado. Si desea ejecutar el código en su propio entorno, asegúrese de tener las siguientes bibliotecas:

- pandas
- matplotlib
- folium

Puede instalar las dependencias utilizando pip:

```bash
pip install pandas matplotlib folium
