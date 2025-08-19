# Challenge-Telecom-X- análisis de evasión de clientes

---

### Descripción General 

TelecomX LATAM es un proyecto de análisis de datos enfocado en comprender los factores detrás de la evasión de clientes (Churn). Mediante Python, Pandas y Matplotlib, se ejecuta un flujo ETL, estadísticas descriptivas, análisis exploratorio y visualizaciones estratégicas, generando insights claros y recomendaciones de negocio. Este proyecto forma parte de un desafío de prácticas reales para analistas de datos.

---

## 1. ▌DESCRIPCIÓN DEL PROYECTO

El notebook desarrolla un flujo ETL completo:

- **Extracción:** Datos de clientes desde una API en formato JSON.
- **Transformación:** Limpieza, tratamiento de valores faltantes, estandarización de columnas y creación de "Cuentas\_Diarias".
- **Análisis Exploratorio:** Métricas descriptivas (media, mediana, desviación), distribución del churn, análisis por variables categóricas y numéricas.
- **Informe final:** Introducción, metodología, visualizaciones y recomendaciones claras.

---

## 2. ▌ESTRUCTURA DEL CÓDIGO

1. Introducción y objetivo del proyecto.
2. Conexión y descarga de datos JSON.
3. Exploración de la estructura del dataset.
4. Limpieza y tratamiento de datos (valores nulos, duplicados).
5. Creación de nuevas métricas ("Cuentas\_Diarias").
6. Análisis descriptivo y distribución de churn.
7. Análisis por variables categóricas y numéricas.
8. Visualizaciones estratégicas con Matplotlib.
9. Informe final con recomendaciones.

---

## 3. ▌RESULTADOS PRINCIPALES

* Distribución clara del churn general.
* Patrones por género, tipo de contrato, método de pago.
* Relación entre gasto total y evasión.

---

## 4. ▌CONCLUSIONES E INSIGHTS

* Contratos mensuales y pagos electrónicos muestran mayor evasión.
* Clientes con soporte técnico frecuente tienden a cancelar más.
* Segmentos identificados para campañas de retención.

---

## 5. ▌RECOMENDACIONES

* Fidelizar clientes con contratos flexibles.
* Revisar la experiencia de facturación.
* Preparar modelos predictivos para detección temprana.

---

## 6. ▌PROBLEMAS FRECUENTES Y SOLUCIONES

| Problema                  | Solución                                   |
| ------------------------- | -------------------------------------------- |
| ◉ **API no responde**     | → Verificar token y endpoint                 |
| ◉ **Error JSON**          | → Validar estructura de los datos            |
| ◉ **Librerías faltantes** | → Ejecutar `pip install -r requirements.txt` |

---

