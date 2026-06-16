
### AANALISIS DE DATOS  ANUAL - MUSEO 

Proyecto de análisis de datos desarrollado en Power BI enfocado en el monitoreo de indicadores operativos y experiencia del visitante dentro de un entorno educativo/cultural.

 ## 🎯 Objetivo 

Diseñar un dashboard ejecutivo que permita visualizar tendencias de asistencia, desempeño operativo y métricas clave para apoyar la toma de decisiones.

Comportamiento del Visitante: ¿Cuáles son los días de la semana o tipos de días (Tipo_Dia) con mayor afluencia? ¿Cómo se distribuye nuestro público (niños, adultos, maestros, INAPAM)?
Rendimiento Financiero: ¿Cuál es la principal fuente de ingresos (Ingreso_Boletaje, Tienda, Cafeteria) y cómo se correlacionan con el volumen de visitas?
Eficiencia Operativa: ¿Qué días o temporadas generan picos de asistencia que requieran planificar más personal o inventario?

## 🛠️ Herramientas Utilizadas
Power BI

## KPIs monitoreados
**Operativos** <b>
Total de Visitantes: SUM(Total_Visitantes)
Promedio Diario de Visitas: AVERAGE(Total_Visitantes)
Mix de Audiencia (%): Proporción de Niños, Adultos, Maestros e INAPAM sobre el total.
<b>
**Financieros**
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

***Principales insights***
Identificación de patrones de asistencia por temporada
Detección de horarios de mayor demanda
Visualización de tendencias operativas para optimización de recursos

<img width="829" height="466" alt="Captura99" src="https://github.com/user-attachments/assets/cf7d7fe1-2f99-4f33-8c5d-ac088d3c2645" />

<img width="828" height="461" alt="Captura99A" src="https://github.com/user-attachments/assets/d5106042-c23c-4b5d-9d2b-559884a50e71" />

## Comunicación con Stakeholders -(Método SCQA)
Estimada Dirección General,

SITUACIÓN
Durante 2025 el museo ha registrado más de 329,000 visitantes y $85 millones en ingresos totales, operando con información dispersa que dificultaba identificar patrones y tomar decisiones con agilidad.

COMPLICACIÓN
Sin una vista consolidada, era difícil responder preguntas clave en tiempo real: ¿qué tipo de día genera más valor?, ¿qué segmento de visitante mueve la demanda?, ¿estamos creciendo o repitiendo el mismo comportamiento cada año?

PREGUNTA
¿Cómo podemos convertir los datos operativos del museo en una herramienta que apoye decisiones estratégicas de forma inmediata?

RESPUESTA
Hemos desarrollado un Panel de Decisiones Operativas en Power BI, disponible a partir de hoy, que consolida en dos vistas los indicadores más relevantes:

• Overview ejecutivo — KPIs de afluencia e ingresos, tendencia mensual, composición de visitantes y comportamiento por tipo de día.
• Detalle analítico — Patrones semanales, evolución de segmentos y tabla de exploración por fecha.

Los primeros hallazgos son concretos: un día de vacaciones concentra el triple de visitantes que un día escolar, el ingreso por visitante se mantiene estable en ~$257 independientemente del volumen, y los niños representan 6 de cada 10 visitas.

Quedo disponible para agendar una sesión de walkthrough donde revisemos el dashboard juntos y definamos las preguntas prioritarias para la siguiente etapa.

Quedo a sus órdenes,

