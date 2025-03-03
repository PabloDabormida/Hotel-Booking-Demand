# Hotel-Booking-Demand

🇬🇧 **This project is available in [English](README.md)**  

## Resumen

Este artículo de datos describe dos conjuntos de datos de demanda hotelera. Uno de los hoteles (H1) es un hotel resort y el otro es un hotel urbano (H2). Ambos conjuntos de datos comparten la misma estructura, con 31 variables que describen las 40.060 observaciones de H1 y las 79.330 observaciones de H2. Cada observación representa una reserva de hotel. Ambos conjuntos de datos comprenden reservas previstas entre el 1 de julio de 2015 y el 31 de agosto de 2017, incluidas las reservas que efectivamente llegaron y las reservas que se cancelaron.

Dado que se trata de datos reales de hoteles, se eliminaron todos los elementos de datos relacionados con la identificación del hotel o del cliente. Debido a la escasez de datos comerciales reales con fines científicos y educativos, estos conjuntos de datos pueden tener un papel importante para la investigación y la educación en gestión de ingresos, Machine Learning o minería de datos, así como en otros campos.

🔗 Fuente Original: https://www.researchgate.net/publication/329286343_Hotel_booking_demand_datasets

## Valor de los datos
• La analítica descriptiva se puede emplear para comprender mejor los patrones, tendencias y anomalías en los datos;

• Se utiliza para realizar investigaciones en diferentes problemas como: predicción de cancelaciones de reservas, segmentación de clientes, satisfacción del cliente, estacionalidad, entre otros;

• Los investigadores pueden utilizar los conjuntos de datos para comparar los modelos de predicción de cancelaciones de reservas con resultados ya conocidos;

• Los investigadores en aprendizaje automático pueden usar los conjuntos de datos para evaluar el rendimiento de diferentes algoritmos para resolver el mismo tipo de problema (clasificación, segmentación u otros);

• Los educadores pueden utilizar los conjuntos de datos para problemas de clasificación o segmentación en aprendizaje automático;

• Los educadores pueden utilizar los conjuntos de datos para obtener formación en estadísticas o minería de datos.

## Objetivos
El objetivo principal de este análisis de datos hotelero es ofrecer una visión integral y profunda de las operaciones y el desempeño financiero de dos hoteles a través de tres dashboards específicos. Se busca identificar patrones clave, optimizar la toma de decisiones estratégicas y mejorar la eficiencia operativa del negocio. Los objetivos específicos son los siguientes:

 **•** Analizar la estacionalidad y la tasa de ocupación de los hoteles, identificando picos y valles en la demanda, así como las fluctuaciones relacionadas con temporadas altas, eventos locales y días de la semana.
 
 **•** Evaluar la rentabilidad de los hoteles a través de métricas como ADR (Average Daily Rate) y RevPAR (Revenue per Available Room), proporcionando un análisis claro sobre los ingresos generados por habitación ocupada y por habitación disponible.
 
 **•** Monitorear el comportamiento de las reservas y cancelaciones, identificando patrones según tipo de cliente, canal de reserva y temporada, con el fin de optimizar la gestión de inventarios y minimizar las pérdidas asociadas.
 
 **•** Segmentar y analizar a los clientes según su perfil y preferencias, detectando las características de habitación más demandadas, la duración promedio de las estancias y la tasa de repetición para mejorar la oferta y la experiencia del cliente.
 
 **•** Evaluar la eficiencia operativa de los hoteles, identificando áreas de mejora en la utilización de recursos, el manejo de la capacidad y la capacidad de respuesta frente a variaciones en la demanda.
 
 **•** Analizar la elasticidad de precios y el impacto de descuentos y promociones en las reservas, optimizando la estrategia de precios para maximizar ingresos sin sacrificar ocupación.
 
 **•** Ofrecer un análisis comparativo de los ingresos y pérdidas, incluyendo la identificación de fuentes de ingresos netos y la relación entre ingresos efectivos e ingresos totales.
 
 **•** Monitorear los principales KPIs hoteleros a lo largo del tiempo para evaluar el desempeño y la competitividad del hotel frente al mercado.

Este análisis tiene como finalidad proporcionar una herramienta visual clara y accesible que permita a los responsables hoteleros tomar decisiones fundamentadas para mejorar la eficiencia operativa, aumentar los ingresos y minimizar las pérdidas, maximizando así la rentabilidad de ambos hoteles.

## Descripción del Proyecto

