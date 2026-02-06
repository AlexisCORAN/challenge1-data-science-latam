
# Análisis de Desempeño Comercial: Alura Store Latam

## Descripción del Proyecto

Este proyecto consiste en un análisis de **Business Intelligence (BI)** aplicado a una cadena de retail con cuatro sucursales. El objetivo principal es evaluar el rendimiento sistémico de cada tienda para asesorar al "Sr. Juan" en la toma de decisiones estratégicas, específicamente identificando qué unidad de negocio presenta menor eficiencia operativa para su posible desinversión.

El análisis abarca dimensiones financieras, logísticas, de satisfacción del cliente y distribución geoespacial.

---

## 🛠️ Stack Tecnológico

| Tecnología | Uso Principal |
| --- | --- |
| **Python 3.x** | Lenguaje base del análisis. |
| **Pandas** | Manipulación y procesamiento de estructuras de datos (DataFrames). |
| **Matplotlib** | Generación de visualizaciones estáticas y mapas de calor. |
| **Google Colab** | Entorno de desarrollo y ejecución en la nube. |

---

## Metodología de Análisis

El flujo de trabajo se dividió en cinco fases críticas:

1. **Entrada de Datos:** Carga y consolidación de datasets externos vía URL.
2. **Análisis de Facturación:** Evaluación del ingreso total y participación de mercado (Market Share).
3. **Evaluación de costos de envío:** Análisis de la relación entre el precio del producto y el costo de envío mediante gráficos de dispersión.
4. **Satisfacción del cliente:** Procesamiento de métricas de feedback de clientes (Rating promedio).
5. **Análisis Geoespacial:** Generación de **Heatmaps** y detección de **Hotspots** (nodos de alta demanda) mediante coordenadas de latitud y longitud.

---

##  Principales Hallazgos (Insights)

* **Eficiencia Financiera:** La Tienda 1 lidera la facturación, mientras que la **Tienda 4** presenta un déficit del ~10% respecto a la líder.
* **Correlación Logística:** Se identificó una correlación lineal directa entre el costo de envío y el precio del producto.
* **Falla de Competitividad:** El análisis geoespacial demostró que todas las tiendas compiten en los mismos nodos urbanos. 

---

## Estructura del Repositorio

* `AluraStoreLatam.ipynb`: Notebook principal con el código documentado.
* `README.md`: Documentación del proyecto.

---

## Conclusión Técnica

Tras la evaluación multivariable, se recomienda la **venta de la Tienda 4**. La decisión se fundamenta en su baja capacidad de conversión en zonas de alta densidad de mercado y su impacto negativo en la reputación de la marca debido a bajas calificaciones de servicio.

---

### Autor

Alexis Coronado
*Estudiante de Ingeniería de Sistemas e Informática*

---
