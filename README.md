# 📱 ConnectaTel Customer Analysis

## 📌 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel mediante técnicas de limpieza, exploración y análisis de datos. Se busca identificar patrones de uso, segmentar a los usuarios según su comportamiento y generar recomendaciones de negocio que ayuden a mejorar la oferta de planes y la estrategia comercial de la empresa.

---

## 📂 Datasets utilizados

El análisis se realizó utilizando dos conjuntos de datos:

* **users.csv**

  * Información demográfica de los clientes.
  * Variables como edad, tipo de plan y user_id.

* **usage.csv**

  * Historial de uso de los clientes.
  * Incluye llamadas, mensajes, duración de llamadas y longitud de mensajes.

---

## 🛠️ Etapas del análisis

El proyecto se desarrolló siguiendo las siguientes fases:

1. Carga y exploración de los datos.
2. Evaluación de calidad de datos.
3. Identificación y tratamiento de valores ausentes.
4. Verificación de valores faltantes dependientes del tipo de servicio (MAR).
5. Corrección de fechas imposibles y revisión de inconsistencias.
6. Creación de métricas agregadas por usuario.
7. Análisis estadístico descriptivo.
8. Visualización de distribuciones mediante histogramas.
9. Identificación de valores atípicos utilizando Boxplots e IQR.
10. Segmentación de clientes por nivel de uso y grupo de edad.
11. Elaboración de un análisis ejecutivo con recomendaciones para el negocio.

---

## 📊 Principales herramientas utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## ▶️ Cómo ejecutar el proyecto

1. Clona este repositorio o descárgalo.
2. Abre el archivo `.ipynb` utilizando Google Colab o Jupyter Notebook.
3. Verifica que los archivos `users.csv` y `usage.csv` se encuentren en la misma carpeta o actualiza la ruta de lectura de los datos.
4. Ejecuta las celdas en orden para reproducir completamente el análisis.

---

## 📈 Resultados

Durante el análisis se identificaron patrones de comportamiento asociados al uso de llamadas y mensajes, así como diferencias entre los distintos tipos de usuarios. También se detectaron valores atípicos correspondientes a clientes de alto consumo que representan oportunidades para estrategias de fidelización y actualización de planes.

La segmentación permitió clasificar a los clientes por edad y nivel de uso, proporcionando información útil para el diseño de nuevos planes y campañas comerciales más personalizadas.

---

## 📁 Estructura del repositorio

```
connectatel-customer-analysis/
│
├── notebooks/
│   └── connectatel_analysis.ipynb
│
├── data/
│   ├── users.csv
│   └── usage.csv
│
└── README.md
```

---

## 👨‍💻 Autor

**Luis Carlos Rodríguez de la Fuente**

Bootcamp de Data Analytics – TripleTen

GitHub: https://github.com/LCRodriguez-DATA
      
