

# 🛰️ WasiGuard: Sistema Inteligente de Predicción y Alerta de Huaicos

**WasiGuard** es un sistema integral de monitoreo, simulación y alerta temprana de huaicos en zonas vulnerables del Perú. Este proyecto combina análisis geoespacial, modelado de desastres naturales y tecnologías de visualización para ofrecer una herramienta predictiva que puede salvar vidas.


---

## 🚀 Objetivo del Proyecto

El objetivo principal de WasiGuard es:

- Detectar zonas de posible impacto ante huaicos usando modelos de elevación digital (DEM) y puntos de alerta.
- Simular zonas de afectación utilizando filtros gaussianos sobre mapas topográficos.
- Determinar usuarios potencialmente afectados en tiempo real y alertarlos de forma oportuna.
- Proporcionar rutas de evacuación seguras.
- Visualizar mapas interactivos con zonas de impacto, usuarios y alertas en mapas satelitales.

---

## 🔍 ¿Por qué este proyecto es importante?

- **Prevención de desastres**: El cambio climático y la urbanización aumentan el riesgo de huaicos. Anticiparse puede salvar cientos de vidas.
- **Tecnología con propósito**: Uso de datos abiertos, ciencia de datos geoespacial y sensores para proteger comunidades.
- **Aplicación real**: Pensado para ser implementado en gobiernos locales, ONGs y redes de protección civil.

---

## 🧠 Tecnologías utilizadas

- Python, Jupyter Notebooks
- GeoPandas, Rasterio, Shapely, Scipy
- Contextily, Matplotlib
- Archivos DEM y GeoJSON
- Automatización de alertas y exportación de resultados

---

## 📌 Estructura del repositorio

```
PrediccionAlcanceHuaico/
│
├── data/                # Datos de entrada (DEM, usuarios, puntos de alerta)
├── results/             # Zonas afectadas simuladas y CSVs de usuarios alertados
├── notebooks/           # Notebooks de simulación y análisis
├── utils/               # Funciones auxiliares (en desarrollo)
└── README.md            # Este archivo
```

---

## 🎯 Resultados

El sistema permite simular diferentes escenarios de huaico con alta precisión espacial y determinar en segundos qué usuarios registrados se encuentran en zonas de riesgo. Los resultados se exportan como:

- Polígonos de zonas afectadas (GeoJSON)
- CSV de usuarios alertados con detalles
- Mapas interactivos de validación

