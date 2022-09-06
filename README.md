# BikeRegister

En Los Ángeles existe un sistema compartido de bicicletas que brinda datos anónimos acerca
del uso del servicio. La tabla que se proporciona contiene el histórico de viajes que se han
realizado desde 2016 y contiene una columna que es de particular interés y que se buscará
analizar a más profundidad: Passholder_type. A continuación se presentan las columnas
que contiene la tabla:
- trip_id: identificador único para el viaje
- duration: duración del viaje en minutos
- start_time: dia/hora donde en viaje inicia en formato ISO 8601 tiempo local
- end_time: dia/hora donde el viaje termina en formato ISO 8601 tiempo local
- start_station: la estación donde el viaje inició
- start_lat: la latitud de la estación donde el viaje se originó
- start_lon: la longitud de la estación donde el viaje se originó
- end_station: la estación donde el viaje terminó
- end_lat: la latitud de la estación donde terminó el viaje
- end_lon: la longitud de la estación donde terminó el viaje
- bike_id: un entero único que identifica la bicicleta
- plan_duration: número de días que el usuario tendrá el paso. 0 significa un viaje único
(Walk-up plan)
- trip_route_category: “Round trip” son viajes que empiezan y terminan en la misma
estación
- passholder_type: El nombre del plan de passholder
Tareas a realizar:
1) Exploratorio de datos: Para comenzar la asignación se requiere realizar un análisis
exploratorio de datos que busque contestar preguntas relevantes a los siguientes dos
temas:
- Saturación del servicio: La empresa busca contar con la disponibilidad más alta
de servicio en el mercado, por lo que se quiere entender cómo se comporta la
demanda de servicio en las distintas estaciones y horarios para cada plan
- Crecimiento de planes: Se tiene la intuición que la tendencia en uso de
bicicletas compartidas entre estaciones va a la alta, por lo que se requiere
realizar una correcta planificación de bicicletas que deben tener.
Adicionalmente, se espera que los planes de consumo anual crezcan en mayor
proporción.

2) Modelo analítico: Se desea saber si es posible inferir el tipo de pase tomando en
cuenta las demás variables de viaje.
- Construya un modelo analítico que incluya los puntos indispensables a
considerar para un modelo (feature engineering, diseño de train-test split,
cross-validation, métricas de desempeño, entre otros)
- Interprete el resultado en contexto del problema y determine qué variables
impactan en la predicción
- Tomando en cuenta los exploratorios y el modelo analítico, ¿cree que es un
buen modelo? ¿Qué variables adicionales añadiría para mejorar el modelo?
