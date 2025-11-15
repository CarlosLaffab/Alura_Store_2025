# Análisis de Desempeño de Tiendas y Recomendación Estratégica

## 🚀 Introducción
Este proyecto tiene como objetivo principal realizar un análisis exhaustivo del desempeño de cuatro tiendas de comercio electrónico del Sr. Juan para identificar la tienda con el rendimiento más bajo y recomendar su cierre, buscando optimizar la rentabilidad y la eficiencia operativa del negocio.

## 🎯 Objetivos del Análisis
El análisis se centró en las siguientes métricas clave para cada una de las cuatro tiendas:

*   **Ingresos Totales:** Evaluación de la capacidad de generación de ingresos.
*   **Satisfacción del Cliente:** Medida a través de la calificación promedio de los clientes.
*   **Costo de Envío Promedio:** Análisis de la eficiencia logística.
*   **Ventas por Categoría:** Identificación de las categorías de productos más y menos populares.
*   **Productos Más y Menos Vendidos:** Detección de productos estrella y de bajo rendimiento.
*   **Análisis Geográfico:** Visualización de la distribución de ventas y patrones de concentración.

## 🛠️ Metodología
El análisis se llevó a cabo utilizando Python y las librerías `pandas`, `matplotlib`, y `seaborn`. Los pasos principales incluyeron:

1.  **Importación y Consolidación de Datos:** Carga de los archivos CSV de cada una de las cuatro tiendas y concatenación en un único DataFrame.
2.  **Limpieza y Preprocesamiento de Datos:** Conversión de tipos de datos (fechas, precios a numérico) y manejo de valores nulos.
3.  **Cálculo de Métricas Clave:** Agrupación y agregación de datos para obtener ingresos, calificaciones, costos de envío, y conteos de ventas por producto y categoría.
4.  **Visualización de Datos:** Creación de gráficos (barras, líneas, pastel, dispersión) para facilitar la interpretación de las métricas.
5.  **Análisis Geográfico:** Estudio de la latitud y longitud de las compras para entender la distribución espacial de las ventas.

## 📊 Hallazgos Clave y Conclusiones

A continuación, se resumen los hallazgos más relevantes por métrica:

### Ingresos Totales por Tienda
| Tienda   | Ingresos Totales (COP) |
|:---------|:-----------------------|
| Tienda 1 | 11,508,804,000         |
| Tienda 2 | 11,163,435,000         |
| Tienda 3 | 10,980,196,000         |
| Tienda 4 | 10,383,757,000         |

*   **Conclusión:** La **Tienda 1** es la líder en ingresos, mientras que la **Tienda 4** muestra el rendimiento más bajo en esta métrica.

### Calificación Promedio de Clientes por Tienda
| Tienda   | Calificación Promedio |
|:---------|:----------------------|
| Tienda 1 | 3.98                  |
| Tienda 2 | 4.04                  |
| Tienda 3 | 4.05                  |
| Tienda 4 | 4.00                  |

*   **Conclusión:** La **Tienda 3** tiene la calificación más alta, indicando la mayor satisfacción del cliente. Todas las tiendas mantienen un buen nivel general de satisfacción.

### Costo de Envío Promedio por Tienda
| Tienda   | Costo de Envío Promedio (COP) |
|:---------|:------------------------------|
| Tienda 1 | 26,019                        |
| Tienda 2 | 25,216                        |
| Tienda 3 | 24,806                        |
| Tienda 4 | 23,459                        |

*   **Conclusión:** La **Tienda 4** tiene el costo de envío promedio más bajo, mientras que la Tienda 1 tiene el más alto.

### Ventas por Categoría
*   **Categoría Más Vendida:** "**Muebles**" es consistentemente la categoría principal en todas las tiendas.
*   **Categoría Menos Vendida:** "Artículos para el hogar" o "Instrumentos musicales" (en Tienda 4).

### Productos Más y Menos Vendidos
*   Se identificaron productos estrella y de bajo rendimiento específicos para cada tienda, reflejando particularidades locales o de inventario.

### Análisis Geográfico
*   Las ventas de todas las tiendas se concentran principalmente en la región central de Colombia (ciudades como Bogotá, Medellín, Cali y Cartagena).
*   Existe una **alta superposición geográfica** entre las operaciones de las cuatro tiendas, lo que indica que compiten en los mismos mercados clave.
*   La **Tienda 4** mostró una densidad de ventas ligeramente menor en los clústeres más densos en comparación con las otras tiendas, lo cual se correlaciona con sus ingresos más bajos.

## 💡 Recomendación Final: Cierre de la Tienda 4

Basado en el análisis objetivo de las métricas de desempeño, se recomienda al Sr. Juan **cerrar la Tienda 4**.

### Justificación:
*   **Menor Rendimiento Financiero:** La Tienda 4 genera consistentemente los **ingresos totales más bajos**.
*   **Desempeño Combinado:** A pesar de tener el costo de envío más bajo, esta ventaja no compensa su bajo volumen de ventas y no la diferencia significativamente en satisfacción del cliente respecto a las demás.
*   **Consistencia Negativa:** En comparación con el rendimiento superior de las Tiendas 1 y 2, y la alta satisfacción de la Tienda 3, la Tienda 4 presenta la combinación menos atractiva de métricas para la continuidad.

### Beneficios del Cierre:
*   **Optimización de Recursos:** Reasignación de recursos a tiendas más rentables.
*   **Reducción de Costos Operativos:** Eliminación de costos fijos y variables asociados a la Tienda 4.
*   **Mejora del Enfoque Estratégico:** Concentración de esfuerzos en unidades de mayor rendimiento y potencial.

## 📂 Anexos y Archivos Generados
Durante este análisis, se generaron los siguientes archivos CSV que contienen los resultados detallados:

*   `ingresos_por_tienda.csv`
*   `categoria_mas_vendida_por_tienda.csv`
*   `categoria_menos_vendida_por_tienda.csv`
*   `calificacion_promedio_por_tienda.csv`
*   `productos_mas_vendidos_por_tienda.csv`
*   `productos_menos_vendidos_por_tienda.csv`
*   `costo_envio_promedio_por_tienda.csv`

## 🏃 Cómo Ejecutar el Proyecto
1.  **Clonar el repositorio:** `git clone <URL_DEL_REPOSITORIO>`
2.  **Abrir el notebook:** Cargar el archivo `.ipynb` en Google Colab o Jupyter Notebook.
3.  **Instalar dependencias:** Asegúrate de tener `pandas`, `matplotlib` y `seaborn` instalados (`pip install pandas matplotlib seaborn`).
4.  **Ejecutar todas las celdas:** Corre las celdas en orden para reproducir el análisis.

## ✍️  CARLOS D. VARGAS CASTRO
Modelo de Lenguaje de Google Colab
