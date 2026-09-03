# Packet-tracer----lab_Roteamento-Inter-Redes-A-B-C
Estudos de Roteamento e Redes
##  Visão Geral

Este laboratório foi desenvolvido utilizando o **Cisco Packet Tracer** com o objetivo de praticar conceitos fundamentais de **redes de computadores, endereçamento IP, roteamento e segmentação de redes**.

A atividade simula uma infraestrutura de rede composta por diferentes segmentos interconectados por dispositivos de rede, permitindo a aplicação prática dos conceitos estudados.

## Topologia e Arquitetura de Rede
![Topologia da Rede](./topologia.png)

A rede foi estruturada em diferentes segmentos, com dispositivos conectados por switches e roteadores.

### Endereçamento da Rede

| Segmento | Endereço de Rede | Gateway | Máscara | Função |
|---|---|---|---|---|
| Rede A | `10.0.0.0/8` | `10.0.0.1` | `255.0.0.0` | Rede Corporativa |
| Rede B | `172.16.0.0/16` | `172.16.0.1` | `255.255.0.0` | Estações de Trabalho |
| Rede C | `192.168.1.0/24` | `192.168.1.1` | `255.255.255.0` | Rede de Convidados |

---
##  Conceitos Praticados

Durante o laboratório foram trabalhados os seguintes conceitos:

- IPv4
- Endereçamento IP
- Máscaras de sub-rede
- Gateway padrão
- Roteamento
- Switching
- Segmentação de redes
- Comunicação entre dispositivos
- Modelo de rede TCP/IP
