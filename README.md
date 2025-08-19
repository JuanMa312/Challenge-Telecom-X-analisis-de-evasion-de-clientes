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

## 2. ▌REQUISITOS DEL SISTEMA


| **Lenguaje**     |
|:-----------------:|
| **Python >= 3.8**| 
|<img src="https://github.com/user-attachments/assets/9352bed0-668d-49ec-ab0b-e621ef4fa462" width="120" alt="Python logo">|

|| **Bibliotecas necesarias:** ||
|:-----------------:|:-----------------:|:-----------------:|
| **Pandas**      | **Matplotlib**      | **NumPy**     
|<img src="https://github.com/user-attachments/assets/9a938aa7-6c50-4142-aab8-68180fb072f9" width="120" alt="Pandas logo"> | <img src="https://github.com/user-attachments/assets/06721bd1-e433-4c99-aa2c-5799c9d2b286" width="120" alt="Matplotlib logo"> | <img src="https://numpy.org/images/logo.svg" width="120" alt="NumPy logo"> |

|Entorno ||
|:-----------------:|:-----------------:|
|Jupyter Notebook| Google Colab|
|<img width="120" height="120" alt="descarga" src="https://github.com/user-attachments/assets/ce18a335-1543-4194-a5b8-551c19348b0d" />|<img width="120" height="120" alt="descarga (1)" src="https://github.com/user-attachments/assets/a1ed5c80-3052-4264-8935-0930f80f1a2d" />|


---

## 3. ▌ESTRUCTURA DEL CÓDIGO

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

## 6. ▌RESULTADOS PRINCIPALES

* Distribución clara del churn general.
* Patrones por género, tipo de contrato, método de pago.
* Relación entre gasto total y evasión.

---

## 7. ▌CONCLUSIONES E INSIGHTS

* Contratos mensuales y pagos electrónicos muestran mayor evasión.
* Clientes con soporte técnico frecuente tienden a cancelar más.
* Segmentos identificados para campañas de retención.

---

## 8. ▌RECOMENDACIONES

* Fidelizar clientes con contratos flexibles.
* Revisar la experiencia de facturación.
* Preparar modelos predictivos para detección temprana.

---

## 9. ▌PROBLEMAS FRECUENTES Y SOLUCIONES

| Problema                  | Solución                                   |
| ------------------------- | -------------------------------------------- |
| ◉ **API no responde**     | → Verificar token y endpoint                 |
| ◉ **Error JSON**          | → Validar estructura de los datos            |
| ◉ **Librerías faltantes** | → Ejecutar `pip install -r requirements.txt` |

---

