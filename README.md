# Development of an Integrated Apiary Telemetry System
Bachelor's thesis for the Electronics Engineering degree at the University of West Attica (UNIWA).

## Abstract
<div align="justify">
  This thesis focuses on the development of an integrated beekeeping telemetry system that enables
  continuous monitoring of critical hive parameters such as weight, temperature, and humidity. The
  system is based on Internet of Things technologies and employs sensors to collect data, which is
  transmitted via an NB-IoT network to a central data storage and analysis infrastructure.
  The system architecture includes a Microchip SAM D21 microcontroller that gathers measurements
  and publishes them to an MQTT broker. The data is then forwarded via Apache Kafka, where it is
  processed and stored in an Apache IoTDB database. The system supports data visualisation through
  Grafana, providing beekeepers with a comprehensive view of their apiary's status.
  Special attention was given to optimising data storage using compression and encoding techniques,
  as well as ensuring data security through digital signatures. Additionally, a cost analysis demonstrated
  that the proposed solution is up to twenty-one times more cost-effective than commercial alternatives,
  as it eliminates subscription fees and high communication costs.
  In conclusion, the proposed implementation offers a flexible and low-cost telemetry system that can
  be expanded and adapted to the beekeeper's needs, contributing to improved productivity and hive
  management.
</div>

## Keywords
Precision Beekeeping, Telemetry, Internet of Things, MQTT, Apache Kafka, Apache IoTDB,
NB-IoT, Grafana, Sensors, Data analysis.
