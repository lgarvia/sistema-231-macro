# RADAR DE EVENTOS — SEPTIEMBRE 2026

> **Versión:** 2.3 — W38, TASK_116.
> **Corte factual:** 2026-09-19 05:29 Europe/Madrid (precierre; no cobertura íntegra del domingo 20).
> **Horizonte:** 2026-09-19 → 2026-11-18 inclusive (+60 días).
> **Filas:** 21 · **Prioridades:** 1 Régimen / 7 Crítico / 9 Elevado / 4 Latente.
> **Ventanas enriquecidas:** 0 · **Observatorios:** 4 · **Resoluciones históricas:** 16.

## TABLA DE HITOS CALENDARIZADOS

| ID | Fecha / ventana | Confirmación | Actor | Tipo | Vector | Evento sensor | Tesis | Observable / Trigger | Prioridad | Descripción factual | Fuente |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `E_2026_09_09_US_Treasury_Long_End_Buybacks` | 2026-09-09/2026-11-04 | CONFIRMADO | U.S. Treasury / NY Fed | Operación de liquidez | V01 | V01 — Absorción y liquidez de deuda | TESIS_01_Dominancia_Fiscal | Volumen anunciado, ofertado y aceptado por tramo; distinguir tamaño autorizado de adjudicación efectiva; bid-ask y liquidez off-the-run | ELEVADO | Ventana iniciada el 09/09, aún en curso hasta el 04/11; la recompra del Tesoro no equivale a QE. | [Tesoro, anuncio 19/08](https://home.treasury.gov/news/press-releases/sb0607) |
| `E_2026_09_22_EU_Russia_Sanctions_Expiry` | 2026-09-22 | CONFIRMADO | Consejo de la Unión Europea | Vencimiento normativo | V06 | NINGUNO — sensor V06 | TESIS_04_Multipolaridad_Logistica | Nuevo acto de prórroga, modificación o expiración de medidas individuales; comprobar alcance y fecha | ELEVADO | La Decisión 2026/2103 solo extiende vigencia hasta 22/09; no anticipa otra renovación. | [Decisión 2026/2103](https://eur-lex.europa.eu/eli/dec/2026/2103/oj/eng/pdf) |
| `E_2026_09_24_BoJ_Rate_Effective` | 2026-09-24 | CONFIRMADO | Banco de Japón | Entrada efectiva de tipos | V01 | Japón/liquidez — carry | TESIS_01_Dominancia_Fiscal | Implementación del objetivo 1,25% y comparación de diferencial; no usar tipos oficiales como retorno 30Y cubierto | CRÍTICO | Vigencia anunciada el 18/09; evento de decisión consumido y ventana de implementación separada, sin doble carga. | [BoJ, decisión y anexo](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf) |
| `E_2026_09_30_US_Quarter_End_Liquidity` | 2026-09-25/2026-09-30 | RECURRENTE OFICIAL | Fed / NY Fed / Dealers | Cierre regulatorio | V01 | Japón/Liquidez — Trigger D | TESIS_01_Dominancia_Fiscal | 1) Uso del Standing Repo Facility (SRF > $20B diarios durante >2 días); 2) Spread SOFR frente a IORB; 3) Dispersión en percentil 99 de repo tri-party; 4) Saldo ON RRP | CRÍTICO | Ventana de observación del cierre Q3. Posible tensión de intermediación, que debe medirse; no se da por ocurrida. | [NY Fed Markets Data](https://www.newyorkfed.org/markets/reference-rates) |
| `E_2026_09_29_US_Section338_Import_Bans` | 2026-09-29 | CONFIRMADO | Casa Blanca / CBP | Entrada en vigor de prohibiciones | V04 | Tariff Stack — continuación de A/B | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Productos canadienses efectivamente prohibidos; 2) Alcance jurídico; 3) Exenciones o licencias; 4) Evidencia de aplicación aduanera | CRÍTICO | Segunda fecha de ejecución de la respuesta estadounidense: entrada de determinadas prohibiciones de importación previstas en las proclamaciones Section 338 del 08/09. | [White House — respuesta a Canadá](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/) |
| `E_2026_09_30_Micron_FY26_Q4_Earnings` | 2026-09-30 | CONFIRMADO | Micron Technology | Resultados corporativos | V03 | CoWoS — Sensor HBM | TESIS_06_IA_como_silicio_y_energia | 1) Horizonte de venta agotada (sold-out) en HBM3E y progreso de validación de HBM4; 2) Guía de CAPEX fabril FY2027; 3) Rendimiento de memoria para aceleradores | ELEVADO | Resultados del 4T fiscal de Micron. Termómetro directo del estrangulamiento de memoria de alto ancho de banda (HBM) en la cadena de suministro de hardware de IA. | [Convocatoria oficial, 30/09 14:30 Mountain](https://investors.micron.com/news/press-release/2026/Micron-Technology-to-Report-Fiscal-Fourth-Quarter-Results-on-September-30-2026/default.aspx) |
| `E_2026_10_04_OPEC_Plus_Seven_Countries` | 2026-10-04 | CONFIRMADO | Siete países participantes OPEP+ | Reunión de producción | V02 | NINGUNO — Sensor V02 | TESIS_04_Multipolaridad_Logistica | Niveles de producción, compensación y decisión para el mes siguiente | LATENTE | Siguiente reunión anunciada el 06/09 por siete participantes. No se identifica como 68ª JMMC. | [OPEP, comunicado 06/09](https://www.opec.org/pr-detail/613-6-september-2026.html) |
| `E_2026_10_06_US_International_Trade_August` | 2026-10-06 | CONFIRMADO | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Identificar categorías aranceladas; 2) Variación interanual (YoY); 3) Comprobar si caída supera -15% YoY (posible mes 1); 4) Déficit bilateral | ELEVADO | Primer dato comercial post-arancel susceptible de constituir mes 1 del Trigger D si las importaciones en sectores cubiertos caen >15% YoY según Census/BEA. | [Census, calendario FT900 2026](https://www.census.gov/foreign-trade/schedule.html) |
| `E_2026_10_07_08_US_Treasury_10Y_30Y_Reopenings` | 2026-10-07/2026-10-08 | PROVISIONAL | U.S. Treasury | Subasta soberana | V01 | V01 — Absorción soberana de duración | TESIS_01_Dominancia_Fiscal | Bid-to-cover <2,30 en dos emisiones sucesivas verificadas; tail frente a when-issued y asignación indirecta. No presuponer el resultado de septiembre. | LATENTE | Reapertura de subastas a 10 y 30 años de octubre. Contraste de persistencia de absorción para evaluar si se consuma el Trigger 03 de V01 (<2,30x en 2 emisiones). | [Tesoro, calendario tentativo de subastas](https://home.treasury.gov/system/files/221/Tentative-Auction-Schedule.pdf) |
| `E_2026_10_08_Japan_Monthly_Securities_Flows_September` | 2026-10-08 | RECURRENTE OFICIAL | Ministerio de Finanzas de Japón | Estadística de flujos | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Compras netas de deuda extranjera a largo plazo; 2) Signo del total de cartera; 3) Comparación con agosto (−¥143,0B en deuda larga); 4) Confirmar o negar segundo mes negativo | CRÍTICO | Publicación mensual de septiembre. Puede completar el componente de dos meses consecutivos del Trigger A, pero todavía exige verificar el diferencial cubierto durante 15 días. | [MOF Japan — calendario de publicación](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm) |
| `E_2026_10_08_TSMC_September_Sales` | 2026-10-08 | PROVISIONAL | TSMC | Ingresos corporativos | V03 | V03 — Ciclo de fundición y demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación mensual en NT$; 2) Crecimiento YoY; 3) Cierre consolidado del 3T vs guidance trimestral (inferencia); 4) Variación acumulada 2026 | LATENTE | Facturación de septiembre y cierre trimestral de TSMC. Sensor agregado de demanda; no desglosa nodos 3nm/5nm ni cuellos de botella CoWoS/HBM. | [Calendario TSMC, sujeto a cambios](https://investor.tsmc.com/english/financial-calendar) |
| `E_2026_10_16_US_TIC_Securities_Data` | 2026-10-16 | RECURRENTE OFICIAL | U.S. Treasury | Estadística financiera | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | Flujos japoneses comparables y composición; distinguir stock de transacciones y comprobar los >15 días hábiles de diferencial cubierto | CRÍTICO | Datos de agosto; no se presume julio negativo por el descenso del stock. | [TIC julio: siguiente publicación 16/10](https://home.treasury.gov/news/press-releases/sb0631/) |
| `E_2026_10_28_Fed_FOMC_Decision` | 2026-10-27/2026-10-28 | CONFIRMADO | Reserva Federal | Decisión monetaria | V01 | V01 — Política monetaria | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre tipo de fondos federales; 2) Tono del comunicado sobre riesgos de empleo e inflación; 3) Mensaje sobre estabilidad de reservas antes de elecciones | ELEVADO | Reunión de política monetaria intermedia (sin SEP). Calibra las condiciones de liquidez monetaria una semana antes de las elecciones legislativas estadounidenses. | [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| `E_2026_10_29_ECB_Monetary_Policy` | 2026-10-28/2026-10-29 | CONFIRMADO | Banco Central Europeo | Decisión monetaria | V01 | NINGUNO — sensor de tipos y fragmentación V01 | TESIS_01_Dominancia_Fiscal | 1) Tipos de depósito/MRO/marginal frente a 2,50%/2,65%/2,90%; 2) Orientación de balance; 3) Referencias operativas a fragmentación o spreads soberanos; 4) Instrumentos de transmisión | ELEVADO | Primera decisión del BCE posterior al alza del 10/09. Se admite por su canal directo a coste soberano y fragmentación, no como reunión rutinaria automática. | [ECB — calendario del Consejo de Gobierno](https://www.ecb.europa.eu/press/calendars/mgcgc/html/index.en.html) |
| `E_2026_10_30_BoJ_MPM_Outlook` | 2026-10-29/2026-10-30 | CONFIRMADO | Banco de Japón | Decisión monetaria | V01 | Japón/Liquidez — Carry trade | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre objetivo del tipo overnight; 2) Proyecciones plurianuales de PIB e inflación 2026–2027 en el Outlook Report; 3) Evaluación del tipo de cambio | ELEVADO | Reunión trimestral con Outlook Report del BoJ. Determina la trayectoria esperada de tipos de interés para finales de 2026 e inicios de 2027. | [Bank of Japan Releases](https://www.boj.or.jp/en/mopo/mpmsche_minu/index.htm) |
| `E_2026_11_02_US_Treasury_Financing_Estimates` | 2026-11-02 | CONFIRMADO | U.S. Treasury | Estimación financiera | V01 | V01 — Necesidades de endeudamiento | TESIS_01_Dominancia_Fiscal | 1) Estimación oficial de endeudamiento neto para el 4T 2026 y 1T 2027; 2) Saldo objetivo de caja TGA al cierre de año; 3) Proporción estimada bills vs cupones | ELEVADO | Publicación de necesidades de financiación previas al Refunding. Fija la escala de liquidez requerida por el Tesoro de los mercados primarios. | [Tesoro, próximas publicaciones 02/11 y 04/11](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/most-recent-quarterly-refunding-documents/) |
| `E_2026_11_03_US_Midterm_Elections` | 2026-11-03 | CONFIRMADO | Electorado de EE. UU. / Congreso | Elección política | V06 | NINGUNO — Sensor político-fiscal | TESIS_01_Dominancia_Fiscal, TESIS_04_Multipolaridad_Logistica | 1) Mayorías parlamentarias en Cámara y Senado; 2) Margen legislativo para sostener o modificar aranceles; 3) Perspectiva sobre prórroga fiscal y techo de deuda en 2027 | ELEVADO | Elecciones de mitad de mandato en EE. UU. Condicionan la arquitectura fiscal y el margen de ejecución de la política comercial y regulatoria federal. | [FEC, fecha de elecciones federales 2026](https://www.fec.gov/introduction-campaign-finance/election-results-and-voting-information/) |
| `E_2026_11_04_US_International_Trade_September` | 2026-11-04 | CONFIRMADO | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Comprobar si septiembre presenta caída >15% YoY en sectores cubiertos Y si agosto ya cumplió >15% YoY; 2) Activación completa de Trigger D | CRÍTICO | Balanza comercial de septiembre. Punto resolutivo para la activación formal del Trigger D si se encadenan dos meses consecutivos con caída >15% YoY. | [Census, calendario FT900 2026](https://www.census.gov/foreign-trade/schedule.html) |
| `E_2026_11_04_US_Treasury_Quarterly_Refunding` | 2026-11-04 | CONFIRMADO | U.S. Treasury | Emisión soberana | V01 | V01 — Política de emisión y colateral | TESIS_01_Dominancia_Fiscal | 1) Tamaños de subastas en tramos 2Y, 5Y, 10Y y 30Y; 2) Cuota de financiación vía T-Bills respecto a deuda cupón; 3) Decisión sobre el programa de buybacks; 4) Informe TBAC | RÉGIMEN | Anuncio formal de política de refinanciación de la deuda de EE. UU. Determina si el tramo largo de la curva soberana sufre sobresaturación o racionamiento de colateral. | [Tesoro, próximas publicaciones 02/11 y 04/11](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/most-recent-quarterly-refunding-documents/) |
| `E_2026_11_10_Japan_Monthly_Securities_Flows_October` | 2026-11-10 | RECURRENTE OFICIAL | Ministerio de Finanzas de Japón | Estadística de flujos | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Compras netas de deuda extranjera a largo plazo; 2) Persistencia mensual; 3) Composición por tipo de activo; 4) Contraste con septiembre y agosto | CRÍTICO | Publicación mensual de octubre. Comprueba si una eventual secuencia de desinversión exterior persiste; no sustituye el requisito del diferencial cubierto. | [MOF Japan — calendario de publicación](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm) |
| `E_2026_11_10_TSMC_October_Sales` | 2026-11-10 | PROVISIONAL | TSMC | Ingresos corporativos | V03 | CoWoS — sensor agregado de demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación mensual en NT$; 2) Crecimiento interanual; 3) Acumulado enero-octubre; 4) Trayectoria frente a guía trimestral como inferencia | LATENTE | Extiende el horizonte hasta noviembre con un sensor agregado comparable. No mide capacidad CoWoS, *yields*, AP7 ni entregas físicas de aceleradores. | [Calendario TSMC, sujeto a cambios](https://investor.tsmc.com/english/financial-calendar) |

---

## 1. CANDIDATO EN CUARENTENA — VISITA XI A EE. UU.

### [CAND_2026_OTONO_Visita_Xi_US] — fecha exacta pendiente

- **Estado:** ANUNCIADO en términos estacionales; **NO ADMITIDO** en la tabla calendarizada hasta disponer de fecha oficial acotada.
- **Respaldo disponible:** la Casa Blanca y el Ministerio de Exteriores chino confirman una visita de Estado de Xi Jinping a Washington «este otoño». Ninguna de las dos fuentes fija el 24/09.
- **Decisión W37:** retirar `VEN_2026_09_24_Cumbre_Xi_US` de la tabla y revocar temporalmente su promoción como Ventana Enriquecida. La fecha aportada no supera los criterios de temporalidad y fuente primaria del Radar 2.0.
- **Vectores potenciales:** V04 primario; V06 y V03 secundarios.
- **Eventos sensores potenciales:** [[Evento_E1_2026_07_24_US_Tariff_Stack]] · [[Evento_E0_2026_CoWoS_Capacity]].
- **Observables preservados para una futura readmisión:** acto arancelario vinculante; normativa BIS sobre GPUs/HBM/litografía; licencias MOFCOM sobre minerales críticos; y comunicado o memorando conjunto.
- **Condición de readmisión:** publicación por la Casa Blanca o MOFA/MOFCOM de una fecha o ventana bilateral acotada dentro del horizonte rodante. Solo entonces se reevalúan los seis criterios A–F de Ventana Enriquecida.
- **Fuentes:** [Casa Blanca — visita prevista en otoño](https://www.whitehouse.gov/fact-sheets/2026/05/fact-sheet-president-donald-j-trump-secures-historic-deals-with-china-delivering-for-american-workers-farmers-and-industry/); [Ministerio de Exteriores de China — visita prevista en otoño](https://www.fmprc.gov.cn/eng/xw/zwbd/202606/t20260622_11949659.html).

---

## 1b. Notas de ventanas prioritarias

Las notas siguientes conservan criterios de decisión sin duplicar estados ni añadir ventanas enriquecidas. La proximidad temporal no constituye evidencia ni altera la carga.

### Section 338 Canadá — 15 y 29-sep

El ID `E_2026_09_15_US_Section338_Product_Changes` está en consumidos; `E_2026_09_29_US_Section338_Import_Bans` permanece futuro. V04 primario; transmisión a V05/V01; TESIS_02. Verificar ejecución efectiva, alcance por producto, instrucciones aduaneras y eventuales suspensiones. Son continuación de la escalada jurídica ya incorporada en Tariff Stack; no activan automáticamente C–E sin datos de transmisión.

### TGA 15-sep

Hito consumido MATERIAL para la evaluación de liquidez; B parcial. Véanse la fila de resolución y la ficha Japón. No queda como fecha futura.

### FOMC 16-sep

Hito consumido MATERIAL: alza de 25 pb. La siguiente decisión es 27–28/10; BoJ implementará el alza anunciada el 24/09.

### Cierre Q3 30-sep

Observar 25–30/09 con datos publicados después de cada jornada. D exige >20 B$ diarios durante >2 días consecutivos dentro de la ventana; la SRF provee liquidez. El percentil 99 requiere aclarar serie y referencia antes de automatizar la alternativa de C.

### Midterms 03-nov

La proximidad electoral no prueba apoyo monetario ni liquidez garantizada. FEC confirma el 03/11/2026; el resultado y su efecto fiscal siguen futuros.

---

## 2. OBSERVATORIOS ESTRUCTURALES

### 1. Observatorio de Riesgo Marítimo y Seguridad de Chokepoints (Ormuz y Bab el-Mandeb)
- **Vectores:** [[VECTOR_02_Energia_y_nodos_geoeconomicos]], [[VECTOR_04_Reconfiguracion_del_comercio_global]], [[VECTOR_01_Arquitectura_monetaria_global]]
- **Evento conectado:** [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb]]
- **Variables monitoreadas:** 
  1. Recuento oficial de ataques y bajas marítimas por la OMI (publicado 16/09: 80 ataques verificados en Ormuz y proximidades, al menos 22 fallecidos).
  2. Avisos de incidentes cinéticos en tiempo real de UKMTO (enfoque en boca de Ormuz y Bab el-Mandeb).
  3. Revisiones de áreas listadas del Joint War Committee de Lloyd's (JWLA-035 vigente, fechada 16/09; modificación del mar Negro).
  4. Cotizaciones verificables de primas adicionales de guerra en brokers de Londres (umbral Trigger A $\ge 1,5\%$).
  5. Daños estructurales o hundimientos en buques petroleros VLCC o metaneros LNG (Trigger B).
  6. Interrupción de tránsito físico superior a 5 Mb/d por más de 48 horas (Trigger D).
- **Condición de promoción a tabla calendarizada:** Publicación oficial con fecha fijada de una nueva circular del JWC (distinta de JWLA-035, ya publicada) o convocatoria formal de una conferencia regulatoria marítima de la OMI.

### 2. Observatorio de Estrés de Red Eléctrica e Infraestructura Crítica de IA (Grid Stress)
- **Vectores:** [[VECTOR_02_Energia_y_nodos_geoeconomicos]], [[VECTOR_03_Semiconductores_y_soberania_tecnologica]]
- **Evento conectado:** [[Evento_E0_2026_07_08_Grid_Stress_IA]]
- **Variables monitoreadas:**
  1. Resoluciones administrativas y órdenes de FERC sobre dockets de coincentivación y centros de datos (EL26-67 a EL26-72).
  2. Emisión y vencimiento de órdenes de emergencia bajo Sección 202(c) de la Federal Power Act por el Department of Energy (DOE); nueva 202-26-45 para 17–18/09, con EEA1; no demuestra el trigger CPD completo.
  3. Declaraciones de alerta de emergencia de energía (EEA 1/2/3) en operadores regionales PJM, MISO y ERCOT.
  4. Moratorias locales formales o denegaciones de derechos de conexión a centros de datos de IA (ej. Loudoun County, Ohio, Texas).
  5. Solicitudes de suministro cautivo de agua o generación nuclear privada co-ubicada.
- **Condición de promoción a tabla calendarizada:** Fijación de fecha formal para votación de órdenes de tarificación en sesión pública de la FERC o vencimiento formal de órdenes administrativas del DOE.

### 3. Observatorio de Capacidad Física de Empaquetado Avanzado y Silicio (CoWoS & HBM)
- **Vectores:** [[VECTOR_03_Semiconductores_y_soberania_tecnologica]], [[VECTOR_02_Energia_y_nodos_geoeconomicos]]
- **Evento conectado:** [[Evento_E0_2026_CoWoS_Capacity]]
- **Variables monitoreadas:**
  1. Hitos de construcción, entrega de salas limpias y ensamblaje de toolings en la gigafab AP7 de TSMC en Chiayi.
  2. *Lead times* de empaquetado avanzado CoWoS-S/L/R y disponibilidad de sustratos ABF; exigir evidencia generalizada y contrastarla con el umbral inferior a 20 semanas del Trigger D.
  3. Capacidad fabril y rendimientos de obleas de memoria HBM3E y validación de HBM4 en SK Hynix, Micron y Samsung.
  4. Compromisos vinculantes de CAPEX físico en hardware por los hiperescalares (Microsoft, Google, Meta, AWS).
- **Condición de promoción a tabla calendarizada:** Calendario oficial de presentaciones trimestrales de resultados o anuncios regulatorios del BIS con fecha de vigencia formal.

### 4. Observatorio de Fragmentación Geopolítica, Sanciones y Arquitectura Financiera Alternativa (V06)
- **Vectores:** [[VECTOR_06_Orden_geopolitico_y_esferas_de_influencia]], [[VECTOR_01_Arquitectura_monetaria_global]], [[VECTOR_04_Reconfiguracion_del_comercio_global]]
- **Evento conectado:** NINGUNO — sensor estructural V06
- **Variables monitoreadas:**
  1. Nuevas rondas de sanciones secundarias de la OFAC del Departamento del Tesoro dirigidas a entidades bancarias en jurisdicciones intermedias.
  2. Volúmenes de liquidación transfronteriza fuera de SWIFT a través del sistema CIPS chino y proyectos de monedas digitales de bancos centrales multilaterales (mBridge).
  3. Variaciones netas en tenencias de reservas soberanas en oro físico y liquidación de activos en divisas del G7 por bancos centrales del Sur Global.
  4. Acuerdos de cooperación militar, derechos de atraque de doble uso o bases navales en el Índico, Mar Rojo y Golfo de Guinea.
- **Condición de promoción a tabla calendarizada:** Convocatoria oficial fechada de cumbres multilaterales de alto nivel (BRICS+, OCS) o adopción legal de tratados de seguridad con fecha de ratificación.

---

## 3. HITOS EJECUTADOS / CONSUMIDOS (AUDITORÍAS W36–W38)

| ID / Hito | Fecha real | Resultado primario verificado | Evento / Vector | Resolución | Acción tomada |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **US ISM Manufacturing PMI** | Periodo: agosto 2026; publicación: 2026-09-01 | PMI **54,6** frente a 55,6 en julio; precios **71,1**. Fuente: [ISM, agosto 2026](https://www.ismworld.org/supply-management-news-and-reports/reports/ism-pmi-reports/pmi/august/). Consulta 06/09/2026. | V05 | `NO MATERIAL` para triggers canónicos | Se corrige la falsa contracción: expansión industrial, con menor ritmo. Rectificar la justificación de V05; no activa por sí solo sus triggers seculares. |
| **Japan 30Y JGB Auction** | Subasta y publicación: 2026-09-03 | Issue 91; yield medio **4,079%** y yield de corte **4,100%**; cobertura competitiva **1.728,1 / 456,2 = 3,788x**. Fuente: [MOF, resultado específico](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260903.htm). Consulta 06/09/2026. | Japón · V01 | `NO MATERIAL` para Trigger A | Demanda competitiva superior al volumen adjudicado. La tabla no identifica al comprador final: no prueba por sí sola absorción doméstica ni repatriación. |
| **US International Trade (Julio)** | Periodo: julio 2026; publicación: 2026-09-03 | Déficit de bienes y servicios **$88,6B**, frente a $71,2B en junio revisado. Fuente: [BEA/Census, julio 2026](https://www.bea.gov/news/2026/us-international-trade-goods-and-services-july-2026). Consulta 06/09/2026. | Tariff Stack · V04 | `NO MATERIAL` para Trigger D | Dato agregado anterior a la entrada de Section 338 el 22-ago; no demuestra dos meses de contracción sectorial ni causalidad arancelaria. |
| **US Non-Farm Payrolls (Agosto)** | Periodo: agosto 2026; publicación: 2026-09-04 | Nóminas **+162.000**; paro **4,1%**; salarios **+0,3% mensual / +3,1% anual**; manufacturas **+16.000**. Fuente: [BLS, comunicado archivado](https://www.bls.gov/news.release/archives/empsit_09042026.htm). Consulta 06/09/2026. | V01 · V05 | `NO MATERIAL` para triggers canónicos | Se retira el argumento de pérdida fabril. El dato no descarta por sí solo una recesión ni determina la decisión del FOMC. |
| **OPEC+ Core Meeting** | Reunión y publicación: 2026-09-06 | Los siete participantes mantuvieron para octubre la producción requerida de septiembre y fijaron la siguiente reunión para el 04/10. Fuente: [OPEP, comunicado específico](https://www.opec.org/pr-detail/613-6-september-2026.html). Consulta 12/09/2026. | V02 | `NO MATERIAL` para eventos activos | No altera los triggers físicos o aseguradores de Lloyd’s; se conserva como próximo sensor la reunión de siete participantes del 04/10 (denominación JMMC rectificada en TASK_116). |
| **Canada Counter-Tariffs** | Orden: 2026-09-04; efectiva: 2026-09-08 | La Orden en Consejo **P.C. 2026-0785** hizo efectivos tipos del 15%, 25% y 50% sobre **27.600 M CAD** de importaciones estadounidenses. Fuentes: [Orden](https://orders-in-council.canada.ca/attachment.php?attach=48943&lang=en) y [lista oficial](https://www.canada.ca/en/department-finance/programs/international-trade-finance-policy/canadas-response-us-tariffs/complete-list-us-products-subject-to-counter-tariffs.html). Consulta 12/09/2026. | Tariff Stack · V04 | `MATERIAL` — Trigger B | Trigger B activado; Tariff Stack pasa de → a ↑. La respuesta de EE. UU. genera nuevas ventanas el 15 y 29/09. |
| **Japan Monthly Securities Flows (Agosto)** | Periodo: agosto 2026; publicación: 2026-09-08 | Inversores designados: **−¥143,0B** netos en deuda extranjera a largo plazo y **+¥136,6B** en cartera total. Fuente: [MOF, publicación mensual](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/monthEng.pdf). Consulta 12/09/2026. | Japón/Liquidez · V01 | `NO MATERIAL` para Trigger A | Un mes negativo en deuda larga no completa los dos meses consecutivos; el total de cartera fue positivo y falta verificar 15 días de diferencial cubierto. |
| **US Treasury 10Y/30Y Reopenings** | Subastas: 2026-09-09/10 | El calendario oficial confirma ambas subastas, pero en este corte no se recuperó un documento primario estable con todos los observables —BTC, indirectos, *tail* y *when-issued*— para las dos emisiones. Fuentes: [calendario oficial](https://home.treasury.gov/system/files/221/Tentative-Auction-Schedule.pdf) y [buscador de resultados](https://www.treasurydirect.gov/auctions/auction-query/). Consulta 12/09/2026. | V01 | `NO VERIFICABLE` en esta auditoría | La fila se retira de futuros por vencimiento, sin declarar Trigger 03 ni inferir fallo de absorción. |
| **TSMC Monthly Sales (Agosto)** | Periodo: agosto 2026; publicación: 2026-09-10 | Ingresos **514.806 M NT$**, +10,1% mensual y +53,3% interanual; enero-agosto **3.386.870 M NT$**, +39,3%. Fuente: [TSMC, publicación específica](https://pr.cld.tsmc.com/english/news/3340). Consulta 12/09/2026. | CoWoS · V03 | `NO MATERIAL` para A–D | Confirma demanda agregada, pero no desglosa capacidad CoWoS, AP7, *yields*, entregas Blackwell ni *lead times*. |
| **ECB Monetary Policy Decision** | Decisión: 2026-09-10; efectiva: 2026-09-16 | Alza de 25 pb: depósito **2,50%**, MRO **2,65%** y marginal **2,90%**. Fuente: [BCE, decisión específica](https://www.ecb.europa.eu/press/pr/date/2026/html/ecb.mp260910~314e508016.en.html). Consulta 12/09/2026. | V01 | `MATERIAL` como señal de tipos; sin trigger de evento | Endurece el punto de partida europeo y justifica admitir la reunión del 28–29/10 por su canal a coste soberano y fragmentación; no modifica por sí solo la carga primaria. |
| `E_2026_09_15_US_Section338_Product_Changes` | 15/09; publicación FR 14/09 | Acto jurídico efectivo; no auditoría de recaudación por producto. [FR 2026-18839](https://www.govinfo.gov/content/pkg/FR-2026-09-14/pdf/2026-18839.pdf) | V04 / Tariff | `MATERIAL` | Continuidad jurídica; no nueva activación ni transmisión C–E. |
| `E_2026_09_15_US_Corporate_Tax_TGA_Drain` | 15/09; H.4.1 observado 16/09 y publicado 17/09 | TGA 991,708 B$; reservas 2.921,536 B$; impuestos corporativos 51,579 B$. [H.4.1](https://www.federalreserve.gov/releases/h41/Current/) / [DTS](https://api.fiscaldata.treasury.gov/services/api/fiscal_service/v1/accounting/dts/deposits_withdrawals_operating_cash?filter=record_date:eq:2026-09-15&page[size]=500) | V01 / Japón | `MATERIAL` | B parcial: umbral y tiempo sí; causalidad completa no. Tendencia ↑. |
| `E_2026_09_15_EU_Russia_Sanctions_Renewal` | 15/09 | Prórroga solo hasta 22/09 por Decisión 2026/2103. [Acto oficial](https://eur-lex.europa.eu/eli/dec/2026/2103/oj/eng/pdf) | V06 | `MATERIAL` | Nueva ventana 22/09; sin evento ni carga adicionales. |
| `E_2026_09_16_Fed_FOMC_Decision` | 16/09; implementación 17/09 | Alza 25 pb, rango 3,75–4%; IORB 3,90%; SEP prospectivo. [FOMC](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260916a.htm) / [implementación](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260916a1.htm) | V01 | `MATERIAL` | Actualizar diferencial y contraevidencia de TESIS_01; sin trigger automático. |
| `E_2026_09_16_US_TIC_Securities_Data` | Julio; publicación 16/09 | Entrada agregada 83,7 B$; stock Japón 1.103,9 B$, variación −12,8 B$. [TIC](https://home.treasury.gov/news/press-releases/sb0631/) / [stock](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table5.html) | V01 / Japón | `NO MATERIAL para activar A` | Resultado estadístico verificado; flujos japoneses comparables y diferencial cubierto NO VERIFICABLES completos. |
| `E_2026_09_18_BoJ_MPM` | 18/09; implementación 24/09 futura | Decisión 7–2 de elevar a 1,25%. [BoJ](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf) | V01 / Japón | `MATERIAL` | Actualizar decisión; conservar 1,00% vigente al corte y crear ventana de implementación. |

Consulta de las seis resoluciones W38: 19/09/2026; documentos publicados antes del corte. Diez resoluciones anteriores conservan sus fechas de contraste.

---

## 4. COBERTURA POR VECTOR

| Vector | Filas | Observación |
|:---|---:|:---|
| V01 | 12 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| V02 | 1 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| V03 | 3 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| V04 | 3 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| V05 | 0 | Hueco real: sin hitos admitidos que resuelvan sus triggers seculares. |
| V06 | 2 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| **Total** | **21** | **1 Régimen / 7 Crítico / 9 Elevado / 4 Latente** |

## 5. COBERTURA POR EVENTO ACTIVO

| Evento | Próximo sensor | Cobertura y límite |
|:---|:---|:---|
| Japón/liquidez | BoJ 24/09; cierre 25–30/09; MOF 08/10 | B parcial; SOFR diario publicado y SRF; faltan diferencial cubierto y flujos mensuales completos |
| Grid | Observatorio DOE/FERC/PJM/ERCOT | Orden 45 admitida; A–F requieren sujetos, magnitudes y duraciones; D–F sin verificación suficiente |
| CoWoS | Micron 30/09; TSMC 08/10 y 10/11 | Demanda agregada no sustituye AP7/yields/lead times |
| Lloyd’s | Observatorio OMI/JWC/UKMTO | Recuento y circular verificados; primas, flujos y daños tipificados incompletos |
| Tariff Stack | 29/09; comercio agosto/septiembre según calendario provisional | Separar norma, aplicación y transmisión C–E |

## 6. HUECOS REALES DE COBERTURA

V05 no tiene hitos admitidos en la ventana. Los incidentes marítimos, restricciones de red y anuncios de capacidad son observatorios sin fecha inventada. No se añaden filas hasta el 18/11 solo para llenar el horizonte. La visita Xi–EE. UU. sigue en cuarentena por fecha no verificada en este corte. No hay monitorización continua implícita.

## 7. Respaldo documental y límites de verificación

**Corte:** 2026-09-19 05:29 Europe/Madrid. Horizonte 19/09–18/11 inclusive: 60 días transcurridos, 61 fechas. Una ventana iniciada el 09/09 se conserva porque termina el 04/11. Las filas restantes no han vencido por su fecha final.

- **Reconciliación:** 25 anteriores − 6 consumidas + 2 nuevas = **21**. Dieciséis resoluciones acumuladas, cero ventanas enriquecidas y cuatro observatorios. Doce campos por fila y 21 IDs únicos; presencia de fuentes no es certificación factual total.
- **Nuevas fechas:** UE 22/09 y BoJ 24/09, documentos específicos en tabla. Micron 30/09, OPEP+ 04/10, TIC 16/10, calendarios MOF y TSMC se recontrastan. TSMC mantiene advertencia de provisionalidad.
- **Calendarios monetarios:** [Fed](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm), [BoJ 2026](https://www.boj.or.jp/en/mopo/mpmsche_minu/m_ref/mref250731a.pdf) y [BCE](https://www.ecb.europa.eu/press/calendars/mgcgc/html/index.en.html), consulta 19/09. Confirmar una reunión no confirma su resultado.
- **Comprobación adicional de los siete calendarios heredados:** fechas de comercio 06/10 y 04/11 confirmadas por Census; recompras 09/09–04/11 por Tesoro 19/08; financiación 02/11 y Refunding 04/11 por el calendario vigente del Tesoro; elecciones 03/11 por FEC. Las subastas 07–08/10 figuran en el PDF tentativo del Tesoro y conservan PROVISIONAL. Fuentes específicas sustituidas en las siete filas, consulta 19/09. Son verificaciones de fechas, no resultados futuros.
- **OPEP+:** el antiguo ID `E_2026_10_04_OPEC_Plus_JMMC` se sustituye por `E_2026_10_04_OPEC_Plus_Seven_Countries`, corrigiendo actor, observables y tesis. La fuente confirma siete participantes, no una 68ª JMMC.
- **No anticipación:** el plazo UE del 22/09 no prueba una renovación futura; la implementación BoJ del 24/09 no es un alza ya efectiva; el 29/09 arancelario sigue futuro.

Fuentes y criterios completos en [[ACTUALIZACION_SEMANAL_231_2026_09_20]]. Los textos rectificados de revisiones anteriores conservan carácter histórico.

### Rectificaciones fechadas — TASK_090

El 06/09/2026 se sustituyeron en el estado vivo los NFP +142.000 / paro 4,2% / salarios +0,4% y +3,8% y el ISM 47,2 / precios 54,0, correspondientes a agosto de 2024 ([BLS 2024](https://www.bls.gov/news.release/archives/empsit_09062024.htm); [ISM 2024](https://www.ismworld.org/supply-management-news-and-reports/news-publications/inside-supply-management-magazine/blog/2024/2024-093/rob-roundup-august-2024-manufacturing-pmi/)). No se usan para diagnosticar 2026. Se corrigió además el déficit de julio de $78,8B a $88,6B con BEA. La versión previa se conserva íntegra en [[Radar_Eventos_2026_09__PRE_TASK090]] y no alimenta estados vigentes.

**Regla de reutilización:** dato + unidad + periodo observado + fecha de publicación + documento específico + fecha de consulta. Si falta respaldo, marcarlo pendiente; las inferencias deben identificarse como tales. Una actualización de formato o enlaces no renueva automáticamente la fecha de contraste factual.
