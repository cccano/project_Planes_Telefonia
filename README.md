# Comportamiento del uso de planes de telefonia
Análisis del comportamiento de usuarios por segemento de edad y nivel de uso de los planes de telefonia

**Objetivo**

Identificar patrones de uso, comportamientos atípicos y comprender que segmentos de clientes muestran necesidades diferenciales.

**Datasets Utilizados**

- plans.csv : planes actuales, precios de planes y minutos, GB incluidos y costos extras.
- users_latam.csv : información de los clientes, como edad, ciudad, planes, fechas de registro.
- usage.csv : detalle de uso real en llamadas y mensajes.

**Etapas de Análsis**

- Exploración y estructura de datesets.
- Identificación de problemas de calidad de los datos.
- Detección de valores invalidos y sentinels.
- Estandarización de fechas.
- Limpieza básica de datos.
- Corregir sentinels y fechas imposibles.
- Resumenes estadistico.
- Visualización de distribución e identificación de outliers.
- Segmentación de clientes por edad y nivel de uso.
- Insights 

**Como ejecutar el notebook**

Desde el siguiente boton dando clic para ir al notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cccano/sprint7-final-project/blob/main/Proyect_Telecom_S7.ipynb)

**Guia de reproducción**

Descarga los achivos csv y cargarlos en colab.

Dirígete al menú lateral izquierdo de tu Google Colab y haz clic en el ícono de Carpeta (Archivos).

Haz clic en el primer ícono de arriba que dice "Subir al almacenamiento de sesiones" (representado con una pequeña carpeta y una flecha hacia arriba).

Selecciona tu archivo desde tu PC.

Una vez cargado en la lista, haz clic derecho sobre el nombre del archivo, selecciona "Copiar ruta" (Copy path) y pégala dentro de tu función de Pandas

