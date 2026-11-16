
# Diseño de una infraestructura de red empresarial con VLAN

## 1. Descripción del proyecto

Este proyecto académico presenta una propuesta de diseño de infraestructura de red empresarial mediante segmentación lógica con VLAN, utilizando equipos Cisco y direccionamiento IPv4.

El propósito es organizar los dispositivos de una institución en diferentes segmentos de red, facilitar su administración y mejorar el control del tráfico.

## 2. Objetivo general

Diseñar una infraestructura de red jerárquica que permita segmentar los servicios y dispositivos mediante VLAN, considerando la conectividad, administración y escalabilidad.

## 3. Tecnologías y herramientas

- Cisco Packet Tracer.
- Switch multicapa Cisco Catalyst 3650-24PS.
- Switches Cisco 2950.
- VLAN y enlaces troncales IEEE 802.1Q.
- Direccionamiento IPv4.
- DHCP.
- Enrutamiento inter-VLAN.

## 4. Propuesta de segmentación

| VLAN | Área | Red propuesta |
|---|---|---|
| 10 | Administración | 192.168.10.0/24 |
| 20 | Docencia | 192.168.20.0/24 |
| 30 | Laboratorios | 192.168.30.0/24 |
| 40 | Cámaras IP | 192.168.40.0/24 |
| 50 | Puntos de acceso | 192.168.50.0/24 |
| 60 | Televisión | 192.168.60.0/24 |

## 5. Arquitectura propuesta

La infraestructura contempla un switch multicapa como núcleo de la red y switches de acceso para conectar los diferentes dispositivos.

Los enlaces troncales permiten transportar el tráfico de las VLAN configuradas. El enrutamiento inter-VLAN se plantea en el equipo de capa 3 y DHCP permite la asignación dinámica de direcciones IP.

## 6. Resultados esperados

- Segmentación lógica de los dispositivos.
- Organización del tráfico por áreas.
- Administración centralizada de la infraestructura.
- Comunicación controlada entre VLAN.
- Facilidad de crecimiento y mantenimiento.

## 7. Conclusión

La segmentación mediante VLAN constituye una alternativa para organizar redes empresariales, mejorar su administración y establecer una estructura escalable. El diseño propuesto permite comprender la función de los switches multicapa, los enlaces troncales y los servicios de direccionamiento IP en una infraestructura de red.

## 8. Recurso gráfico

El repositorio incluye una ilustración conceptual de la topología propuesta. Esta imagen representa el diseño lógico y no constituye evidencia de una simulación ejecutada.