Este proyecto de análisis de datos hotelero se centra en evaluar y optimizar el rendimiento de dos hoteles (Resort Hotel y City Hotel) mediante el uso de herramientas de visualización en Tableau. El análisis se realizó a través de tres dashboards principales, diseñados para proporcionar una visión clara y detallada de los aspectos más relevantes de la operación hotelera.

  **• Dashboard de Reservas y Cancelaciones:** Enfocado en analizar el comportamiento de las reservas, las tasas de cancelación y los patrones de no-show. Aquí se estudian las tendencias en las reservas a lo largo del tiempo, permitiendo identificar períodos de alta y baja demanda, así como posibles factores que influyen en la cancelación de reservas.
  
  **• Dashboard de Ingresos y Pérdidas:** Este dashboard ofrece una visión detallada sobre los ingresos generados, pérdidas por cancelaciones y la relación entre tarifas aplicadas (ADR) y la ocupación de las habitaciones. También permite identificar las fuentes principales de ingresos y las variaciones en la rentabilidad según los diferentes períodos y segmentos de clientes.
  
  **• Dashboard General y KPIs:** Proporciona una vista general de los principales indicadores de rendimiento del hotel, incluyendo la tasa de ocupación, ingresos totales, tasa de cancelaciones y ADR. Este panel tiene como objetivo ofrecer una visión global del desempeño del hotel en un solo lugar, facilitando la comparación de KPIs clave a lo largo del tiempo.

A lo largo de este proyecto, se han utilizado diversas técnicas analíticas para descomponer los datos en segmentos de valor y extraer patrones que puedan guiar la toma de decisiones. Esto incluye el análisis de estacionalidad, segmentación de clientes y evaluación de la eficiencia operativa de cada hotel. El resultado final es una herramienta que permite a los gestores hoteleros comprender mejor su operación y tomar decisiones basadas en datos para mejorar la rentabilidad y la satisfacción del cliente.

## Conclusiones

El análisis de datos realizado sobre las operaciones de los dos hoteles (Resort Hotel y City Hotel) ha permitido identificar varias tendencias clave que afectan tanto a la rentabilidad como a la eficiencia operativa. A través de los tres dashboards implementados, se destacaron los siguientes puntos:

 **•** Estacionalidad y Demanda: Se observan patrones claros de estacionalidad que impactan directamente en la tasa de ocupación y en la demanda general de reservas. Los meses de alta y baja ocupación han sido identificados con precisión, lo que permite anticipar la demanda de manera más efectiva.
Aprovechando esto, los hoteles podrían implementar una política de precios dinámicos para ajustar las tarifas en función de la demanda proyectada. Durante los períodos de baja ocupación, se podrían ofrecer descuentos o paquetes promocionales que atraigan a más clientes, maximizando el RevPar.

 **•** Cancelaciones y No-Show: Los datos revelan una tasa considerable de cancelaciones, especialmente en determinadas épocas del año, lo que afecta negativamente los ingresos potenciales. El análisis de cancelaciones y no-show muestra la necesidad de revisar las políticas de cancelación, así como de incentivar la confirmación anticipada de reservas.
 Es recomendable revisar y endurecer las políticas de cancelación o implementar incentivos para que los clientes mantengan sus reservas, como descuentos por pago anticipado o penalizaciones más estrictas por cancelaciones de último minuto.

 **•** Ingresos y Rentabilidad: El análisis detallado de los ingresos indica que el ADR (tarifa promedio diaria) tiene una influencia significativa sobre el RevPAR (ingreso por habitación disponible). Se detectaron fluctuaciones en las tarifas a lo largo del tiempo, sugiriendo oportunidades de optimización, especialmente en los períodos de baja ocupación.
Durante los períodos de baja demanda, se pueden implementar estrategias de ajustes en la gestión de recursos para optimizar costos. Además, la mejora de la comunicación con los clientes para reducir los no-shows podría tener un impacto positivo en la ocupación y los ingresos.

 **•** Segmentación de Clientes: La segmentación reveló que ciertos grupos de clientes generan mayor rentabilidad que otros, lo que abre la posibilidad de ajustar las estrategias de marketing y fidelización para centrarse en esos segmentos clave.
Los hoteles deberían centrarse en fidelizar a los clientes más rentables, utilizando los datos para personalizar ofertas, mejorar la experiencia del cliente e incrementar la lealtad, lo que a largo plazo aumentará la rentabilidad.

Además, se podrían utilizar los patrones de estacionalidad identificados para lanzar campañas de marketing dirigidas, orientadas a incrementar la ocupación en los meses de menor demanda y aprovechar los picos de alta demanda para maximizar los ingresos.
Estas acciones permitirán mejorar la retención, incrementar la rentabilidad y ofrecer una experiencia más ajustada a las necesidades de los clientes, basadas en datos y patrones objetivos.

## Glosario

