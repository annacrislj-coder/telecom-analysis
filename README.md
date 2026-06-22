# Telecom-analysis - Sprint 7

## 🧠 Objetivo del análisis: 
Identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

## 📂 Usamos 3 dataset para este análisis
-plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

-users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.

-usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

## Camino de análisis:
Cargar datasets → Explorar → Detectar problemas → Limpiar → Calcular estadísticas → Visualizar → Detectar outliers → Segmentar → Generar insights

## Para ejecutar el Notebook
▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:
[![Open In Colab](https://colab.research.google.com/drive/1LNRdLEenG3qdzmoM1hKSY0iEaqAPnLrN)]](URL_DEL_NOTEBOOK_EN_GITHUB)

O:
1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**
## 📘 Cómo reproducir el análisis
1. Abre `notebooks/telecom_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## Preguntas clave
-¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?

-¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?

-¿Cómo varía el uso según la edad y el tipo de plan contratado?

-¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

