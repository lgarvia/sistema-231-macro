# Radar_Eventos_2026_05

## CAPA 1: TABLA DE DETECCIÓN

| ID | Fecha | Actor / Institución | Tipo | Vector (principal) | Trigger | Descripción factual brief |
|:--- |:--- |:--- |:--- |:--- |:--- |:--- |
| E_2026_05_12_US_CPI_April | 2026-05-12 | BLS | Dato Macro | V01 | ✅ | Publicación del IPC de EE.UU. correspondiente a abril.<br>Transmisión hacia: V04 |
| E_2026_05_14_US_China_Summit | 2026-05-14 | EE.UU. / China | Cumbre | V04 | | Encuentro bilateral para renegociación de aranceles y estabilización comercial.<br>Transmisión hacia: V06 |
| E_2026_05_14_IEA_Oil_Report | 2026-05-14 | AIE | Informe | V02 | | Actualización de proyecciones de oferta/demanda global de crudo. |
| E_2026_05_15_Fed_Powell_Term | 2026-05-15 | Reserva Federal | Institucional | V01 | | Expiración del mandato de Powell como Chair. Votación para Kevin Warsh.<br>Chokepoint potencial afectado: Mercado de Treasuries de EE.UU. |
| E_2026_05_20_Taiwan_Inauguration | 2026-05-20 | Taiwán | Político | V06 | | Toma de posesión presidencial en Taiwán.<br>Chokepoint potencial afectado: Estrecho de Taiwán |
| E_2026_05_20_Nvidia_Earnings_Q1 | 2026-05-20 | Nvidia | Corporativo | V03 | | Presentación de resultados Q1 FY27 y actualización de CAPEX/demanda de chips IA.<br>Transmisión hacia: V01 |
| E_2026_05_22_SCFI_Freight_Update | 2026-05-22 | SCFI | Dato Físico | V04 | | Actualización del índice de fletes de contenedores ante desvíos por el Cabo. |
| E_2026_05_29_Shangri_La_Dialogue | 2026-05-29 | Asia Security | Cumbre | V06 | | Cumbre de seguridad asiática con participación de defensa de múltiples potencias. |
| E_2026_06_02_Computex_Taipei | 2026-06-02 | Industria Tech | Evento | V03 | | Mayor evento global de hardware y semiconductores. Actualización de roadmaps. |
| E_2026_06_02_Auto_Sales_May | 2026-06-02 | Sector Auto | Dato Físico | V05 | | Publicación de ventas y penetración de mercado de Vehículos Eléctricos en UE. |
| E_2026_06_06_EU_Elections | 2026-06-06 | UE | Electoral | V05 | | Elecciones al Parlamento Europeo. Define el ritmo de la regulación industrial y aranceles.<br>Transmisión hacia: V04 |
| E_2026_06_07_OPEP_Meeting | 2026-06-07 | OPEP+ | Institucional | V02 | ✅ | 41ª Reunión Ministerial. Definición de cuotas y ajustes de producción.<br>Transmisión hacia: V01 |
| E_2026_06_07_Ger_IPI_Apr | 2026-06-07 | Destatis | Dato Macro | V05 | | Índice de Producción Industrial de Alemania. Termómetro de la desindustrialización. |
| E_2026_06_10_US_CPI_May | 2026-06-10 | BLS | Dato Macro | V01 | ✅ | Publicación del IPC de EE.UU. correspondiente a mayo. |
| E_2026_06_11_BCE_Meeting | 2026-06-11 | BCE | Institucional | V01 | ✅ | Reunión de política monetaria del Consejo de Gobierno del BCE. |
| E_2026_06_13_IEA_Oil_Report_Jun | 2026-06-13 | AIE | Informe | V02 | | Actualización mensual del mercado de petróleo global. |
| E_2026_06_15_Spain_Pensiones_Renta | 2026-06-15 | Seguridad Social | Institucional | V05 | | Debate y tensión sobre el déficit de pensiones (€35B+) y secuestro de renta. |
| E_2026_06_15_G7_Summit | 2026-06-15 | G7 | Cumbre | V06 | | Cumbre de líderes del G7. Potenciales acuerdos de resiliencia de cadenas y sanciones.<br>Transmisión hacia: V04 |
| E_2026_06_15_ASML_Export_Review | 2026-06-15 | Gob. Holanda/EEUU| Regulación | V03 | | Revisión trimestral de licencias de exportación de litografía a China.<br>Chokepoint potencial afectado: Litografía EUV (ASML) |
| E_2026_06_16_BoJ_Meeting | 2026-06-16 | BoJ | Institucional | V01 | ✅ | Reunión de política monetaria. Tensión sobre intervención en el Yen. |
| E_2026_06_17_Fed_FOMC | 2026-06-17 | Reserva Federal | Institucional | V01 | ✅ | Reunión del FOMC y publicación de actualización de proyecciones económicas. |
| E_2026_06_20_EU_China_EV_Tariffs | 2026-06-20 | Comisión Europea| Regulación | V04 | | Fecha límite esperada para imposición de aranceles punitivos a EVs chinos. |
| E_2026_06_22_BRICS_Ministers | 2026-06-22 | BRICS+ | Cumbre | V06 | | Reunión de ministros de exteriores y finanzas preparando infraestructura alternativa. |
| E_2026_06_25_LNG_Qatar_Shipments | 2026-06-25 | Logística | Dato Físico | V02 | | Reporte mensual de volúmenes de exportación de GNL qatarí cruzando Ormuz.<br>Chokepoint potencial afectado: Nodos de regasificación de GNL |

