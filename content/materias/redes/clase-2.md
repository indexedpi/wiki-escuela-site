# Redes: Clase 2 — Direccionamiento IP

**Fecha:** 09/03/2026
**Materia:** Redes
**Clase N°:** 2
**Docente:** Volonté, H (nivel 0)
**Ubicación:** Taller
**Revisado:** Sí

---

## Temas vistos
- Direccionamiento IP: IPv4 e IPv6
- DHCP y asignación automática de parámetros
- Direcciones MAC y Protocolo ARP
- IP pública vs. privada (WAN/LAN)
- Rangos de clases de IP (A, B, C)
- Puerto de enlace y máscara de red
- IPs reservadas, localhost y loopback
- DNS y puertos (default :80)
- Problemática de los módems de ISP

## Conceptos clave
- **IPv4:** Versión más común en redes domésticas. Notación decimal punteada (x.x.x.x), 32 bits, permite 2³² direcciones.
- **IPv6:** 128 bits en formato xxxx:xxxx:xxxx:xxxx...
- **DHCP:** Servidor que asigna automáticamente IP, máscara, gateway y DNS.
- **Dirección MAC:** Identificador único de 48 bits (hexadecimal), 16¹² combinaciones.
- **ARP:** Traduce IP → MAC para identificar físicamente un dispositivo.
- **IP pública:** IPv4 insuficiente → ISP asigna privadas + comparten IP de WAN.
- **Gateway:** Camino interno que conecta WAN con cada dispositivo de la LAN.
- **Máscara de red:** Determina clase de IP (A, B o C) y rango de red local.
- **localhost:** 127.0.0.1
- **Puerto HTTP:** :80 (implícito tras IP/dominio).
- **DNS:** Transforma dominio → IP. Ej: "google.com" → 142.250.x.x.

## Tareas
- [ ] Averiguar los rangos de IP y DNS que asigna tu ISP por DHCP
