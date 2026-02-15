# 📊 Telecom X - Predicción (Parte 2)
<div align="center">
``
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dZR4UQkFRlTS7l4flv0ayyBiLTUMRe8y?usp=drive_link)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-success.svg)]()

**Sistema de Machine Learning para predecir la cancelación de clientes en telecomunicaciones**

[🚀 Ejecutar en Colab](https://colab.research.google.com/drive/1dZR4UQkFRlTS7l4flv0ayyBiLTUMRe8y?usp=drive_link) • [📧 Contacto](mailto:jordanne@hotmail.es)

</div>

---

## 👨‍💻 Autor

**Jordan Negria Chiripua** | *Ingeniero de Sistemas*  
📧 [jordanne@hotmail.es](mailto:jordanne@hotmail.es)

> *"Los datos no mienten, pero tampoco cuentan toda la historia. Nuestro trabajo es encontrar el significado detrás de los números."*

---

## 🎯 Descripción del Proyecto

Pipeline completo de Machine Learning que predice qué clientes tienen mayor probabilidad de cancelar sus servicios en una empresa de telecomunicaciones. El proyecto incluye:

✅ Preparación y limpieza de datos  
✅ Análisis exploratorio con visualizaciones  
✅ 4 modelos de clasificación (Logistic Regression, KNN, Random Forest, Decision Tree)  
✅ Evaluación exhaustiva con múltiples métricas  
✅ Interpretación de variables importantes  
✅ Recomendaciones estratégicas para retención de clientes

---

## ⚡ Inicio Rápido

### Opción 1: Google Colab (Recomendado)

**¡La forma más rápida!** Solo 3 pasos:

1. Haz clic aquí: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dZR4UQkFRlTS7l4flv0ayyBiLTUMRe8y?usp=drive_link)
2. Ejecuta las celdas en orden ▶️
3. Obtén resultados en 5 minutos ⚡

**Sin instalaciones • Sin configuraciones • Dataset incluido**

### Opción 2: Local

```bash
# Clonar repositorio
git clone https://github.com/jordannegria/Challenge-Telecom-X---Parte-2.git
cd Challenge-Telecom-X---Parte-2

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar notebook
jupyter notebook Telecom_X_Parte2_Prediccion_Churn.ipynb
```

---

## 📊 Dataset

| Característica | Detalle |
|----------------|---------|
| **Registros** | 7,267 clientes |
| **Variables** | 21 features + 1 target |
| **Target** | Churn (Yes/No) |
| **Balance** | 73.5% No Churn / 26.5% Churn |

### Variables Principales

- **Cliente:** Género, edad senior, pareja, dependientes, antigüedad
- **Servicios:** Teléfono, internet (DSL/Fibra), seguridad, soporte técnico, streaming
- **Cuenta:** Tipo de contrato, método de pago, cargos mensuales/totales

---

## 🤖 Modelos Implementados

| Modelo | Normalización | Características |
|--------|---------------|-----------------|
| **Regresión Logística** | ✅ Sí | Interpretable, coeficientes claros |
| **K-Nearest Neighbors** | ✅ Sí | k=5 vecinos, sensible a escala |
| **Random Forest** | ❌ No | 100 árboles, importancia de variables |
| **Decision Tree** | ❌ No | max_depth=10, fácil interpretación |

---

## 📈 Resultados

### Métricas de Evaluación

Todos los modelos son evaluados con:
- ✅ Accuracy (Exactitud)
- ✅ Precision (Precisión)
- ✅ Recall (Sensibilidad)
- ✅ F1-Score (Balance)
- ✅ ROC-AUC (Discriminación)
- ✅ Matriz de Confusión

### Variables Más Importantes

Los análisis revelan que los principales factores de churn son:

1. 📝 **Tipo de contrato** (Month-to-month tiene 3x más riesgo)
2. ⏰ **Antigüedad del cliente** (primeros 6 meses críticos)
3. 💰 **Cargo mensual** (precios altos aumentan cancelación)
4. 🌐 **Tipo de internet** (Fiber optic tiene mayor churn)
5. 🛡️ **Servicios adicionales** (Soporte técnico reduce churn 25%)

