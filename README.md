# 📱 Análisis de Tarifas de Megaline

Este proyecto analiza los datos de clientes del operador de telecomunicaciones **Megaline**, el cual ofrece dos planes de prepago: **Surf** y **Ultimate**. El objetivo principal es identificar **cuál de los dos planes genera mayores ingresos mensuales promedio**, y ofrecer recomendaciones estratégicas para el área comercial y de marketing.

---

## 🧠 Objetivo del proyecto

- Analizar el comportamiento mensual de 500 clientes: llamadas, mensajes de texto y uso de internet.
- Calcular los ingresos mensuales por cliente según la tarifa contratada.
- Comparar ingresos promedio entre tarifas mediante pruebas estadísticas.
- Evaluar diferencias de ingresos por ubicación geográfica (Nueva York/Nueva Jersey vs otras regiones).

---

## 🗂️ Datos utilizados

El análisis se basa en cinco tablas:

1. **users** → Datos personales y plan contratado de cada cliente.
2. **calls** → Registro de llamadas por usuario y duración.
3. **messages** → Envío de mensajes de texto por usuario.
4. **internet** → Consumo de datos en MB por sesión y mes.
5. **plans** → Descripción y precios de las tarifas Surf y Ultimate.

---

## 🔍 Principales tareas realizadas

### 🔧 Preparación de datos
- Conversión de tipos de datos y tratamiento de valores ausentes
- Cálculo mensual por cliente: minutos usados, mensajes enviados y GB consumidos
- Cálculo de ingresos por cliente según las condiciones de cada tarifa

### 📊 Análisis exploratorio
- Distribución de consumo mensual por tipo de plan
- Cálculo de estadísticas descriptivas (media, varianza, desviación estándar)
- Visualización mediante histogramas

### 📈 Pruebas estadísticas
- **Hipótesis 1:** El ingreso promedio es distinto entre Surf y Ultimate
- **Hipótesis 2:** El ingreso promedio es diferente en NY/NJ vs otras regiones
- Se utilizó la prueba de hipótesis para medias (test de Student)

---

## 🧰 Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scipy.stats (pruebas estadísticas)
- Jupyter Notebook

---

## 📌 Conclusiones generales
Se identificaron diferencias significativas en los ingresos promedio entre tarifas y por región, lo que permite **optimizar estrategias de promoción y segmentación de clientes** para Megaline.

---

## 👨🏻‍💻 Autor
Julio Hernández Tejeida
*Business Analyst en formación con enfoque en datos, visualización y análisis estratégico*
