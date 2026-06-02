
### VISITOR & OPERATIONS ANALYTICS DASHBOARD 

Proyecto de análisis de datos desarrollado en Power BI enfocado en el monitoreo de indicadores operativos y experiencia del visitante dentro de un entorno educativo/cultural.

 ## 🎯 Objetivo 

Diseñar un dashboard ejecutivo que permita visualizar tendencias de asistencia, desempeño operativo y métricas clave para apoyar la toma de decisiones.

Comportamiento del Visitante: ¿Cuáles son los días de la semana o tipos de días (Tipo_Dia) con mayor afluencia? ¿Cómo se distribuye nuestro público (niños, adultos, maestros, INAPAM)?
Rendimiento Financiero: ¿Cuál es la principal fuente de ingresos (Ingreso_Boletaje, Tienda, Cafeteria) y cómo se correlacionan con el volumen de visitas?
Eficiencia Operativa: ¿Qué días o temporadas generan picos de asistencia que requieran planificar más personal o inventario?

## 🛠️ Herramientas Utilizadas
Power BI
Excel
SQL
Power Query

## KPIs monitoreados
OperativosTotal de Visitantes: SUM(Total_Visitantes)
Promedio Diario de Visitas: AVERAGE(Total_Visitantes)
Mix de Audiencia (%): Proporción de Niños, Adultos, Maestros e INAPAM sobre el total.

Financieros
Ingreso Total: SUM(Ingreso_Total)
Ticket Promedio por Visitante: Un ratio crucial para medir el gasto de los usuarios.
Gasto Promedio por Categoría: Desglose del ticket promedio en Boletaje, Tienda y Cafetería para entender el comportamiento de consumo.




## Proceso realizado
Conexión y Limpieza de Datos (Power Query)
- Limpieza y transformación de datos
- Validación de Calidad
- Modelado de Datos y Tabla de Tiempos
- Creación de métricas en DAX
- Diseño de dashboard ejecutivo
- Generación de insights para toma de decisiones

Principales insights
Identificación de patrones de asistencia por temporada
Detección de horarios de mayor demanda
Visualización de tendencias operativas para optimización de recursos

(Inserta aquí capturas del dashboard)


📁 Estructura del Repositorio
data/: Contiene los datasets originales (o enlaces a las fuentes).

notebooks/: Jupyter Notebooks con el proceso de limpieza y análisis.

visuals/: Gráficos de barras, histogramas y boxplot generados.


## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/vestrada-data/Project_NovaRetail/blob/main/.ipynb)

Sobre mí

Ingeniera en Computación con experiencia en análisis operativo, KPIs y mejora de procesos. Actualmente fortaleciendo habilidades en Data Analytics y Business Intelligence.


