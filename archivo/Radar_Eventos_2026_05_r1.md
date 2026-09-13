# RADAR DE EVENTOS: MAYO 2026

*Sensor adelantado. Operando bajo principio de detección exhaustiva y priorización de falso positivo sobre falso negativo.*

## CAPA 1: TABLA DE DETECCIÓN

| ID | Fecha | Actor / Institución | Tipo | Vector (principal) | Trigger | Descripción factual brief |
|:--- |:--- |:--- |:--- |:--- |:--- |:--- |
| E_2026_05_01_US_ISM_Manuf | 2026-05-01 | ISM | Fricción real | V05 |  | Publicación del índice de gestores de compras del sector manufacturero de EE.UU.<br>Vectores secundarios: V01 |
| E_2026_05_06_Fed_Decision | 2026-05-06 | Reserva Federal | Gatillo | V01 | ✅ | Decisión de tipos y rueda de prensa de Powell en entorno de fragmentación interna.<br>Chokepoint potencial afectado: Mercado Repo |
| E_2026_05_07_BoE_Decision | 2026-05-07 | Bank of England | Gatillo | V01 | ✅ | Decisión de política monetaria en el Reino Unido. |
| E_2026_05_08_US_NFP | 2026-05-08 | BLS | Gatillo | V01 | ✅ | Datos de empleo no agrícola de EE.UU. |
| E_2026_05_09_Russia_VictoryDay | 2026-05-09 | Rusia | Binario | V06 |  | Desfile del Día de la Victoria; posible anuncio de movimientos estratégicos. |
| E_2026_05_13_US_CPI | 2026-05-13 | BLS | Gatillo | V01 | ✅ | Publicación de datos de inflación al consumidor (CPI) en EE.UU.<br>Vectores secundarios: V02 |
| E_2026_05_14_US_China_Cumbre | 2026-05-14 | EE.UU. / China | Fricción real | V04 |  | Cumbre bilateral para reordenación logística y compras pragmáticas.<br>Chokepoint potencial afectado: Restricciones de exportación |
| E_2026_05_18_Xi_Putin_Meet | 2026-05-18 | China / Rusia | Transmisión | V06 |  | Reunión de alto nivel para reforzar alianzas estratégicas y acuerdos comerciales energéticos. |
| E_2026_05_20_Taiwan_Inauguration | 2026-05-20 | Taiwán | Fricción real | V06 |  | Toma de posesión presidencial en Taiwán; riesgo de respuesta de Beijing.<br>Chokepoint potencial afectado: Estrecho de Taiwán<br>Vectores secundarios: V03 |
| E_2026_05_25_Tech_AI_Summit | 2026-05-25 | Hyperscalers | Transmisión | V03 |  | Cumbre tecnológica; foco en suministro eléctrico y escalado de CAPEX en CPDs.<br>Vectores secundarios: V02 |
| E_2026_06_01_OPEP_Meeting | 2026-06-01 | OPEP+ | Gatillo | V02 | ✅ | Reunión ministerial para decidir cuotas de producción en contexto de Ormuz bloqueado.<br>Chokepoint potencial afectado: Ormuz |
| E_2026_06_04_BCE_Consejo | 2026-06-04 | BCE | Gatillo | V01 | ✅ | Reunión de política monetaria del BCE; foco en fragmentación e inflación importada.<br>Vectores secundarios: V05 |
| E_2026_06_06_EU_Elections | 2026-06-06 | Unión Europea | Binario | V06 |  | Elecciones al Parlamento Europeo; posible reconfiguración del peso institucional. |
| E_2026_06_11_Fed_FOMC | 2026-06-11 | Reserva Federal | Gatillo | V01 | ✅ | Reunión del FOMC y actualización de proyecciones económicas. |

---

## CAPA 2: CLASIFICACIÓN EN RADAR OPERATIVO

### ⚫ EVENTOS DE RÉGIMEN (binarios)
* E_2026_05_14_US_China_Cumbre → V04 | Trigger: No
* E_2026_05_20_Taiwan_Inauguration → V06 | Trigger: No
* E_2026_06_06_EU_Elections → V06 | Trigger: No

### 🔴 CRÍTICO
* E_2026_05_06_Fed_Decision → V01 | Trigger: Sí
* E_2026_06_01_OPEP_Meeting → V02 | Trigger: Sí
* E_2026_06_04_BCE_Consejo → V01 | Trigger: Sí

### 🟠 ELEVADO
* E_2026_05_13_US_CPI → V01 | Trigger: Sí
* E_2026_06_11_Fed_FOMC → V01 | Trigger: Sí

### 🟡 LATENTE
* E_2026_05_18_Xi_Putin_Meet → V06 | Trigger: No
* E_2026_05_25_Tech_AI_Summit → V03 | Trigger: No
* E_2026_05_09_Russia_VictoryDay → V06 | Trigger: No

### ⚪ MONITORIZACIÓN
* E_2026_05_01_US_ISM_Manuf → V05 | Trigger: No
* E_2026_05_07_BoE_Decision → V01 | Trigger: Sí
* E_2026_05_08_US_NFP → V01 | Trigger: Sí

---

## Observatorios narrativos estructurales

| Fecha | Actor / Evento | Tipo | Vector (principal) | Descripción factual brief |
|:--- |:--- |:--- |:--- |:--- |
| En curso | BRICS+ Payment System | Estructural | V01 | Desarrollo en curso del sistema de liquidación interbancaria descentralizada. |
| En curso | Tether/Circle en T-Bills | Estructural | V01 | Acumulación masiva de deuda soberana de EE.UU. por emisores de stablecoins. |
| En curso | Industria automotriz EU | Estructural | V05 | Caída en márgenes y reestructuraciones ante competencia china de VE. |

---

## Cobertura por vector (Resumen)

| Vector | Eventos detectados |
|:--- |:--- |
| V01 Arquitectura monetaria | 7 |
| V02 Energía | 1 |
| V03 Semiconductores | 1 |
| V04 Comercio | 1 |
| V05 Industria / movilidad | 1 |
| V06 Orden geopolítico | 3 |
