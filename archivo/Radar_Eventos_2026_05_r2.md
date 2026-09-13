# RADAR DE EVENTOS: MAYO 2026

*Sensor adelantado. Operando bajo principio de detección exhaustiva y priorización de falso positivo sobre falso negativo.*

## CAPA 1: TABLA DE DETECCIÓN

| ID | Fecha | Actor / Institución | Tipo | Vector (principal) | Trigger | Descripción factual brief |
|:--- |:--- |:--- |:--- |:--- |:--- |:--- |
| E_2026_05_01_US_ISM_Manuf | 2026-05-01 | ISM | Transmisión | V05 |  | Publicación del índice ISM manufacturero de EE.UU.<br>Transmisión hacia: V01 |
| E_2026_05_05_DE_IPI | 2026-05-05 | Destatis | Fricción real | V05 |  | Índice de Producción Industrial Alemán mostrando caídas en sectores críticos. |
| E_2026_05_06_Fed_Decision | 2026-05-06 | Reserva Federal | Gatillo | V01 | ✅ | Decisión de tipos y rueda de prensa en entorno de fragmentación interna.<br>Chokepoint potencial afectado: Mercado Repo<br>Transmisión hacia: V06 |
| E_2026_05_07_BoE_Decision | 2026-05-07 | Bank of England | Gatillo | V01 | ✅ | Decisión de política monetaria en el Reino Unido. |
| E_2026_05_08_US_NFP | 2026-05-08 | BLS | Gatillo | V01 | ✅ | Datos de empleo no agrícola de EE.UU. |
| E_2026_05_09_Russia_VictoryDay | 2026-05-09 | Rusia | Gatillo | V06 | ✅ | Desfile del Día de la Victoria; discursos estratégicos institucionales. |
| E_2026_05_10_US_Export_Controls | 2026-05-10 | EE.UU. (DoC) | Fricción real | V03 |  | Anuncio de nuevas restricciones formales a la exportación de litografía a China.<br>Transmisión hacia: V04, V06 |
| E_2026_05_12_ASML_Guidance | 2026-05-12 | ASML | Transmisión | V03 |  | Actualización de pedidos y previsión de CAPEX por parte del monopolio litográfico. |
| E_2026_05_13_US_CPI | 2026-05-13 | BLS | Gatillo | V01 | ✅ | Publicación de datos de inflación al consumidor (CPI) en EE.UU.<br>Transmisión hacia: V05 |
| E_2026_05_14_US_China_Cumbre | 2026-05-14 | EE.UU. / China | Fricción real | V04 |  | Cumbre bilateral para reordenación logística y compras pragmáticas. |
| E_2026_05_15_GNL_Insurance_Spike | 2026-05-15 | Lloyd's / Sector GNL | Fricción real | V02 |  | Repunte extremo del War Risk Insurance para metaneros en Oriente Medio.<br>Transmisión hacia: V01, V04 |
| E_2026_05_18_Xi_Putin_Meet | 2026-05-18 | China / Rusia | Transmisión | V06 |  | Reunión de alto nivel para reforzar alianzas estratégicas. |
| E_2026_05_18_BASF_Closure | 2026-05-18 | BASF / Industria EU | Fricción real | V05 |  | Confirmación de cierre de líneas de producción base por coste energético.<br>Transmisión hacia: V01 |
| E_2026_05_20_EIA_Oil_Spike | 2026-05-20 | EIA | Transmisión | V02 |  | Caída drástica en inventarios de crudo confirmando disrupción de flujos. |
| E_2026_05_20_Taiwan_Inauguration | 2026-05-20 | Taiwán | Fricción real | V06 |  | Toma de posesión presidencial en Taiwán; riesgo militar latente.<br>Chokepoint potencial afectado: Estrecho de Taiwán<br>Transmisión hacia: V03 |
| E_2026_05_22_US_EU_Auto_Tariffs | 2026-05-22 | USTR / Comisión EU | Fricción real | V04 |  | Amenaza formal de aranceles cruzados al sector automotor.<br>Transmisión hacia: V05 |
| E_2026_05_25_Tech_AI_Summit | 2026-05-25 | Hyperscalers | Transmisión | V03 |  | Cumbre tecnológica revelando problemas de suministro eléctrico para CPDs.<br>Transmisión hacia: V02 |
| E_2026_05_28_SCFI_Spike | 2026-05-28 | Shanghai Exchange | Fricción real | V04 |  | El índice global de fletes marítimos alcanza máximos plurianuales.<br>Transmisión hacia: V01 |
| E_2026_06_01_OPEP_Meeting | 2026-06-01 | OPEP+ | Gatillo | V02 | ✅ | Reunión ministerial para decidir cuotas de producción físicas. |
| E_2026_06_04_BCE_Consejo | 2026-06-04 | BCE | Gatillo | V01 | ✅ | Reunión de política monetaria del BCE; foco en fragmentación.<br>Transmisión hacia: V05 |
| E_2026_06_06_EU_Elections | 2026-06-06 | Unión Europea | Gatillo | V06 | ✅ | Elecciones al Parlamento Europeo; impacto en peso institucional europeo. |

