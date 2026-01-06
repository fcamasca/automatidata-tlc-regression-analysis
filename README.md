# 🚕 Proyecto Automatidata — TLC (Regresión Lineal)
**Estimación Predictiva de Tarifas de Taxi | Baseline Interpretable**

![Status](https://img.shields.io/badge/Regression-Complete-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-blue)
![PowerBI](https://img.shields.io/badge/PowerBI-Report-blue)
![Last Update](https://img.shields.io/badge/Last_Update-2026-lightgrey)

---

## 🧠 Sobre el Proyecto

Automatidata colabora con la **Taxi and Limousine Commission (TLC) de Nueva York** para desarrollar un modelo analítico que permita **estimar la tarifa de un viaje de taxi antes de que ocurra**, utilizando únicamente información disponible en ese momento.

El proyecto combina análisis exploratorio, depuración de datos, ingeniería de variables y un modelo de **regresión lineal interpretable**, con el objetivo de identificar los factores que influyen en el costo del viaje y apoyar la toma de decisiones operativas y financieras.

📌 **Alcance del proyecto**
- Modelo predictivo como **línea base interpretable**
- Enfoque explicativo y de comunicación, no productivo
- Documentación metodológica (PACE) y resumen ejecutivo para stakeholders

---

## 🔑 Insights Clave

- La *distancia promedio del viaje* es el principal factor que explica la tarifa, seguida por la *duración promedio*.
- El costo estimado equivale aproximadamente a **2 USD por cada milla adicional recorrida**, manteniendo constantes los demás factores.
- Existen **tarifas reguladas fijas** que generan patrones específicos y no dependen de distancia ni tiempo.
- El modelo explica aproximadamente **entre 84 % y 87 % de la variabilidad de la tarifa**, con desempeño consistente entre entrenamiento y prueba.
- La depuración de valores atípicos y la eliminación de variables no disponibles antes del viaje mejoraron la capacidad de generalización.

---

## 📊 Resultados del Modelo

**Desempeño**
- R² (entrenamiento): ~0.84  
- R² (prueba): ~0.87  
- Error promedio: ~2 USD  
- Error típico: ~4 USD  

Estos resultados indican que el modelo es adecuado como **herramienta de estimación previa**, no como tarifa exacta.

---

## 🗂️ Estructura del Repositorio

```
automatidata-tlc-regression/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── automatidata_tlc_regression_portfolio.ipynb
│
├── dashboards/
│   ├── tableau/
│   └── powerbi/
│
├── documents/
│   ├── PACE/
│   │   └── PACE_Automatidata_TLC.pdf
│   └── executive_summary/
│       └── Resumen_Ejecutivo_Automatidata_TLC.pdf
│
├── images/
│   └── README.md
│
├── requirements.txt
└── README.md
```

---

## 📄 Documentos del Proyecto

| Tipo | Archivo |
|------|--------|
| 📘 Notebook (Regresión) | `notebooks/automatidata_tlc_regression_portfolio.ipynb` |
| 📄 PACE (Metodología) | `documents/PACE/PACE_Automatidata_TLC.pdf` |
| 🧾 Resumen Ejecutivo | `documents/executive_summary/Resumen_Ejecutivo_Automatidata_TLC.pdf` |
| 📊 Evidencias Tableau | `dashboards/tableau/` |
| 📈 Evidencias Power BI | `dashboards/powerbi/` |

---

## 🔧 Cómo Ejecutar el Proyecto

1. Clonar el repositorio  
2. Instalar dependencias  
3. Abrir el notebook en Jupyter  

*(flujo estándar, ver `requirements.txt`)*

---

## 🧪 Tecnologías y Herramientas

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  
- Tableau  
- Power BI  

---

## 📬 Autor

**Frankz Camasca**  
Analista de Datos | Modelado • Interpretabilidad • Storytelling con datos

GitHub: https://github.com/fcamasca  
LinkedIn: https://www.linkedin.com/in/frankz-william-camasca-castillo-b63a0094

---

## 📄 Licencia
Proyecto de uso educativo y demostración profesional.