**• hotel:** Tipo de Hotel. **Notas:** Resort Hotel - City Hotel.<br> 
**• is_canceled:** Valor que indica si la reserva fue cancelada. **Notas:** (1) Cancelada - (0) No Cancelada.<br> 
**• lead_time:** Número de días transcurridos entre la fecha de entrada de la reserva y la fecha de llegada.<br> 
**• arrival_date_year:**  Año de la Fecha de Llegada.<br> 
**• arrival_date_month:**  Mes de la Fecha de Lelegada (12 categorias). **Notas:** “January” a “December”.<br>
**• arrival_date_week_number:** Numero de Semana de la Fecha de Llegada.<br> 
**• arrival_date_day_of_month:** Dia del mes de la Fecha de Llegada.<br> 
**• stays_in_weekend_nights:**  Número de noches de fin de semana (sábado o domingo) que el huésped se alojó o reservó para alojarse en el hotel.<br> 
**• stays_in_week_nights:** Número de noches de la semana (de lunes a viernes) que el huésped se alojó o reservó para alojarse en el hotel.<br> 
**• adults:** Cantidad de Adultos.<br> 
**• children:** Cantidad de Niños.<br> 
**• babies:** Cantidad de Bebes.<br> 
**• meal:** Tipo de comida reservada. Las categorías se presentan en paquetes de comidas. **Notas:** Indefinida / SC - sin paquete de comida. BB – Bed & Breakfast. HB – Media pensión (desayuno y otra comida, normalmente la cena). FB – - Pensión completa (desayuno, almuerzo y cena).<br> 
**• country:** País de origen. Las categorías se representan en el formato ISO 3155–3:2013.<br> 
**• market_segment:** Designación de segmento de mercado. **Notas:** “TA” = “Agentes de Viajes”. “TO” = “Operadoras Turísticas”.<br>
**• distribution_channel:** Canal de distribución de reservas. **Notas:** “TA” = “Agentes de viajes”. "TO" = "Tour Operadores".<br>
**• is_repeated_guest:** Valor que indica si el nombre de la reserva era de un huésped repetido. **Notas:** (1) is repeated - (0) is not repeated.<br>
**• previous_cancellations:** Número de reservas anteriores que fueron canceladas por el cliente antes de la reserva actual.<br> 
**• previous_bookings_not_canceled:** Número de reservas anteriores "no canceladas" por el cliente antes de la reserva actual.<br> 
**• reserved_room_type:**  Código del tipo de habitación reservada. Se presenta el código en lugar de la designación por razones de anonimato.<br>
**• assigned_room_type:** Código del tipo de habitación asignada a la reserva. En ocasiones, el tipo de habitación asignada difiere del tipo de habitación reservada debido a razones operativas del hotel. Se presenta un código en lugar de la designación por razones de anonimato.<br>
**• booking_changes:** Número de cambios/modificaciones realizadas en la reserva desde el momento en que se introdujo la reserva hasta el momento del check-in o cancelación.<br> 
**• deposit_type:** Indicación de si el cliente realizó un depósito para garantizar la reserva. Esta variable puede asumir tres categorías. **Notas:** No Deposit – no se realizó ningún depósito - Non Refund – se realizó un depósito por el valor total de la estadía - Refundable –se realizó un depósito con un valor inferior al costo total de la estadía.<br> 
**• agent:** Identificación de la agencia de viajes que realizó la reserva.<br> 
**• company:** Identificación de la empresa/entidad que realizó la reserva o responsable del pago de la reserva. Notas: Se presenta el ID en lugar de designación por razones de anonimato.<br>
**• days_in_waiting_list:** Número de días que la reserva estuvo en lista de espera antes de ser confirmada al cliente.<br> 
**• customer_type:** Tipo de reserva, suponiendo una de cuatro categorías. Notas: Contract - cuando la reserva tiene un cupo u otro tipo de contrato asociado. Group – cuando la reserva está asociada a un grupo.<br> Transient – cuando la reserva no forma parte de un grupo o contrato y no está asociada a otra reserva transitoria. Transient-party –cuando la reserva es transitoria, pero está asociada al menos a otra reserva transitoria. adr: Average Daily Rate (Tarifa diaria promedio).<br> 
**• required_car_parking_spaces:** Número de plazas de aparcamiento solicitadas por el cliente.<br> 
**• total_of_special_requests:** Número de peticiones especiales realizadas por el cliente (por ejemplo, dos camas individuales o piso alto).<br> 
**• reservation_status**: Último estado de la reserva, asumiendo una de tres categorías. Notas: Canceled – la reserva fue cancelada por el cliente. Check-Out – el cliente ha realizado el check-in pero ya se fue. No-Show – el cliente no realizo el Check-in y no informó al hotel el motivo.<br>
**• reservation_status_date:** Fecha en la que se estableció la ultima actualizacion de estado. Esta variable se puede utilizar junto con ReservationStatus para comprender cuándo se canceló la reserva o cuándo el cliente abandonó el hotel.
