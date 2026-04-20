# 📊 Análisis de Datos y Dashboard Interactivo en Excel

## 📝 Descripción del Proyecto

Este proyecto tiene como objetivo aplicar una metodología completa de análisis de datos utilizando Microsoft Excel, abarcando desde la importación de datos hasta la creación de un dashboard interactivo.

Se estructura en tres fases principales:

1. **Importación y preparación de datos**
2. **Análisis de datos**
3. **Creación de un dashboard interactivo**

El objetivo es transformar datos brutos en información clara y accionable mediante visualizaciones dinámicas y KPIs.

---

## 📊 Dataset Utilizado

* **Dataset principal**: `kiva_loans.csv`
* **Fuente**: Kaggle
* **Organización**: Kiva.org

Este dataset contiene información sobre préstamos concedidos a nivel global, incluyendo variables como importe, país, sector, género y plazos de devolución.

---

## 📌 Elección de KPIs del Dashboard

Para el diseño del dashboard se seleccionaron indicadores clave que permiten entender rápidamente el comportamiento de los préstamos:

* 💰 **Total Loan Amount**: volumen total de préstamos concedidos
* 💵 **Total Funded Amount**: cantidad total financiada
* 🧑‍🤝‍🧑 **Total Partner ID**: número agregado de socios involucrados
* ⏳ **Total Term in Months**: suma de los plazos de los préstamos

Estos KPIs permiten tener una visión general del impacto financiero y operativo del dataset.

---

## 📊 Visualizaciones del Dashboard

El dashboard incluye diferentes tipos de gráficos para facilitar el análisis:

* 📈 Distribución de préstamos por **sector**
* 🌍 Análisis por **país**
* 👥 Segmentación por **género**
* ⏱️ Comparativa por **tipo de pago** (monthly, irregular, bullet)
* 📅 Filtros interactivos por **año**

Además, se implementaron **segmentadores (slicers)** que permiten filtrar todos los gráficos de forma dinámica.

---

## 🛠️ Tecnologías Utilizadas

* Microsoft Excel
* Tablas dinámicas (Pivot Tables)
* Segmentadores (Slicers)
* Power Query (transformación de datos)

---

## 📦 Estructura del Proyecto

```
📁 proyecto1-analisisexcel-irene/
│
├── 📄 README.md
├── dashboard.png
├── 📊 proyecto001.xlsx
├── 📁 data/
│   └── kiva_loans.csv
```

---

## ⚙️ Proceso de Desarrollo

### 1. Importación y Preparación

* Importación de datos en Excel
* Conversión a formato tabla
* Limpieza de datos (duplicados, ordenación, filtros)

### 2. Análisis de Datos

* Uso de tablas dinámicas para agregaciones
* Creación de métricas clave
* Análisis exploratorio

### 3. Creación del Dashboard

* Diseño visual con formas y KPIs
* Gráficos dinámicos conectados a tablas dinámicas
* Interactividad mediante segmentadores

---

## 🖥️ Vista del Dashboard

![Dashboard Excel](./dashboard.png)

---

## ▶️ Cómo Usar el Proyecto

1. Abrir el archivo `proyecto001.xlsx`
2. Ir a la hoja **Dashboard**
3. Utilizar los **segmentadores** para filtrar datos
4. Analizar los cambios dinámicos en KPIs y gráficos

---

## 🚀 Conclusión

Este proyecto demuestra cómo Excel puede utilizarse como una herramienta completa de análisis de datos, permitiendo construir dashboards interactivos y visualmente atractivos sin necesidad de software adicional.

---