---

## CAPA 2: CLASIFICACIÓN EN RADAR OPERATIVO

### ⚫ EVENTOS DE RÉGIMEN (binarios)
* E_2026_05_14_US_China_Cumbre → V04 | Trigger: No
* E_2026_05_20_Taiwan_Inauguration → V06 | Trigger: No

### 🔴 CRÍTICO
* E_2026_05_06_Fed_Decision → V01 | Trigger: Sí
* E_2026_05_10_US_Export_Controls → V03 | Trigger: No
* E_2026_06_01_OPEP_Meeting → V02 | Trigger: Sí
* E_2026_06_04_BCE_Consejo → V01 | Trigger: Sí

### 🟠 ELEVADO
* E_2026_05_13_US_CPI → V01 | Trigger: Sí
* E_2026_05_15_GNL_Insurance_Spike → V02 | Trigger: No
* E_2026_05_18_BASF_Closure → V05 | Trigger: No
* E_2026_05_22_US_EU_Auto_Tariffs → V04 | Trigger: No
* E_2026_05_28_SCFI_Spike → V04 | Trigger: No
* E_2026_06_06_EU_Elections → V06 | Trigger: Sí

### 🟡 LATENTE
* E_2026_05_07_BoE_Decision → V01 | Trigger: Sí
* E_2026_05_08_US_NFP → V01 | Trigger: Sí
* E_2026_05_09_Russia_VictoryDay → V06 | Trigger: Sí
* E_2026_05_05_DE_IPI → V05 | Trigger: No
* E_2026_05_12_ASML_Guidance → V03 | Trigger: No
* E_2026_05_18_Xi_Putin_Meet → V06 | Trigger: No
* E_2026_05_20_EIA_Oil_Spike → V02 | Trigger: No
* E_2026_05_25_Tech_AI_Summit → V03 | Trigger: No

### ⚪ MONITORIZACIÓN
* E_2026_05_01_US_ISM_Manuf → V05 | Trigger: No

*(Nota: Ningún evento con Trigger ✅ ha sido clasificado como Monitorización)*

---

## Observatorios narrativos estructurales

| Fecha | Actor / Evento | Tipo | Vector (principal) | Descripción factual brief |
|:--- |:--- |:--- |:--- |:--- |
| En curso | BRICS+ Payment System | Estructural | V01 | Desarrollo en curso del sistema de liquidación interbancaria descentralizada. |
| En curso | Tether/Circle en T-Bills | Estructural | V01 | Acumulación masiva de deuda soberana de EE.UU. por emisores de stablecoins. |
| En curso | Industria automotriz EU | Estructural | V05 | Caída en márgenes y reestructuraciones ante competencia china de VE. |

---

## Cobertura por vector (Resumen)

| Vector | Eventos detectados | Porcentaje (%) |
|:--- |:--- |:--- |
| V01 Arquitectura monetaria | 5 | 23.8% |
| V02 Energía | 3 | 14.3% |
| V03 Semiconductores | 3 | 14.3% |
| V04 Comercio | 3 | 14.3% |
| V05 Industria / movilidad | 3 | 14.3% |
| V06 Orden geopolítico | 4 | 19.0% |
| **Total** | **21** | **100%** |
