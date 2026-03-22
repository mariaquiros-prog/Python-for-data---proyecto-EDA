# Python-for-data---proyecto-EDA
Pasos realizados:
Importación y Concat: Consolidación de tres fuentes de clientes (2012-2014) y unión maestra (merge) con la base de datos del banco mediante el identificador único id_.
Limpieza de Datos: Tratamiento de nulos en ingresos y edad mediante imputación estadística (mediana y media) y normalización de textos en minúsculas.
Feature Engineering: Creación de la variable total_minors combinando datos de niños y adolescentes para analizar el impacto de la carga familiar.
Análisis Exploratorio: Ejecución de agrupamientos (groupby) y segmentación para identificar patrones de éxito en la suscripción de productos.

Informe de Análisis:
Perfil de Ingresos: El nivel económico promedio varía significativamente por profesión, siendo los roles de gestión y técnicos los de mayor capacidad financiera.
Tasa de Éxito: Se ha detectado que los estudiantes y jubilados tienen la mayor disposición a contratar el producto, superando el 25% de efectividad.
Eficacia de Campaña: Existe una correlación negativa entre el número de contactos (campaign) y el éxito; contactar demasiadas veces al mismo cliente reduce la probabilidad de conversión.
Carga Familiar: La mayoría de los clientes tienen al menos un menor a su cargo, lo que influye directamente en su comportamiento de ahorro y visitas web.
Visualización: El análisis gráfico confirma que las profesiones con menor tasa de éxito (como operarios) requieren un cambio de estrategia o una oferta de producto más ajustada.