---

## 🎨 Visualizaciones

El notebook incluye más de **20 visualizaciones profesionales**:

- 📊 Distribución de churn y balance de clases
- 🔥 Matrices de correlación
- 📦 Boxplots comparativos
- 🎯 Matrices de confusión
- 📈 Curvas ROC
- 📊 Importancia de variables
- 📉 Análisis de overfitting

---

## 🛠️ Estructura del Proyecto

```
Challenge-Telecom-X---Parte-2/
│
├── 📓 Telecom_X_Parte2_Prediccion_Churn.ipynb  # Notebook principal
├── 📊 datos_tratados.csv                        # Dataset
├── 📖 README.md                                 # Este archivo
```

---

## 🔍 Características Destacadas

### 🎯 Automatización Inteligente
- Detección automática de columnas (target, IDs, features)
- Tratamiento automático de valores faltantes
- Selección automática del mejor modelo
- Generación automática de reportes

### 📊 Análisis Completo
- Pipeline end-to-end desde datos crudos hasta insights
- Preprocesamiento robusto (encoding, normalización, balanceo)
- Evaluación exhaustiva con múltiples métricas
- Interpretación de resultados con visualizaciones

### 💼 Enfoque de Negocio
- Conclusiones estratégicas accionables
- Recomendaciones para retención de clientes
- Identificación de segmentos de alto riesgo
- KPIs para monitoreo continuo

---

## 💡 Conclusiones Estratégicas

El análisis identifica **4 áreas clave de acción**:

### 1️⃣ Contratos y Fidelización
- Incentivar contratos de 1-2 años con descuentos
- Beneficios progresivos por antigüedad
- Programas de puntos y recompensas

### 2️⃣ Servicio al Cliente
- Mejorar soporte técnico en primeros 6 meses
- Ofrecer seguridad online sin costo adicional
- Sistema de alertas tempranas para clientes en riesgo

### 3️⃣ Estrategia de Precios
- Revisar estructura de precios para Fiber optic
- Paquetes personalizados según perfil
- Descuentos proactivos a clientes de alto riesgo

### 4️⃣ Retención Proactiva
- Usar modelo para scoring mensual de clientes
- Contacto proactivo cuando probabilidad > 70%
- Campañas de retención personalizadas

---

## 📚 Requisitos

### Librerías

```python
pandas >= 1.3.0
numpy >= 1.21.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
scikit-learn >= 0.24.0
imbalanced-learn >= 0.8.0
```

### Instalación

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```



---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar el proyecto:

1. 🍴 Haz un Fork del repositorio
2. 🔨 Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push a la rama (`git push origin feature/AmazingFeature`)
5. 🔃 Abre un Pull Request

---

## 📞 Contacto

**Jordan Negria Chiripua**  
*Ingeniero de Sistemas*

📧 Email: [jordanne@hotmail.es](mailto:jordanne@hotmail.es)  
🔗 GitHub: [@jordannegria](https://github.com/jordannegria)

---

## ⭐ ¿Te fue útil este proyecto?

Si este proyecto te ayudó en tu aprendizaje o trabajo:

- ⭐ Dale una estrella al repositorio
- 🔄 Compártelo con otros
- 📧 Envíame tus comentarios

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

Desarrollado con fines educativos como parte del Challenge Telecom X.

---

## 🙏 Agradecimientos

- **Telecom X** - Por proporcionar el desafío
- **Comunidad de Data Science** - Por recursos y mejores prácticas
- **Scikit-learn Team** - Por la increíble librería de ML
- **Usuarios del proyecto** - Por el feedback y sugerencias

---

<div align="center">

## 💙 Desarrollado con pasión por Jordan Negria Chiripua

**[⭐ Star este proyecto](https://github.com/jordannegria/Challenge-Telecom-X---Parte-2)** • **[🚀 Ejecutar en Colab](https://colab.research.google.com/drive/1dZR4UQkFRlTS7l4flv0ayyBiLTUMRe8y?usp=drive_link)**

---

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![ML](https://img.shields.io/badge/ML-Scikit--learn-orange)

**© 2025 Jordan Negria Chiripua | Todos los derechos reservados**
