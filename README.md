## 🎯 Objetivo del proyecto:

Identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.


## 🗂️ Fuentes de datos:

1. plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

2. users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.

3. usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).


## 🔍 Las etapas del análisis realizadas:

1. Cargar y explorar los tres datasets.

2. Identificar los problemas de calidad de los datos.

3. Detectar valores invalidos o sentinels.

4. Revisar y estandarizar fechas.

5. Limpiar datos.

6. Resumen estadístico.

7. Visualizar distribuciones.

8. Segmentar clientes.

9. Insight ejecutivo.



 ## 🚀 Cómo ejecutar el notebook 
 
#### ⚙️ Abrir en Google Colab:

1. Ve al archivo `.ipynb` dentro de este repositorio. 📓 [Ver notebook del análisis](telecom-analysis.ipynb)
  
2. Haz clic en el botón **"Open in Colab"** (o copia la URL del notebook y pégala en [https://colab.research.google.com](https://colab.research.google.com) → pestaña "GitHub").
   
3. Una vez abierto, ejecuta las celdas en orden desde el menú **Runtime > Run all**.

> No necesitas instalar Python ni librerías localmente; Colab ya las incluye.



## 📋 Guía de reproducción:

1. Asegúrate de tener los datasets (`plans.csv`, `users_latam.csv`, `usage.csv`) en la misma carpeta que el notebook, o en la ruta indicada dentro del código.
   
2. Ejecuta las celdas **en orden secuencial**, ya que algunas dependen de variables o transformaciones definidas en pasos anteriores (por ejemplo, la limpieza de `NaT` y sentinels debe correr antes del análisis de segmentos).
   
3. Los resultados principales (segmentación por edad, nivel de uso, y detección de outliers) se generan automáticamente al final del notebook.