---

## CAPA 2: CLASIFICACIÓN EN RADAR OPERATIVO

### ⚫ EVENTOS DE RÉGIMEN (binarios)
* E_2026_05_15_Fed_Powell_Term → V01 | Trigger: No
* E_2026_05_20_Taiwan_Inauguration → V06 | Trigger: No
* E_2026_06_06_EU_Elections → V05 | Trigger: No

### 🔴 CRÍTICO
* E_2026_05_14_US_China_Summit → V04 | Trigger: No
* E_2026_06_07_OPEP_Meeting → V02 | Trigger: Sí
* E_2026_06_11_BCE_Meeting → V01 | Trigger: Sí
* E_2026_06_15_Spain_Pensiones_Renta → V05 | Trigger: No
* E_2026_06_16_BoJ_Meeting → V01 | Trigger: Sí
* E_2026_06_17_Fed_FOMC → V01 | Trigger: Sí

### 🟠 ELEVADO
* E_2026_05_12_US_CPI_April → V01 | Trigger: Sí
* E_2026_05_20_Nvidia_Earnings_Q1 → V03 | Trigger: No
* E_2026_06_10_US_CPI_May → V01 | Trigger: Sí
* E_2026_06_15_ASML_Export_Review → V03 | Trigger: No
* E_2026_06_20_EU_China_EV_Tariffs → V04 | Trigger: No
* E_2026_06_22_BRICS_Ministers → V06 | Trigger: No

### 🟡 LATENTE
* E_2026_05_22_SCFI_Freight_Update → V04 | Trigger: No
* E_2026_05_29_Shangri_La_Dialogue → V06 | Trigger: No
* E_2026_06_07_Ger_IPI_Apr → V05 | Trigger: No
* E_2026_06_15_G7_Summit → V06 | Trigger: No

### ⚪ MONITORIZACIÓN
* E_2026_05_14_IEA_Oil_Report → V02 | Trigger: No
* E_2026_06_02_Computex_Taipei → V03 | Trigger: No
* E_2026_06_02_Auto_Sales_May → V05 | Trigger: No
* E_2026_06_13_IEA_Oil_Report_Jun → V02 | Trigger: No
* E_2026_06_25_LNG_Qatar_Shipments → V02 | Trigger: No

---

## Observatorios narrativos estructurales

| Fecha | Actor / Evento | Tipo | Vector (principal) | Descripción factual brief |
|:--- |:--- |:--- |:--- |:--- |
| 2026-05-18 | Xi Jinping y Vladimir Putin | Encuentro | V06 | Encuentro de alto nivel previsto tras el 'Perfil Bajo' del 9 de mayo.<br>Transmisión hacia: V04 |
| 2026-06-01 | Narrativa de Desacople Industrial | Tendencia | V05 | Aceleración de los discursos proteccionistas previos a las elecciones europeas. |
| 2026-06-28 | IA como Servicio y Energía | Tendencia | V03 | La narrativa mediática gira del "software de IA" a la escasez crítica de redes eléctricas para centros de datos.<br>Transmisión hacia: V02 |

---

## Cobertura por vector (Resumen)

| Vector | Eventos detectados |
|:--- |:--- |
| V01 Arquitectura monetaria | 6 |
| V02 Energía | 4 |
| V03 Semiconductores | 3 |
| V04 Comercio | 3 |
| V05 Industria / movilidad | 3 |
| V06 Orden geopolítico | 4 |
