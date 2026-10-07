# ⚡ CEMAN | Propuesta Técnica de Monitoreo CCTV 24/7 y Dictamen de Riesgo
### Central de Ciclo Combinado "Jorge Luque" (Generadora Fénix) — Tultitlán, Edo. Méx.
#### En Cumplimiento de la Especificación Técnica No. 238-26 (`ES-SC-238-26`, Rev. 01)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-success.svg)](#-despliegue-en-vivo-github-pages)
[![RFP: ES-SC-238-26](https://img.shields.io/badge/RFP-ES--SC--238--26-cyan.svg)](ANALISIS_DELICTIVO_FENIX.md)
[![CCTV: 34 Cámaras](https://img.shields.io/badge/CCTV-34%20C%C3%A1maras%2024%2F7-emerald.svg)](index.html)
[![GeoData: GeoJSON](https://img.shields.io/badge/GeoData-GeoJSON-brightgreen.svg)](data/puntos_criticos_fenix.geojson)

Proyecto de ingeniería de seguridad patrimonial, análisis criminológico ambiental (CPTED) y propuesta de **Monitoreo Remoto 24/7 de las 34 Cámaras** de la **Central de Ciclo Combinado "Jorge Luque" (Generadora Fénix)** elaborado por **CEMAN (Centro de Monitoreo y Análisis de Seguridad)** en estricto apego a las bases de la licitación `ES-SC-238-26`.

---

## 📍 Identificación Geográfica y Activo Estratégico

* **Instalación:** Central de Ciclo Combinado "Jorge Luque" (Generadora Fénix — Mota-Engil / SME).
* **Ubicación Oficial:** Carretera Tlalnepantla - Cuautitlán Km 22.5 Industrial Lechería, Tultitlán, Estado de México.
* **Coordenadas de Referencia:** `19.6176111° N, -99.1902971° W`
* **Naturaleza del Activo:** **Infraestructura Crítica Estratégica Nacional** (1,660 MW proyectados, turbinas de gas/vapor, subestación eléctrica de alta tensión, estación de gasoducto GNV y almacenamiento de combustibles).

![Mapa Táctico Geográfico y Análisis CEMAN - Fénix CCC Jorge Luque](./mapa_tactico_geografico_fenix.png)

---

## 📋 Resumen de Cumplimiento Técnico (Especificación No. 238-26)

| Requerimiento RFP | Especificación `ES-SC-238-26` | Solución y Compromiso CEMAN |
| :--- | :--- | :--- |
| **Alcance y Ubicación** | Monitoreo remoto fuera de las instalaciones de CCC JL | Operación 24/7/365 desde el Centro de Monitoreo Externo de CEMAN. |
| **Inventario CCTV** | **34 Cámaras existentes** en la Central | Vigilancia activa e ininterrumpida con operadores dedicados a las 34 cámaras. |
| **Infraestructura SOC** | Biométricos, CCTV interno, controles físicos y política sin celulares | Doble esclusa biométrica, sala estéril (*clean room*) con prohibición absoluta de dispositivos móviles. |
| **Supervisión Operativa** | Control de procesos internos y desvíos a procedimientos (Sec. 3.3) | Verificación de protocolos EPP/LOTO, bitácora de turnos e informe mensual integrado. |
| **Enlace y Red (TI)** | Canal dedicado/VPN y mitigación de cortes de comunicación | Túnel VPN IPsec redundante con *heartbeat* activo; notificación de cortes en <3 min. |
| **Plazo del Servicio** | **6 meses de prueba** condicionado a evaluación de desempeño | Aceptación plena del periodo de prueba y métricas de SLA acordadas. |
| **Condiciones Comerciales**| Precios en **MXN**, pago mensual a **30 días** contra factura e informe | Cotización en moneda nacional y crédito comercial a 30 días contra entregable mensual. |

---

## 🎥 Distribución de las 34 Cámaras en la Central

En correspondencia con la zonificación táctica y el mapa geográfico:

1. 🔴 **Punto 1 — Subestación Eléctrica, Turbinas & Casa de Máquinas (10 Cámaras):**
   * *Riesgo:* Sustracción de cable de cobre, tierras físicas, sabotaje y desvíos a procedimientos de alta tensión (Score: **9.2/10**).
   * *Equipamiento:* Domos PTZ Térmicos 360° con auto-tracking y cámaras de proceso industrial.
2. 🔴 **Punto 2 — Flanco Poniente Autopista México-Querétaro 57D (6 Cámaras):**
   * *Riesgo:* Piratería del asfalto con *jammers*, halconeo en acotamiento y fuga veloz (Score: **8.6/10**).
   * *Equipamiento:* Cámaras térmicas bispectrales de 300 m con analítica de vehículo detenido.
3. 🟡 **Punto 3 — Acceso Principal Sur Calle de Guadalupe (6 Cámaras):**
   * *Riesgo:* Asaltos en cambio de turno, control vehicular y pseudo-sindicatos de choque (Score: **8.4/10**).
   * *Equipamiento:* Cámaras LPR (placas), domos antivandálicos en caseta y botón de pánico enlazado a C5/CEMAN.
4. 🔵 **Punto 4 — Barda Norte Colindancia Tultipark I (5 Cámaras):**
   * *Riesgo:* CPTED punto ciego, baja iluminación nocturna y escalamiento (Score: **7.8/10**).
   * *Equipamiento:* Cámaras DarkFighter 4K, cruce de línea (*tripwire*) y altavoz IP con voceo disuasivo en vivo.
5. 🟣 **Punto 5 — Flanco Oriente E2 GNV Lechería & Vías Férreas (5 Cámaras):**
   * *Riesgo:* Peligro tecnológico en gasoducto/gasera y flujo de población flotante/migrante (Score: **7.9/10**).
   * *Equipamiento:* Cámaras con certificación ATEX/antiexplosión y analítica de merodeo en derecho de vía.
6. 🟠 **Punto 6 — Enlace Logístico y Rutas de Aproximación 57D (2 Cámaras):**
   * *Riesgo:* Emboscadas a transportes con químicos e insumos críticos en bajopuentes (Score: **8.5/10**).
   * *Equipamiento:* Cámaras ópticas contextuales para custodia virtual en ruta de arribo.
* **TOTAL CENTRAL CCC JORGE LUQUE:** **34 CÁMARAS MONITOREADAS 24/7**.

---

## 🏅 Certificaciones y Acreditaciones de CEMAN (Sec. 4)

* **ISO 9001:2015:** Gestión de la Calidad en Monitoreo y Operaciones.
* **ISO 18788:2015:** Operaciones de Seguridad Privada y Protección de Derechos Humanos.
* **ISO 17024:** Certificación de Competencias del Personal de Seguridad y Operadores SOC.
* **CONOCER EC0213:** Prestación de Servicios de Monitoreo de Sistemas de Videovigilancia.
* **ASIS International:** Certificaciones de dirección y supervisión CPP (*Certified Protection Professional*) y PSP (*Physical Security Professional*).
* **NOM-035-STPS-2018:** Prevención de Riesgos Psicosociales en Jornadas 24/7.
* **Registro DGSP:** Permiso Federal y Estatal de Seguridad Privada vigente ante la SSPC.

---

## 📂 Contenido del Repositorio

```bash
ceman-fenix-jorge-luque/
│
├── index.html                   # Aplicativo web interactivo (con mapa satelital zoom embebido)
├── ANALISIS_DELICTIVO_FENIX.md  # Dictamen técnico completo alineado a ES-SC-238-26
├── mapa_tactico_geografico_fenix.png # Render gráfico de alta resolución con las 34 cámaras
├── mapa_base_fenix_zoom.jpg     # Cartografía satelital con zoom calibrado (19.6176, -99.1903)
├── data/
│   ├── puntos_criticos_fenix.geojson # Datos geoespaciales y distribución de cámaras CCTV
│   └── indicadores_tultitlan.json    # Métricas estadísticas oficiales del SESNSP / INEGI
├── .gitignore                   # Exclusiones de control de versiones
├── LICENSE                      # Licencia de uso
└── README.md                    # Portada y documentación ejecutiva
```

---

## 🚀 Despliegue en Vivo (GitHub Pages)

Para consultar este proyecto mediante enlace público en cualquier dispositivo:
1. Sube esta carpeta a tu repositorio en GitHub (`main`).
2. En GitHub ve a **Settings** > **Pages** > selecciona **Deploy from a branch** > rama **`main`** / carpeta **`/ (root)`**.
3. En breves segundos obtendrás el enlace público: `https://<tu-usuario>.github.io/<tu-repositorio>/`.
