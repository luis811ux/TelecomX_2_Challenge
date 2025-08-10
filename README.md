# 📞 TELECOM X - Predicción de Cancelación de Clientes (Churn)

## 🚀 Descripción del Proyecto

Este proyecto desarrolla un **modelo predictivo de Machine Learning** para identificar clientes con alto riesgo de desafiliación en la empresa de telecomunicaciones **TELECOM X**. El objetivo es anticiparse al problema de cancelación y permitir a la empresa implementar estrategias proactivas de retención.

## 🎯 Objetivos

- ✅ Desarrollar un pipeline robusto de Machine Learning
- ✅ Preparar y transformar datos para modelado predictivo
- ✅ Construir y evaluar modelos de clasificación
- ✅ Identificar factores clave que influyen en la cancelación
- ✅ Proponer estrategias de retención basadas en datos

## 🧠 Metodología

El proyecto sigue una metodología estructurada en **4 fases principales**:

### 🟩 FASE A: Exploración y Limpieza
- Análisis exploratorio de datos
- Validación de estructura y calidad
- Codificación de variables
- Análisis de variable objetivo

### 🟦 FASE B: Ingeniería y Preparación
- Feature engineering
- Análisis de correlaciones
- Eliminación de variables irrelevantes
- Tratamiento de outliers y balanceado de clases

### 🟨 FASE C: Modelado y Evaluación
- Construcción de modelos predictivos
- Validación cruzada
- Optimización de hiperparámetros
- Ajuste de umbral para maximizar F1-score

### 🟫 FASE D: Producción y Documentación
- Guardado del modelo optimizado
- Informe de resultados y estrategias

## 📊 Resultados Principales

### Comparación de Modelos Ramdon Forest

| Métrica | Modelo Inicial | Modelo Optimizado | Mejora |
|---------|----------------|-------------------|---------|
| **Recall** | 44.92% | **77.54%** | +32.6% |
| **F1-score** | 47.86% | **57.83%** | +9.97% |
| **AUC** | 70.21% | **77.02%** | +6.81% |

### Variables Más Influyentes

1. **Antigüedad** (27.99%) - Clientes nuevos tienen mayor riesgo
2. **Cargo Diario** (25.87%) - Tarifas altas aumentan cancelaciones
3. **Soporte Técnico** (13.51%) - Su uso mejora la retención
4. **Seguridad en Línea** (8.65%) - Servicios adicionales generan valor
5. **Tipo de Internet** (8.16%) - Fibra óptica asociada a mayores expectativas

## 🎯 Estrategias de Retención Propuestas

### 👶 Clientes Nuevos
- Proceso de bienvenida personalizado
- Programas de fidelización temprana
- Contactos proactivos primeros 90 días

### 💰 Clientes con Tarifas Altas
- Revisión personalizada de planes
- Paquetes con beneficios adicionales
- Justificación de valor

### 🔧 Segmento Sin Soporte Técnico
- Campañas educativas
- Seguimiento proactivo de incidencias

### 🔒 Segmento Sin Seguridad
- Promociones de prueba gratuita
- Paquetes incluidos en planes premium

## 🛠️ Tecnologías Utilizadas

- **Python** - Lenguaje principal
- **Pandas & NumPy** - Manipulación de datos
- **Scikit-learn** - Machine Learning
- **Matplotlib & Seaborn** - Visualización
- **SMOTE** - Balanceado de clases
- **RandomForest** - Modelo principal
- **Google Colab** - Desarrollo

## 📁 Estructura del Proyecto

```
├── data/                          # Datos del proyecto (CSV original)
├── telecom-churn-prediction.ipynb # Notebook principal con todo el análisis
└── README.md                     # Este archivo
```

**El notebook contiene:**
- 🔍 **Código fuente completo** - Todas las fases del pipeline
- 🤖 **Modelos** - Modelo inicial y optimizado guardados
- 📊 **Informes y visualizaciones** - Gráficos, matrices de confusión y análisis

## 🚀 Cómo Ejecutar el Proyecto

### Prerrequisitos
- **Google Colab** (recomendado) - Python 3.11 y todas las librerías ya preinstaladas
- O **Jupyter Notebook local** con Python 3.8+

### Ejecución
1. Clona el repositorio
2. Instala las dependencias
3. Abre y ejecuta `TelecomX_2_LATAM.ipynb`
4. El notebook contiene todo el análisis completo desde la exploración hasta el informe final

## 📈 Impacto del Proyecto

- **59% de reducción** en falsos negativos (de 206 a 84 casos)
- **Identificación proactiva** de clientes en riesgo
- **Estrategias segmentadas** de retención basadas en datos variable de mayor importancia
- **Mejor detección** de clientes que se desafiliarán

## 🔍 Próximos Pasos

- [ ] Implementación en producción
- [ ] Monitoreo continuo del modelo
- [ ] A/B testing de estrategias de retención
- [ ] Incorporación de nuevas variables
- [ ] Automatización del pipeline

## 👨‍💻 Autor

**Analista Junior de Machine Learning - TELECOM X**

---

📧 **Contacto:** luisfer811@gmail.com  
🔗 **LinkedIn:** www.linkedin.com/in/luis-fernando-alcala-ramirez-98263043  
📅 **Fecha:** Agosto 2025

---

⭐ **¿Te gustó este proyecto?** ¡Dale una estrella y compártelo!

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.
