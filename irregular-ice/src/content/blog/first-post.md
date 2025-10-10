---
title: 'Sucursal - Puno'
description: 'Por ultimo la sucursal de Puno, ubicada en la ciudad de Puno, es responsable de atender a nuestros clientes en la región sur del país.'
pubDate: 'Oct 6 2025'
heroImage: '../../assets/Puno.jpg'
---

### Topología Física y Lógica de la red (Puno)

![alt text](../../../public/Puno-Sede.png)

##### Nombre: Sucursal 4 - Puno
##### Dirección IP: 172.21.55.0/22

| Unidad Organizacional | Nombre de la VLAN | VLAN ID (VID) | Requisitos para host actuales | Requisitos para host actuales (20%) | Longitud de prefijo (LP) |
|-----------------------|-------------------|---------------:|-------------------------------:|------------------------------------:|-------------------------:|
| Ventas                | VENTAS            |             10 |                             48 |                               57.6 | /26                      |
| Administracion        | ADMINISTRACION    |             20 |                             24 |                               28.8 | /27                      |
| Finanzas              | FINANZAS          |             30 |                             10 |                               12.0 | /28                      |
| Wifi-Ejecutivos       | WIFI-EJECUTIVO    |             40 |                              8 |                                9.6 | /28                      |
| Marketing             | MARKETING         |             50 |                              7 |                                8.4 | /28                      |
| Logistica             | LOGISTICA         |             60 |                              6 |                                7.2 | /29                      |
| Nativa                | NATIVA            |             70 |                              6 |                                7.2 | /29                      |
| Wifi-Clientes         | WIFI-CLIENTE      |             80 |                              4 |                                4.8 | /29                      |
| Servidores            | SERVIDORES        |             90 |                              3 |                                3.6 | /29                      |
| **Total**             |                   |                |                            116 |                              139.2 |                          |

| Mascara Sub red      | Direccion de red    | Primer host       | Ultimo Host       | Direccion broadcast |
|----------------------|---------------------|-------------------|-------------------:|--------------------:|
| 255.255.255.192      | 172.21.56.0         | 172.21.56.1       | 172.21.56.62      | 172.21.56.63       |
| 255.255.255.224      | 172.21.56.64        | 172.21.56.65      | 172.21.56.94      | 172.21.56.95       |
| 255.255.255.240      | 172.21.56.96        | 172.21.56.97      | 172.21.56.110     | 172.21.56.111      |
| 255.255.255.240      | 172.21.56.112       | 172.21.56.113     | 172.21.56.126     | 172.21.56.127      |
| 255.255.255.240      | 172.21.56.128       | 172.21.56.129     | 172.21.56.142     | 172.21.56.143      |
| 255.255.255.248      | 172.21.56.144       | 172.21.56.145     | 172.21.56.150     | 172.21.56.151      |
| 255.255.255.248      | 172.21.56.152       | 172.21.56.153     | 172.21.56.158     | 172.21.56.159      |
| 255.255.255.248      | 172.21.56.160       | 172.21.56.161     | 172.21.56.166     | 172.21.56.167      |
| 255.255.255.248      | 172.21.56.168       | 172.21.56.169     | 172.21.56.174     | 172.21.56.175      |


