# Telco Comunicaciones

________________________________________
🔹 Contexto
Empresa de telecomunicaciones que enfrenta una tasa significativa de churn (cancelación de clientes), lo que impacta directamente en los ingresos recurrentes y en los costos de adquisición de nuevos clientes.
Este proyecto simula un escenario real de negocio donde el equipo de datos debe identificar patrones de abandono y segmentos de alto riesgo para apoyar la toma de decisiones.
________________________________________
🎯 Objetivo
Analizar el churn de clientes para:
•	Identificar los segmentos con mayor probabilidad de baja
•	Comprender los factores asociados al churn
•	Cuantificar el impacto económico de la pérdida de clientes
•	Proveer insights accionables para estrategias de retención
________________________________________
🧠 Metodología
•	Exploración y limpieza de datos utilizando SQL Server
•	Análisis descriptivo de variables clave (contrato, método de pago, antigüedad)
•	Definición de KPIs orientados a negocio
•	Modelado y visualización de datos en Power BI
•	Enfoque analítico orientado a la toma de decisiones
________________________________________
📊 KPIs Analizados
•	Churn Rate (%)
•	Clientes dados de baja
•	Ingreso mensual estimado perdido
•	Churn por tipo de contrato
•	Churn por método de pago
•	Churn por antigüedad del cliente
________________________________________
🛠️ Tecnologías
•	SQL Server (SSMS) – limpieza y análisis de datos
•	Power BI Desktop & Service – modelado, visualización y publicación
•	DAX – cálculo de métricas y KPIs
________________________________________
📈 Dashboard
El dashboard presenta una vista ejecutiva e interactiva del churn, permitiendo filtrar por variables clave y analizar el impacto económico en tiempo real.
 
________________________________________
🏁 Conclusiones
•	El churn se concentra principalmente en clientes con contratos mensuales y baja antigüedad, lo que indica que la pérdida ocurre en etapas tempranas del ciclo de vida.
•	Existe una ventana crítica durante los primeros meses, donde una activación y acompañamiento insuficientes incrementan la probabilidad de cancelación.
•	Algunos métodos de pago presentan tasas de churn más elevadas, lo que sugiere fricción operativa o fallas en el proceso de cobro.
•	El impacto económico del churn es relevante y afecta directamente los ingresos recurrentes, justificando la implementación de acciones preventivas y segmentadas orientadas a retención.
________________________________________
💰 Estimación de Impacto Económico de las Acciones
La siguiente estimación tiene como objetivo dimensionar el impacto económico potencial de distintas acciones de retención, utilizando valores reales del dataset y supuestos conservadores. No busca predecir resultados exactos, sino priorizar iniciativas desde una perspectiva de negocio.
📌 Base de cálculo
•	Clientes totales analizados: ~7.000
•	Churn total del período: 25% (≈ 1.750 clientes)
•	Período analizado: 72 meses
•	Ingreso promedio mensual por cliente (ARPU): $70
________________________________________
🔹 Acción 1: Estrategia de retención temprana (primer año)
El análisis por antigüedad muestra que el 11,27% del churn ocurre durante el primer año de relación con el cliente, lo que representa aproximadamente 197 clientes.
Considerando estrategias de onboarding, contacto proactivo y beneficios iniciales, se asume de forma conservadora una reducción del 10% del churn en este segmento.
•	Clientes potencialmente retenidos: ≈ 20
•	Impacto económico estimado: $1.400
________________________________________
🔹 Acción 2: Optimización del método de pago (Electronic Check)
El método de pago Electronic Check concentra el 45,29% del churn, equivalente a aproximadamente 793 clientes. Este patrón sugiere fricción operativa y churn involuntario.
Dado que se trata de una causa mayormente operativa, se asume una reducción conservadora del 15% del churn en este segmento mediante incentivos al cambio de método y mejoras en el proceso de cobro.
•	Clientes potencialmente retenidos: ≈ 119
•	Impacto económico estimado: $8.330
________________________________________
🔹 Acción 3: Incentivo a métodos de pago automáticos
Los métodos de pago automáticos (transferencia bancaria y tarjeta de crédito) concentran en conjunto 31,85% del churn (≈ 557 clientes), con tasas de abandono más bajas.
Dado el menor margen de mejora, se asume una reducción incremental del 5% del churn en este segmento.
•	Clientes potencialmente retenidos: ≈ 28
•	Impacto económico estimado: $1.960
________________________________________
📊 Impacto económico total estimado
De manera agregada, las acciones propuestas permitirían retener aproximadamente 167 clientes, lo que representa un impacto económico estimado de $11.690 x mes
Esta estimación equivale a una reducción aproximada del 9,5% del churn total, lograda mediante mejoras focalizadas y realistas sobre los principales segmentos de riesgo.

