# RADAR DE EVENTOS — SEPTIEMBRE 2026

> **Versión:** 2.6 — TASK_148, precierre W39 reconciliado el 27-sep.
> **Corte de evidencia nueva:** 26/09/2026 20:48 Europe/Madrid; aplicación 27-sep. Calendarios: fuentes y fecha de contraste diferenciadas en §7; no se anticipan resultados.
> **Horizonte objetivo:** 26/09 → 25/11 inclusive (+60 días). 60 días transcurridos, 61 fechas; ventanas anteriores incluidas solo si terminan dentro del horizonte.
> **Filas abiertas:** 24 · **Prioridades:** 1 Régimen / 6 Crítico / 13 Elevado / 4 Latente.
> **Ventanas enriquecidas:** 0 · **Observatorios:** 6 · **Resoluciones acumuladas:** 19.

## TABLA DE HITOS CALENDARIZADOS

| ID | Fecha / ventana | Confirmación | Actor | Tipo | Vector | Evento sensor | Tesis | Observable / Trigger | Prioridad | Descripción factual | Fuente |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `E_2026_09_09_US_Treasury_Long_End_Buybacks` | 2026-09-09/2026-11-04 | CONFIRMADO | U.S. Treasury / NY Fed | Operación de liquidez | V01 | V01 — Absorción y liquidez de deuda | TESIS_01_Dominancia_Fiscal | Volumen anunciado, ofertado y aceptado por tramo; distinguir tamaño autorizado de adjudicación efectiva; bid-ask y liquidez off-the-run | ELEVADO | Ventana iniciada el 09/09, aún en curso hasta el 04/11; la recompra del Tesoro no equivale a QE. | [Tesoro, anuncio 19/08](https://home.treasury.gov/news/press-releases/sb0607) |
| `E_2026_09_30_US_Quarter_End_Liquidity` | 2026-09-25/2026-09-30 | RECURRENTE OFICIAL | Fed / NY Fed / Dealers | Cierre regulatorio | V01 | Japón/Liquidez — Trigger D | TESIS_01_Dominancia_Fiscal | 1) Uso del Standing Repo Facility (SRF > $20B diarios durante >2 días); 2) Spread SOFR frente a IORB; 3) Dispersión en percentil 99 de repo tri-party; 4) Saldo ON RRP | CRÍTICO | Ventana de observación del cierre Q3. Posible tensión de intermediación, que debe medirse; no se da por ocurrida. | [NY Fed Markets Data](https://www.newyorkfed.org/markets/reference-rates) |
| `E_2026_09_27_Craig_202c_Effective` | 2026-09-27 | CONFIRMADO | DOE / SPP | Vigencia normativa | V02 | Grid — sensor general | TESIS_06_IA_como_silicio_y_energia | Disponibilidad de Craig1; distinguir vigencia de despacho y obligación CPD | ELEVADO | Orden49 publicada25-sep, efectiva27-sep–25-dic; futura al corte. | [DOE49](https://www.energy.gov/documents/doe-order-no-202-26-49) |
| `E_2026_09_29_US_Section338_Import_Bans` | 2026-09-29 | CONFIRMADO | Casa Blanca / CBP | Entrada en vigor de prohibiciones | V04 | Tariff Stack — continuación de A/B | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Productos canadienses efectivamente prohibidos; 2) Alcance jurídico; 3) Exenciones o licencias; 4) Evidencia de aplicación aduanera | CRÍTICO | Segunda fecha de ejecución de la respuesta estadounidense: entrada de determinadas prohibiciones de importación previstas en las proclamaciones Section 338 del 08/09. | [White House — respuesta a Canadá](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/) |
| `E_2026_09_30_Micron_FY26_Q4_Earnings` | 2026-09-30 | CONFIRMADO | Micron Technology | Resultados corporativos | V03 | CoWoS — Sensor HBM | TESIS_06_IA_como_silicio_y_energia | 1) Horizonte de venta agotada (sold-out) en HBM3E y progreso de validación de HBM4; 2) Guía de CAPEX fabril FY2027; 3) Rendimiento de memoria para aceleradores | ELEVADO | Resultados del 4T fiscal de Micron. Termómetro directo del estrangulamiento de memoria de alto ancho de banda (HBM) en la cadena de suministro de hardware de IA. | [Convocatoria oficial, 30/09 14:30 Mountain](https://investors.micron.com/news/press-release/2026/Micron-Technology-to-Report-Fiscal-Fourth-Quarter-Results-on-September-30-2026/default.aspx) |
| `E_2026_10_01_Japan_Weekly_Securities_Flows` | 2026-10-01 | RECURRENTE OFICIAL | MOF Japón | Estadística de flujos | V01 | Japón — Trigger A | TESIS_01_Dominancia_Fiscal | Compras netas de deuda exterior; semanas13–19 y20–26-sep, no reemplazan dos meses | ELEVADO | Publicación conjunta de dos semanas según calendario; no anticipar signo. | [MOF calendario](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm) |
| `E_2026_10_04_OPEC_Plus_Seven_Countries` | 2026-10-04 | CONFIRMADO | Siete países participantes OPEP+ | Reunión de producción | V02 | NINGUNO — Sensor V02 | TESIS_04_Multipolaridad_Logistica | Niveles de producción, compensación y decisión para el mes siguiente | LATENTE | Siguiente reunión anunciada el 06/09 por siete participantes. No se identifica como 68ª JMMC. | [OPEP, comunicado 06/09](https://www.opec.org/pr-detail/613-6-september-2026.html) |
| `E_2026_10_06_US_International_Trade_August` | 2026-10-06 | CONFIRMADO | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Identificar categorías aranceladas; 2) Variación interanual (YoY); 3) Comprobar si caída supera -15% YoY (posible mes 1); 4) Déficit bilateral | ELEVADO | Primer dato comercial post-arancel susceptible de constituir mes 1 del Trigger D si las importaciones en sectores cubiertos caen >15% YoY según Census/BEA. | [Census, calendario FT900 2026](https://www.census.gov/foreign-trade/schedule.html) |
| `E_2026_10_07_08_US_Treasury_10Y_30Y_Reopenings` | 2026-10-07/2026-10-08 | PROVISIONAL | U.S. Treasury | Subasta soberana | V01 | V01 — Absorción soberana de duración | TESIS_01_Dominancia_Fiscal | Bid-to-cover <2,30 en dos emisiones sucesivas verificadas; tail frente a when-issued y asignación indirecta. No presuponer el resultado de septiembre. | LATENTE | Reapertura de subastas a 10 y 30 años de octubre. Contraste de persistencia de absorción para evaluar si se consuma el Trigger 03 de V01 (<2,30x en 2 emisiones). | [Tesoro, calendario tentativo de subastas](https://home.treasury.gov/system/files/221/Tentative-Auction-Schedule.pdf) |
| `E_2026_10_08_Japan_Monthly_Securities_Flows_September` | 2026-10-08 | RECURRENTE OFICIAL | Ministerio de Finanzas de Japón | Estadística de flujos | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Compras netas de deuda extranjera a largo plazo; 2) Signo del total de cartera; 3) Comparación con agosto (−¥143,0B en deuda larga); 4) Confirmar o negar segundo mes negativo | CRÍTICO | Publicación mensual de septiembre. Puede completar el componente de dos meses consecutivos del Trigger A, pero todavía exige verificar el diferencial cubierto durante 15 días. | [MOF Japan — calendario de publicación](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm) |
| `E_2026_10_08_TSMC_September_Sales` | 2026-10-08 | PROVISIONAL | TSMC | Ingresos corporativos | V03 | V03 — Ciclo de fundición y demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación mensual en NT$; 2) Crecimiento YoY; 3) Cierre consolidado del 3T vs guidance trimestral (inferencia); 4) Variación acumulada 2026 | LATENTE | Facturación de septiembre y cierre trimestral de TSMC. Sensor agregado de demanda; no desglosa nodos 3nm/5nm ni cuellos de botella CoWoS/HBM. | [Calendario TSMC, sujeto a cambios](https://investor.tsmc.com/english/financial-calendar) |
| `E_2026_10_15_TSMC_Q3_Results` | 2026-10-15 | PROVISIONAL | TSMC | Resultados corporativos | V03 | CoWoS — guía y capacidad | TESIS_06_IA_como_silicio_y_energia | Ingresos y guía; buscar datos explícitos de capacidad, yields y entregas | ELEVADO | Resultados Q3 programados, sujetos a cambio; guía no es capacidad observada. | [TSMC calendario](https://investor.tsmc.com/english/financial-calendar) |
| `E_2026_10_16_US_TIC_Securities_Data` | 2026-10-16 | RECURRENTE OFICIAL | U.S. Treasury | Estadística financiera | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | Flujos japoneses comparables y composición; distinguir stock de transacciones y comprobar los >15 días hábiles de diferencial cubierto | CRÍTICO | Datos de agosto; no se presume julio negativo por el descenso del stock. | [TIC julio: siguiente publicación 16/10](https://home.treasury.gov/news/press-releases/sb0631/) |
| `E_2026_10_20_Loudoun_Data_Centers_Resolution` | 2026-10-20 | ANUNCIADO | Loudoun Board | Decisión regulatoria | V02 | Grid — Trigger A | TESIS_06_IA_como_silicio_y_energia | Adopción, alcance, sujeto y MW de eventual pausa; distinguir urbanismo de energía | ELEVADO | Consideración de resolución de pausa legislativa; no adoptada al corte ni aplicable automáticamente a trámites administrativos. | [Loudoun17-sep, actualizado24-sep](https://www.loudoun.gov/m/newsflash/home/detail/10874) |
| `E_2026_10_28_Fed_FOMC_Decision` | 2026-10-27/2026-10-28 | CONFIRMADO | Reserva Federal | Decisión monetaria | V01 | V01 — Política monetaria | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre tipo de fondos federales; 2) Tono del comunicado sobre riesgos de empleo e inflación; 3) Mensaje sobre estabilidad de reservas antes de elecciones | ELEVADO | Reunión de política monetaria intermedia (sin SEP). Calibra las condiciones de liquidez monetaria una semana antes de las elecciones legislativas estadounidenses. | [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| `E_2026_10_29_ECB_Monetary_Policy` | 2026-10-28/2026-10-29 | CONFIRMADO | Banco Central Europeo | Decisión monetaria | V01 | NINGUNO — sensor de tipos y fragmentación V01 | TESIS_01_Dominancia_Fiscal | 1) Tipos de depósito/MRO/marginal frente a 2,50%/2,65%/2,90%; 2) Orientación de balance; 3) Referencias operativas a fragmentación o spreads soberanos; 4) Instrumentos de transmisión | ELEVADO | Primera decisión del BCE posterior al alza del 10/09. Se admite por su canal directo a coste soberano y fragmentación, no como reunión rutinaria automática. | [ECB — calendario del Consejo de Gobierno](https://www.ecb.europa.eu/press/calendars/mgcgc/html/index.en.html) |
| `E_2026_10_30_BoJ_MPM_Outlook` | 2026-10-29/2026-10-30 | CONFIRMADO | Banco de Japón | Decisión monetaria | V01 | Japón/Liquidez — Carry trade | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre objetivo del tipo overnight; 2) Proyecciones plurianuales de PIB e inflación 2026–2027 en el Outlook Report; 3) Evaluación del tipo de cambio | ELEVADO | Reunión trimestral con Outlook Report del BoJ. Determina la trayectoria esperada de tipos de interés para finales de 2026 e inicios de 2027. | [Bank of Japan Releases](https://www.boj.or.jp/en/mopo/mpmsche_minu/index.htm) |
| `E_2026_11_02_US_Treasury_Financing_Estimates` | 2026-11-02 | CONFIRMADO | U.S. Treasury | Estimación financiera | V01 | V01 — Necesidades de endeudamiento | TESIS_01_Dominancia_Fiscal | 1) Estimación oficial de endeudamiento neto para el 4T 2026 y 1T 2027; 2) Saldo objetivo de caja TGA al cierre de año; 3) Proporción estimada bills vs cupones | ELEVADO | Publicación de necesidades de financiación previas al Refunding. Fija la escala de liquidez requerida por el Tesoro de los mercados primarios. | [Tesoro, próximas publicaciones 02/11 y 04/11](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/most-recent-quarterly-refunding-documents/) |
| `E_2026_11_03_US_Midterm_Elections` | 2026-11-03 | CONFIRMADO | Electorado de EE. UU. / Congreso | Elección política | V06 | [[Evento_E0_2026_11_03_Midterms_EEUU]] | TESIS_01_Dominancia_Fiscal, TESIS_04_Multipolaridad_Logistica | 1) Mayorías parlamentarias en Cámara y Senado; 2) Margen legislativo para sostener o modificar aranceles; 3) Perspectiva sobre prórroga fiscal y techo de deuda en 2027 | ELEVADO | Elecciones de mitad de mandato en EE. UU. Condicionan la arquitectura fiscal y el margen de ejecución de la política comercial y regulatoria federal. | [FEC, fecha de elecciones federales 2026](https://www.fec.gov/introduction-campaign-finance/election-results-and-voting-information/) |
| `E_2026_11_04_US_International_Trade_September` | 2026-11-04 | CONFIRMADO | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Comprobar si septiembre presenta caída >15% YoY en sectores cubiertos Y si agosto ya cumplió >15% YoY; 2) Activación completa de Trigger D | CRÍTICO | Balanza comercial de septiembre. Punto resolutivo para la activación formal del Trigger D si se encadenan dos meses consecutivos con caída >15% YoY. | [Census, calendario FT900 2026](https://www.census.gov/foreign-trade/schedule.html) |
| `E_2026_11_04_US_Treasury_Quarterly_Refunding` | 2026-11-04 | CONFIRMADO | U.S. Treasury | Emisión soberana | V01 | V01 — Política de emisión y colateral | TESIS_01_Dominancia_Fiscal | 1) Tamaños de subastas en tramos 2Y, 5Y, 10Y y 30Y; 2) Cuota de financiación vía T-Bills respecto a deuda cupón; 3) Decisión sobre el programa de buybacks; 4) Informe TBAC | RÉGIMEN | Anuncio formal de política de refinanciación de la deuda de EE. UU. Determina si el tramo largo de la curva soberana sufre sobresaturación o racionamiento de colateral. | [Tesoro, próximas publicaciones 02/11 y 04/11](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding/most-recent-quarterly-refunding-documents/) |
| `E_2026_11_10_Japan_Monthly_Securities_Flows_October` | 2026-11-10 | RECURRENTE OFICIAL | Ministerio de Finanzas de Japón | Estadística de flujos | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Compras netas de deuda extranjera a largo plazo; 2) Persistencia mensual; 3) Composición por tipo de activo; 4) Contraste con septiembre y agosto | CRÍTICO | Publicación mensual de octubre. Comprueba si una eventual secuencia de desinversión exterior persiste; no sustituye el requisito del diferencial cubierto. | [MOF Japan — calendario de publicación](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm) |
| `E_2026_11_10_TSMC_October_Sales` | 2026-11-10 | PROVISIONAL | TSMC | Ingresos corporativos | V03 | CoWoS — sensor agregado de demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación mensual en NT$; 2) Crecimiento interanual; 3) Acumulado enero-octubre; 4) Trayectoria frente a guía trimestral como inferencia | LATENTE | Extiende el horizonte hasta noviembre con un sensor agregado comparable. No mide capacidad CoWoS, *yields*, AP7 ni entregas físicas de aceleradores. | [Calendario TSMC, sujeto a cambios](https://investor.tsmc.com/english/financial-calendar) |
| `E_2026_11_20_Eddystone_202c_Expiry` | 2026-11-20 | CONFIRMADO | DOE / PJM | Vencimiento normativo | V02 | Grid — recurrencia regulatoria | TESIS_06_IA_como_silicio_y_energia | Prórroga, sustitución o expiración de orden40; no inferir apagón | ELEVADO | Fin previsto de disponibilidad Eddystone3/4 según orden40; no anticipar decisión. | [DOE40](https://www.energy.gov/documents/doe-order-no-202-26-40) |

---

## 1. VISITA XI — VENTANA RESUELTA, EJECUCIÓN EN SEGUIMIENTO

El hito del 24-sep se retira de futuros: confirmado por comunicado chino del 25-sep y comunicado estadounidense. [[Evento_E0_2026_09_19_Visita_Xi_EEUU]] conserva E0 para comprobar implementación. Anuncios institucionales materiales no equivalen a ejecución de rebajas, flujos o canal de incidentes. Resolución y fuentes debajo.

<details>
<summary>Decisión W37 y corte técnico W38: cuarentena, sustituida por TASK_118</summary>

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

</details>

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

### 5. Observatorio industrial y automoción — C4 + C24

- **Sede canónica:** [[VECTOR_05_Transformacion_industrial_y_demografia#Observatorio industrial y automoción — C4 + C24]].
- **Decisión:** Luis, 19/09; un observatorio, sin evento ni carga propia.
- **Panel:** unidades BEV/PHEV, ventas por marca, cuota, escala UE, producción/exportación, saldo comercial y capacidad/empleo. Series con periodo, universo y fuente; ND visible.
- **Registro breve:** modelos, precios, fábricas, reconversiones y contratos; distinguir anuncio y ejecución.
- **Robótica:** [[Evento_E0_2026_09_19_Robotica_Unitree]], E0 en observación; sin inventar fecha de hito.
- **Revisión:** novedades útiles en la revisión semanal y series cuando publiquen; proponer ficha si surge un caso delimitado o Luis lo prioriza. No automatización continua.

### 6. Observatorio de financiación y rentabilidad del CAPEX IA — C22

- **Sede canónica:** [[VECTOR_01_Arquitectura_monetaria_global#Observatorio de financiación y rentabilidad del CAPEX IA — C22]].
- **Decisión:** Luis, 27-sep; observatorio sin ficha ni carga propia.
- **Panel:** caja operativa, CAPEX bruto/ajustado, anticipos, deuda/vencimientos, utilización y retorno por emisor y trimestre.
- **Límite:** cifras Oracle publicadas 10-sep son antecedentes; un emisor no representa al sector ni prueba insolvencia.
- **Revisión:** semanal; proponer evento solo ante episodio financiero delimitado. No fecha artificial ni automatización.

## 3. HITOS EJECUTADOS / CONSUMIDOS (AUDITORÍAS W36–W39)

| ID / Hito | Fecha real | Resultado primario verificado | Evento / Vector | Resolución | Acción tomada |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `E_2026_09_22_EU_Russia_Sanctions_Expiry` | 22/09/2026 | Prórroga de listados individuales por 36 meses hasta 22-sep-2029. [Consejo UE, 22-sep](https://www.consilium.europa.eu/en/press/press-releases/2026/09/22/ukraine-s-territorial-integrity-eu-extends-individual-listings-for-further-three-years/), consulta 26-sep. No todos los regímenes de sanciones. | V06 | `MATERIAL` institucional | Registrar continuidad jurídica; sin evento adicional ni carga automática. |
| `E_2026_09_24_BoJ_Rate_Effective` | 24/09/2026, fecha efectiva del acto | Entrada en vigor del objetivo 1,25% según [decisión BoJ 18-sep](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf), recontrastada 26-sep; no medición del tipo efectivo transado. | V01 / Japón | `MATERIAL` normativo | Resolver fecha vencida; no duplicar carga de la decisión ni declarar estrés repo. |
| `E_2026_09_24_Visita_Xi_US` | 24/09; comunicado 25/09 | [Fuente china](https://eu.china-mission.gov.cn/eng/mhs/202609/t20260925_12031181.htm) confirma conversaciones; [Casa Blanca](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-advances-a-fair-and-reciprocal-relationship-with-china-while-hosting-historic-state-visit/) anuncia mecanismos y recomendaciones. Consulta 26-sep. | Xi / V06 | `MATERIAL` por anuncios | Mantener E0 y observar ejecución; sin E1 automático. |
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
| V02 | 4 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| V03 | 4 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| V04 | 3 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| V05 | 0 | Sin fecha calendarizada; cubierto por Unitree E0 y observatorio industrial. |
| V06 | 1 | Sensores calendarizados; cobertura complementada por fichas y observatorios cuando corresponde. |
| **Total** | **24** | **1 Régimen / 6 Crítico / 13 Elevado / 4 Latente** |

## 5. COBERTURA POR EVENTO ACTIVO

| Evento | Próximo sensor | Cobertura y límite |
|:---|:---|:---|
| Japón/liquidez | Cierre 25–30/09; MOF 01/10 y 08/10 | B parcial; SOFR diario publicado y SRF; faltan diferencial cubierto y flujos mensuales completos |
| Grid | Craig 27/09; Loudoun 20/10; Eddystone 20/11; observatorio DOE/FERC | Órdenes 46–49 contrastadas; no obligación CPD acreditada; Loudoun es consideración futura |
| CoWoS | Micron 30/09; TSMC 08/10, 15/10 y 10/11 | Demanda agregada no sustituye AP7/yields/lead times |
| Lloyd’s | Observatorio OMI/JWC/UKMTO | Recuento y circular verificados; primas, flujos y daños tipificados incompletos |
| Tariff Stack | 29/09; comercio 06/10 y 04/11 según calendario Census contrastado 19/09 | Separar norma, aplicación y transmisión C–E |
| Xi–EE. UU. | Ejecución de acuerdos, sin nueva fecha exacta | [[Evento_E0_2026_09_19_Visita_Xi_EEUU]]; visita confirmada, implementación pendiente |
| Midterms | 03/11, FEC | [[Evento_E0_2026_11_03_Midterms_EEUU]]; seguimiento de expectativas y resultado |
| Robótica / Unitree | Sin fecha fijada | [[Evento_E0_2026_09_19_Robotica_Unitree]]; entregas, uso productivo y economía, sin mezclar fases |
| Francia | Rendimientos/diferencial comparable y subastas | [[Evento_E0_2026_09_26_Deuda_Francesa_y_Fragmentacion_Europea]]; proxy no equivale a spread homogéneo |
| Gas europeo | Almacenamiento, flujos y demanda | [[Evento_E0_2026_09_26_Gas_Europeo_Invierno]]; instantánea no prueba de escasez |
| Chips chinos | Entregas/uso; previsión comercial Q1 2027 | [[Evento_E0_2026_09_26_Chips_Chinos_Alibaba]]; Q1 fuera de 60 días, sin fecha próxima inventada |

## 6. HUECOS REALES DE COBERTURA

V05 sigue sin hitos calendarizados; Unitree y el observatorio industrial aportan sensores sin fecha artificial. Francia y gas tienen observación de series; el anuncio Alibaba apunta a Q1 2027, fuera del horizonte. La revisión cubre el horizonte hasta 25-nov con hitos localizados hasta20-nov; no certifica exhaustividad ni inventa un hito en el último día. No hay monitorización continua implícita.

## 7. Respaldo documental y límites

Aplicación 27-sep; corte fijo26-sep20:48. **22 previas −3 resueltas +5 nuevas =24 abiertas**; 16+3=19 resoluciones; seis observatorios y cero ventanas enriquecidas. Doce campos por fila e IDs únicos. Nuevas: Craig27-sep, MOF1-oct, TSMC15-oct, Loudoun20-oct y Eddystone20-nov. Prioridades: 1 Régimen / 6 Crítico / 13 Elevado / 4 Latente.

Consultas26–27-sep: MOF, TSMC, DOE, Loudoun, FEC, TIC y actos arancelarios. Se conservan con contraste19-sep los calendarios Fed/BoJ/BCE, OPEP+, Micron, Census, subastas tentativas, buybacks y Refunding, documentados en el historial inferior. Las fechas provisionales siguen provisionales; no se presenta como nueva verificación lo meramente heredado. El calendario de fuente es prospectivo; no se incorpora un resultado posterior al corte. [[ACTUALIZACION_SEMANAL_231_2026_09_27]].

<details>
<summary>Respaldo y límites del corte anterior — histórico, fechas vencidas resueltas arriba</summary>

## 7. Respaldo documental y límites de verificación

**Corte técnico heredado:** 2026-09-19 05:29 Europe/Madrid; adenda selectiva TASK_118 con fuentes consultadas hasta 14:24. Horizonte 19/09–18/11 inclusive: 60 días transcurridos, 61 fechas. Una ventana iniciada el 09/09 se conserva porque termina el 04/11. Las filas restantes no han vencido por su fecha final.

- **Reconciliación:** corte técnico 25 − 6 + 2 = 21; piloto humano +1 Xi = **22**. Dieciséis resoluciones, cero ventanas enriquecidas y cinco observatorios. Doce campos y 22 IDs únicos. Midterms enlaza su ficha sin duplicar fila; Unitree carece de fecha artificial. Fuentes presentes no equivalen a verificación completa.
- **Nuevas fechas:** UE 22/09 y BoJ 24/09, documentos específicos en tabla. Micron 30/09, OPEP+ 04/10, TIC 16/10, calendarios MOF y TSMC se recontrastan. TSMC mantiene advertencia de provisionalidad.
- **Calendarios monetarios:** [Fed](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm), [BoJ 2026](https://www.boj.or.jp/en/mopo/mpmsche_minu/m_ref/mref250731a.pdf) y [BCE](https://www.ecb.europa.eu/press/calendars/mgcgc/html/index.en.html), consulta 19/09. Confirmar una reunión no confirma su resultado.
- **Comprobación adicional de los siete calendarios heredados:** fechas de comercio 06/10 y 04/11 confirmadas por Census; recompras 09/09–04/11 por Tesoro 19/08; financiación 02/11 y Refunding 04/11 por el calendario vigente del Tesoro; elecciones 03/11 por FEC. Las subastas 07–08/10 figuran en el PDF tentativo del Tesoro y conservan PROVISIONAL. Fuentes específicas sustituidas en las siete filas, consulta 19/09. Son verificaciones de fechas, no resultados futuros.
- **OPEP+:** el antiguo ID `E_2026_10_04_OPEC_Plus_JMMC` se sustituye por `E_2026_10_04_OPEC_Plus_Seven_Countries`, corrigiendo actor, observables y tesis. La fuente confirma siete participantes, no una 68ª JMMC.
- **No anticipación:** el plazo UE del 22/09 no prueba una renovación futura; la implementación BoJ del 24/09 no es un alza ya efectiva; el 29/09 arancelario sigue futuro.

Fuentes y criterios completos en [[ACTUALIZACION_SEMANAL_231_2026_09_20]]. Los textos rectificados de revisiones anteriores conservan carácter histórico.

### Rectificaciones fechadas — TASK_090

El 06/09/2026 se sustituyeron en el estado vivo los NFP +142.000 / paro 4,2% / salarios +0,4% y +3,8% y el ISM 47,2 / precios 54,0, correspondientes a agosto de 2024 ([BLS 2024](https://www.bls.gov/news.release/archives/empsit_09062024.htm); [ISM 2024](https://www.ismworld.org/supply-management-news-and-reports/news-publications/inside-supply-management-magazine/blog/2024/2024-093/rob-roundup-august-2024-manufacturing-pmi/)). No se usan para diagnosticar 2026. Se corrigió además el déficit de julio de $78,8B a $88,6B con BEA. La versión previa se conserva íntegra en [[Radar_Eventos_2026_09__PRE_TASK090]] y no alimenta estados vigentes.

**Regla de reutilización:** dato + unidad + periodo observado + fecha de publicación + documento específico + fecha de consulta. Si falta respaldo, marcarlo pendiente; las inferencias deben identificarse como tales. Una actualización de formato o enlaces no renueva automáticamente la fecha de contraste factual.

</details>

<details>
<summary>Filas originales de las tres ventanas resueltas en W39</summary>

| `E_2026_09_22_EU_Russia_Sanctions_Expiry` | 2026-09-22 | CONFIRMADO | Consejo de la Unión Europea | Vencimiento normativo | V06 | NINGUNO — sensor V06 | TESIS_04_Multipolaridad_Logistica | Nuevo acto de prórroga, modificación o expiración de medidas individuales; comprobar alcance y fecha | ELEVADO | La Decisión 2026/2103 solo extiende vigencia hasta 22/09; no anticipa otra renovación. | [Decisión 2026/2103](https://eur-lex.europa.eu/eli/dec/2026/2103/oj/eng/pdf) |
| `E_2026_09_24_BoJ_Rate_Effective` | 2026-09-24 | CONFIRMADO | Banco de Japón | Entrada efectiva de tipos | V01 | Japón/liquidez — carry | TESIS_01_Dominancia_Fiscal | Implementación del objetivo 1,25% y comparación de diferencial; no usar tipos oficiales como retorno 30Y cubierto | CRÍTICO | Vigencia anunciada el 18/09; evento de decisión consumido y ventana de implementación separada, sin doble carga. | [BoJ, decisión y anexo](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf) |
| `E_2026_09_24_Visita_Xi_US` | 2026-09-24 | ANUNCIADO — fuente secundaria | Xi Jinping / Presidencia EE. UU. | Visita bilateral | V06 | [[Evento_E0_2026_09_19_Visita_Xi_EEUU]] | TESIS_04_Multipolaridad_Logistica | Confirmación de agenda; compromisos, ejecución y cambio de relación bilateral; evitar doble carga arancelaria | ELEVADO | Admitido por Luis; 24/09 según Le Monde atribuido a Casa Blanca. Fecha primaria pendiente; resultado futuro. | [Le Monde, 02/09](https://www.lemonde.fr/en/international/article/2026/09/02/china-s-xi-embarks-on-diplomatic-marathon-from-regimes-hostile-to-the-west-to-the-white-house_6757085_4.html) |

</details>
