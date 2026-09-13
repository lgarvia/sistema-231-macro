# RADAR DE EVENTOS — SEPTIEMBRE 2026 (RADAR 2.0)

> **Versión:** 2.2 — W37, reconciliación TASK_099 fase 3  
> **Fecha de corte y generación:** 2026-09-12 21:21 Europe/Madrid (precierre W37)  
> **Horizonte temporal canónico:** 2026-09-12 → 2026-11-11 inclusive (60 días)  
> **Filas en tabla calendarizada:** 25  
> **Distribución por prioridad:** Régimen: 1 | Crítico: 10 | Elevado: 9 | Latente: 5  
> **Ventanas enriquecidas:** 0. La visita de Xi a EE. UU. en otoño está anunciada, pero la fecha 24-sep carece de respaldo oficial específico y queda en cuarentena fuera de la tabla.  
> **Observatorios Estructurales activos:** 4  
> **Hitos consumidos contrastados:** 10 en total: 4 heredados de TASK_090 y 6 incorporados en TASK_099.
> **Alcance factual:** evidencia contrastada hasta el corte anticipado del 12/09/2026; no incorpora publicaciones posteriores ni cobertura íntegra del domingo 13. Estado del respaldo en §7.  

---

## TABLA DE HITOS CALENDARIZADOS (RADAR 2.0)

| ID | Fecha / ventana | Confirmación | Actor | Tipo | Vector | Evento sensor | Tesis | Observable / Trigger | Prioridad | Descripción factual | Fuente |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- | :--- | :--- | :--- |
| `E_2026_09_09_US_Treasury_Long_End_Buybacks` | 2026-09-09/2026-11-04 | CONFIRMADO | U.S. Treasury / NY Fed | Operación de liquidez | V01 | V01 — Absorción y liquidez de deuda | TESIS_01_Dominancia_Fiscal | 1) Volumen ofertado/aceptado en tramos 10–20Y y 20–30Y (al menos $4B por operación); 2) Composición por tramos; 3) Spread bid-ask en deuda off-the-run; 4) Concesión de precios y liquidez de mercado (TGA/reservas como contexto posterior) | ELEVADO | Ventana iniciada y aún activa del calendario ampliado de recompras del Tesoro en el tramo largo (10Y–30Y) hasta el Refunding de noviembre. No es QE. | [U.S. Treasury Buyback Schedule](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding) |
| `E_2026_09_15_US_Section338_Product_Changes` | 2026-09-15 | CONFIRMADO | Casa Blanca / CBP | Entrada en vigor arancelaria | V04 | Tariff Stack — continuación de A/B | TESIS_02_Frictionless_Stabilization | 1) Adiciones y retiradas efectivas de productos; 2) Alcance por cada proclamación; 3) Instrucciones de CBP; 4) Ausencia de suspensión posterior | CRÍTICO | Primera fecha de ejecución de las cinco proclamaciones Section 338 firmadas el 08/09 en respuesta a Canadá. Mide ampliación o recomposición jurídica de la pila, no todavía transmisión a volúmenes o precios. | [White House — respuesta a Canadá](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/) |
| `E_2026_09_15_US_Corporate_Tax_TGA_Drain` | 2026-09-15 | RECURRENTE OFICIAL | IRS / U.S. Treasury | Vencimiento fiscal | V01 | Japón/Liquidez — Trigger B | TESIS_01_Dominancia_Fiscal | 1) Saldo de caja TGA (> $900B); 2) Saldo de reservas bancarias en la Fed (< $3,1T); 3) Spread SOFR vs IORB; 4) Volumen de uso del Standing Repo Facility (SRF) | CRÍTICO | Liquidación de pagos fraccionados de impuestos corporativos. Posible drenaje de reservas hacia la TGA: medir el flujo efectivo; el vencimiento no prueba su magnitud ni estrés. | [IRS Tax Calendar](https://www.irs.gov/businesses/small-businesses-self-employed/tax-calendar) / [Daily Treasury Statement](https://fiscaldata.treasury.gov/datasets/daily-treasury-statement/) |
| `E_2026_09_15_EU_Russia_Sanctions_Renewal` | 2026-09-15 | CONFIRMADO | Consejo de la Unión Europea | Decisión regulatoria | V06 | NINGUNO — Sensor V06 | TESIS_04_Multipolaridad_Logistica | 1) Aprobación formal de prórroga semestral; 2) Altas y bajas en listados individuales (aprox. 2.600 personas y entidades); 3) Cambios en alcance jurídico; 4) Plazo de vigencia | LATENTE | Revisión y vencimiento semestral de los listings individuales de la UE contra Rusia (congelación de activos y prohibición de viajar). | [Consilium EU Restrictive Measures](https://www.consilium.europa.eu/en/policies/sanctions/restrictive-measures-against-russia-over-ukraine/) |
| `E_2026_09_16_Fed_FOMC_Decision` | 2026-09-15/16 | CONFIRMADO | Reserva Federal | Decisión monetaria | V01 | V01 — Política monetaria y diferencial | TESIS_01_Dominancia_Fiscal | 1) Rango meta del tipo federal de fondos; 2) Dot plot de tipos para 2026–2027 en el SEP; 3) Ritmo de QT mensual; 4) Comentarios en rueda sobre liquidez de reservas y repo | ELEVADO | Decisión de tipos y publicación del Summary of Economic Projections (SEP). Calibra el diferencial de rendimientos EE. UU.–Japón y la absorción soberana. | [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| `E_2026_09_16_US_TIC_Securities_Data` | 2026-09-16 | RECURRENTE OFICIAL | U.S. Treasury | Estadística financiera | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Signo y magnitud de compras/ventas netas japonesas de Treasuries; 2) Composición disponible; 3) Stock total japonés (ref. $1.116,7B en junio); 4) Diferencial cubierto >15 días | CRÍTICO | Datos TIC de julio. Primer dato canónico para comprobar si julio registra compras netas negativas de inversores japoneses (posible mes 1 de Trigger A). | [Treasury TIC System Releases](https://home.treasury.gov/data/treasury-international-capital-tic-system) |
| `E_2026_09_18_BoJ_MPM` | 2026-09-17/18 | CONFIRMADO | Banco de Japón | Decisión monetaria | V01 | Japón/Liquidez — Carry trade | TESIS_01_Dominancia_Fiscal | 1) Mantener o modificar el objetivo del tipo overnight (~1,0%); 2) Magnitud en bps de cualquier cambio; 3) Guía de compras de JGBs; 4) Tono de Ueda sobre inflación y tipos de cambio | CRÍTICO | Reunión de política monetaria del Banco de Japón (17–18 sep; comunicado 18-sep). Determina el diferencial de rentabilidad del carry trade y tensión en bonos japoneses. | [Bank of Japan MPM Calendar](https://www.boj.or.jp/en/mopo/mpmsche_minu/index.htm) |
| `E_2026_09_29_US_Section338_Import_Bans` | 2026-09-29 | CONFIRMADO | Casa Blanca / CBP | Entrada en vigor de prohibiciones | V04 | Tariff Stack — continuación de A/B | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Productos canadienses efectivamente prohibidos; 2) Alcance jurídico; 3) Exenciones o licencias; 4) Evidencia de aplicación aduanera | CRÍTICO | Segunda fecha de ejecución de la respuesta estadounidense: entrada de determinadas prohibiciones de importación previstas en las proclamaciones Section 338 del 08/09. | [White House — respuesta a Canadá](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/) |
| `E_2026_09_30_US_Quarter_End_Liquidity` | 2026-09-30 | RECURRENTE OFICIAL | Fed / NY Fed / Dealers | Cierre regulatorio | V01 | Japón/Liquidez — Trigger D | TESIS_01_Dominancia_Fiscal | 1) Uso del Standing Repo Facility (SRF > $20B diarios durante >2 días); 2) Spread SOFR frente a IORB; 3) Dispersión en percentil 99 de repo tri-party; 4) Saldo ON RRP | CRÍTICO | Cierre contable del 3T. Tensión de balance sheet window dressing bancario que contrae la intermediación en repo y prueba la disponibilidad de colateral. | [NY Fed Markets Data](https://www.newyorkfed.org/markets/reference-rates) |
| `E_2026_09_30_Micron_FY26_Q4_Earnings` | 2026-09-30 | CONFIRMADO | Micron Technology | Resultados corporativos | V03 | CoWoS — Sensor HBM | TESIS_06_IA_como_silicio_y_energia | 1) Horizonte de venta agotada (sold-out) en HBM3E y progreso de validación de HBM4; 2) Guía de CAPEX fabril FY2027; 3) Rendimiento de memoria para aceleradores | ELEVADO | Resultados del 4T fiscal de Micron. Termómetro directo del estrangulamiento de memoria de alto ancho de banda (HBM) en la cadena de suministro de hardware de IA. | [Micron Investor Relations Events](https://investors.micron.com/) |
| `E_2026_10_04_OPEC_Plus_JMMC` | 2026-10-04 | CONFIRMADO | OPEP+ (Comité JMMC) | Reunión de monitoreo | V02 | NINGUNO — Sensor V02 | TESIS_03_Captura_de_Renta | 1) Informe de conformidad de cuotas (conformity rate); 2) Planes de compensación por sobreproducción; 3) Recomendación estatutaria sobre condiciones de mercado | LATENTE | 68ª reunión del Comité Ministerial Conjunto de Seguimiento (JMMC) de la OPEP+. Monitoreo del cumplimiento y de balances físicos globales. | [OPEC Calendar of Meetings](https://www.opec.org/opec_web/en/press_room/28.htm) |
| `E_2026_10_06_US_International_Trade_August` | 2026-10-06 | RECURRENTE OFICIAL | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Identificar categorías aranceladas; 2) Variación interanual (YoY); 3) Comprobar si caída supera -15% YoY (posible mes 1); 4) Déficit bilateral | ELEVADO | Primer dato comercial post-arancel susceptible de constituir mes 1 del Trigger D si las importaciones en sectores cubiertos caen >15% YoY según Census/BEA. | [Census International Trade Data](https://www.census.gov/foreign-trade/data/index.html) |
| `E_2026_10_07_08_US_Treasury_10Y_30Y_Reopenings` | 2026-10-07/08 | RECURRENTE OFICIAL | U.S. Treasury | Subasta soberana | V01 | V01 — Absorción soberana de duración | TESIS_01_Dominancia_Fiscal | 1) Bid-to-cover ratio (si BTC < 2,30x tras septiembre, activa Trigger 03 de V01); 2) Tail frente al mercado when-issued; 3) Asignación indirecta | LATENTE | Reapertura de subastas a 10 y 30 años de octubre. Contraste de persistencia de absorción para evaluar si se consuma el Trigger 03 de V01 (<2,30x en 2 emisiones). | [TreasuryDirect Auctions](https://www.treasurydirect.gov/instit/annceresult/annceresult.htm) |
| `E_2026_10_08_TSMC_September_Sales` | 2026-10-08 | RECURRENTE OFICIAL | TSMC | Ingresos corporativos | V03 | V03 — Ciclo de fundición y demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación mensual en NT$; 2) Crecimiento YoY; 3) Cierre consolidado del 3T vs guidance trimestral (inferencia); 4) Variación acumulada 2026 | LATENTE | Facturación de septiembre y cierre trimestral de TSMC. Sensor agregado de demanda; no desglosa nodos 3nm/5nm ni cuellos de botella CoWoS/HBM. | [TSMC Monthly Revenue Reports](https://investor.tsmc.com/english/monthly-revenue) |
| `E_2026_10_08_Japan_Monthly_Securities_Flows_September` | 2026-10-08 | RECURRENTE OFICIAL | Ministerio de Finanzas de Japón | Estadística de flujos | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Compras netas de deuda extranjera a largo plazo; 2) Signo del total de cartera; 3) Comparación con agosto (−¥143,0B en deuda larga); 4) Confirmar o negar segundo mes negativo | CRÍTICO | Publicación mensual de septiembre. Puede completar el componente de dos meses consecutivos del Trigger A, pero todavía exige verificar el diferencial cubierto durante 15 días. | [MOF Japan — calendario de publicación](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm) |
| `E_2026_10_16_US_TIC_Securities_Data` | 2026-10-16 | RECURRENTE OFICIAL | U.S. Treasury | Estadística financiera | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Comprobar si agosto presenta compras netas negativas japonesas condicionado a que julio haya sido negativo; 2) Cumplimiento acumulado de Trigger A | CRÍTICO | Datos TIC de agosto. Comprobación de si agosto constituye un segundo mes consecutivo de ventas netas japonesas, necesario para satisfacer el Trigger A. | [Treasury TIC System](https://home.treasury.gov/data/treasury-international-capital-tic-system) |
| `E_2026_10_28_Fed_FOMC_Decision` | 2026-10-27/28 | CONFIRMADO | Reserva Federal | Decisión monetaria | V01 | V01 — Política monetaria | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre tipo de fondos federales; 2) Tono del comunicado sobre riesgos de empleo e inflación; 3) Mensaje sobre estabilidad de reservas antes de elecciones | ELEVADO | Reunión de política monetaria intermedia (sin SEP). Calibra las condiciones de liquidez monetaria una semana antes de las elecciones legislativas estadounidenses. | [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| `E_2026_10_29_ECB_Monetary_Policy` | 2026-10-28/29 | CONFIRMADO | Banco Central Europeo | Decisión monetaria | V01 | NINGUNO — sensor de tipos y fragmentación V01 | TESIS_01_Dominancia_Fiscal | 1) Tipos de depósito/MRO/marginal frente a 2,50%/2,65%/2,90%; 2) Orientación de balance; 3) Referencias operativas a fragmentación o spreads soberanos; 4) Instrumentos de transmisión | ELEVADO | Primera decisión del BCE posterior al alza del 10/09. Se admite por su canal directo a coste soberano y fragmentación, no como reunión rutinaria automática. | [ECB — calendario del Consejo de Gobierno](https://www.ecb.europa.eu/press/calendars/mgcgc/html/index.en.html) |
| `E_2026_10_30_BoJ_MPM_Outlook` | 2026-10-29/30 | CONFIRMADO | Banco de Japón | Decisión monetaria | V01 | Japón/Liquidez — Carry trade | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre objetivo del tipo overnight; 2) Proyecciones plurianuales de PIB e inflación 2026–2027 en el Outlook Report; 3) Evaluación del tipo de cambio | ELEVADO | Reunión trimestral con Outlook Report del BoJ. Determina la trayectoria esperada de tipos de interés para finales de 2026 e inicios de 2027. | [Bank of Japan Releases](https://www.boj.or.jp/en/mopo/mpmsche_minu/index.htm) |
| `E_2026_11_02_US_Treasury_Financing_Estimates` | 2026-11-02 | RECURRENTE OFICIAL | U.S. Treasury | Estimación financiera | V01 | V01 — Necesidades de endeudamiento | TESIS_01_Dominancia_Fiscal | 1) Estimación oficial de endeudamiento neto para el 4T 2026 y 1T 2027; 2) Saldo objetivo de caja TGA al cierre de año; 3) Proporción estimada bills vs cupones | ELEVADO | Publicación de necesidades de financiación previas al Refunding. Fija la escala de liquidez requerida por el Tesoro de los mercados primarios. | [U.S. Treasury Refunding](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding) |
| `E_2026_11_03_US_Midterm_Elections` | 2026-11-03 | CONFIRMADO | Electorado de EE. UU. / Congreso | Elección política | V06 | NINGUNO — Sensor político-fiscal | TESIS_01_Dominancia_Fiscal, TESIS_04_Multipolaridad_Logistica | 1) Mayorías parlamentarias en Cámara y Senado; 2) Margen legislativo para sostener o modificar aranceles; 3) Perspectiva sobre prórroga fiscal y techo de deuda en 2027 | ELEVADO | Elecciones de mitad de mandato en EE. UU. Condicionan la arquitectura fiscal y el margen de ejecución de la política comercial y regulatoria federal. | [Federal Election Commission](https://www.fec.gov/) / [Congress.gov](https://www.congress.gov/) |
| `E_2026_11_04_US_Treasury_Quarterly_Refunding` | 2026-11-04 | CONFIRMADO | U.S. Treasury | Emisión soberana | V01 | V01 — Política de emisión y colateral | TESIS_01_Dominancia_Fiscal | 1) Tamaños de subastas en tramos 2Y, 5Y, 10Y y 30Y; 2) Cuota de financiación vía T-Bills respecto a deuda cupón; 3) Decisión sobre el programa de buybacks; 4) Informe TBAC | RÉGIMEN | Anuncio formal de política de refinanciación de la deuda de EE. UU. Determina si el tramo largo de la curva soberana sufre sobresaturación o racionamiento de colateral. | [U.S. Treasury Refunding](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding) |
| `E_2026_11_04_US_International_Trade_September` | 2026-11-04 | RECURRENTE OFICIAL | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Comprobar si septiembre presenta caída >15% YoY en sectores cubiertos Y si agosto ya cumplió >15% YoY; 2) Activación completa de Trigger D | CRÍTICO | Balanza comercial de septiembre. Punto resolutivo para la activación formal del Trigger D si se encadenan dos meses consecutivos con caída >15% YoY. | [Census Foreign Trade](https://www.census.gov/foreign-trade/data/index.html) |
| `E_2026_11_10_Japan_Monthly_Securities_Flows_October` | 2026-11-10 | RECURRENTE OFICIAL | Ministerio de Finanzas de Japón | Estadística de flujos | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Compras netas de deuda extranjera a largo plazo; 2) Persistencia mensual; 3) Composición por tipo de activo; 4) Contraste con septiembre y agosto | CRÍTICO | Publicación mensual de octubre. Comprueba si una eventual secuencia de desinversión exterior persiste; no sustituye el requisito del diferencial cubierto. | [MOF Japan — calendario de publicación](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm) |
| `E_2026_11_10_TSMC_October_Sales` | 2026-11-10 | PROVISIONAL | TSMC | Ingresos corporativos | V03 | CoWoS — sensor agregado de demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación mensual en NT$; 2) Crecimiento interanual; 3) Acumulado enero-octubre; 4) Trayectoria frente a guía trimestral como inferencia | LATENTE | Extiende el horizonte hasta noviembre con un sensor agregado comparable. No mide capacidad CoWoS, *yields*, AP7 ni entregas físicas de aceleradores. | [TSMC — calendario financiero](https://investor.tsmc.com/english/financial-calendar) |

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

Las cinco notas siguientes conservan criterios de decisión sin duplicar estados ni añadir ventanas enriquecidas. La proximidad temporal no constituye evidencia ni altera la carga.

### Section 338 Canadá — 15 y 29-sep

Filas `E_2026_09_15_US_Section338_Product_Changes` y `E_2026_09_29_US_Section338_Import_Bans`. V04 primario; transmisión a V05/V01; TESIS_02. Verificar ejecución efectiva, alcance por producto, instrucciones aduaneras y eventuales suspensiones. Son continuación de la escalada jurídica ya incorporada en Tariff Stack; no activan automáticamente C–E sin datos de transmisión.

### TGA 15-sep

Fila `E_2026_09_15_US_Corporate_Tax_TGA_Drain`; próxima. V01 primario; transmisión a V04; TESIS_01. Contrastar la variación efectiva de TGA y reservas durante la quincena con el nexo fiscal del Trigger B. Al 09/09 la TGA estaba en 843,705 B$ y las reservas en 3.036,508 B$: el umbral doble no estaba cruzado simultáneamente. SOFR–IORB y SRF se contrastan con las duraciones exactas de C y D; una observación aislada no basta.

### FOMC 16-sep

Fila `E_2026_09_16_Fed_FOMC_Decision`; próxima y confirmada. V01 primario; transmisión a V04/V06; TESIS_01. Comparar rango de tipos, SEP, implementación y balance con el estado previo. Incorporar decisiones efectivas y distinguirlas de expectativas; no dar por hecho un recorte. Se contrasta después con el BoJ del 17–18/09 y con el BCE del 28–29/10.

### Cierre Q3 30-sep

Fila `E_2026_09_30_US_Quarter_End_Liquidity`; prevista. V01 primario; TESIS_01. Medir SRF y SOFR–IORB durante toda la ventana del Trigger D (25–30 sep), no solo la última jornada. Resolver en la revisión siguiente cuando estén publicados los datos. El PCE de agosto está previsto el mismo día, según [BEA, calendario 2026](https://www.bea.gov/taxonomy/term/476?page=1); se conserva como contexto y no se añade una fila automática sin mecanismo de admisión.

### Midterms 03-nov

Fila `E_2026_11_03_US_Midterm_Elections`; prevista. V06 primario; transmisión a V01/V04; TESIS_01/TESIS_02/TESIS_04. Conservar como hipótesis el incentivo político a evitar turbulencias antes del voto: no prueba intervención monetaria ni liquidez garantizada. Tras el resultado, evaluar composición parlamentaria y capacidad legislativa fiscal/comercial. No cambiar presiones por la mera proximidad de las elecciones.

---

## 2. OBSERVATORIOS ESTRUCTURALES

### 1. Observatorio de Riesgo Marítimo y Seguridad de Chokepoints (Ormuz y Bab el-Mandeb)
- **Vectores:** [[VECTOR_02_Energia_y_nodos_geoeconomicos]], [[VECTOR_04_Reconfiguracion_del_comercio_global]], [[VECTOR_01_Arquitectura_monetaria_global]]
- **Evento conectado:** [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb]]
- **Variables monitoreadas:** 
  1. Recuento oficial de ataques y bajas marítimas por la OMI (actual al 10/09: 75 incidentes confirmados, 22 fallecidos).
  2. Avisos de incidentes cinéticos en tiempo real de UKMTO (enfoque en boca de Ormuz y Bab el-Mandeb).
  3. Revisiones de áreas listadas del Joint War Committee de Lloyd's (JWLA-034 vigente).
  4. Cotizaciones verificables de primas adicionales de guerra en brokers de Londres (umbral Trigger A $\ge 1,5\%$).
  5. Daños estructurales o hundimientos en buques petroleros VLCC o metaneros LNG (Trigger B).
  6. Interrupción de tránsito físico superior a 5 Mb/d por más de 48 horas (Trigger D).
- **Condición de promoción a tabla calendarizada:** Publicación oficial con fecha fijada de una nueva circular del JWC (ej. JWLA-035) o convocatoria formal de una conferencia regulatoria marítima de la OMI.

### 2. Observatorio de Estrés de Red Eléctrica e Infraestructura Crítica de IA (Grid Stress)
- **Vectores:** [[VECTOR_02_Energia_y_nodos_geoeconomicos]], [[VECTOR_03_Semiconductores_y_soberania_tecnologica]]
- **Evento conectado:** [[Evento_E0_2026_07_08_Grid_Stress_IA]]
- **Variables monitoreadas:**
  1. Resoluciones administrativas y órdenes de FERC sobre dockets de coincentivación y centros de datos (EL26-67 a EL26-72).
  2. Emisión y vencimiento de órdenes de emergencia bajo Sección 202(c) de la Federal Power Act por el Department of Energy (DOE); la 202-26-41 expiró el 08/09 sin activar el trigger CPD.
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

## 3. HITOS EJECUTADOS / CONSUMIDOS (AUDITORÍAS W36–W37)

| ID / Hito | Fecha real | Resultado primario verificado | Evento / Vector | Resolución | Acción tomada |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **US ISM Manufacturing PMI** | Periodo: agosto 2026; publicación: 2026-09-01 | PMI **54,6** frente a 55,6 en julio; precios **71,1**. Fuente: [ISM, agosto 2026](https://www.ismworld.org/supply-management-news-and-reports/reports/ism-pmi-reports/pmi/august/). Consulta 06/09/2026. | V05 | `NO MATERIAL` para triggers canónicos | Se corrige la falsa contracción: expansión industrial, con menor ritmo. Rectificar la justificación de V05; no activa por sí solo sus triggers seculares. |
| **Japan 30Y JGB Auction** | Subasta y publicación: 2026-09-03 | Issue 91; yield medio **4,079%** y yield de corte **4,100%**; cobertura competitiva **1.728,1 / 456,2 = 3,788x**. Fuente: [MOF, resultado específico](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260903.htm). Consulta 06/09/2026. | Japón · V01 | `NO MATERIAL` para Trigger A | Demanda competitiva superior al volumen adjudicado. La tabla no identifica al comprador final: no prueba por sí sola absorción doméstica ni repatriación. |
| **US International Trade (Julio)** | Periodo: julio 2026; publicación: 2026-09-03 | Déficit de bienes y servicios **$88,6B**, frente a $71,2B en junio revisado. Fuente: [BEA/Census, julio 2026](https://www.bea.gov/news/2026/us-international-trade-goods-and-services-july-2026). Consulta 06/09/2026. | Tariff Stack · V04 | `NO MATERIAL` para Trigger D | Dato agregado anterior a la entrada de Section 338 el 22-ago; no demuestra dos meses de contracción sectorial ni causalidad arancelaria. |
| **US Non-Farm Payrolls (Agosto)** | Periodo: agosto 2026; publicación: 2026-09-04 | Nóminas **+162.000**; paro **4,1%**; salarios **+0,3% mensual / +3,1% anual**; manufacturas **+16.000**. Fuente: [BLS, comunicado archivado](https://www.bls.gov/news.release/archives/empsit_09042026.htm). Consulta 06/09/2026. | V01 · V05 | `NO MATERIAL` para triggers canónicos | Se retira el argumento de pérdida fabril. El dato no descarta por sí solo una recesión ni determina la decisión del FOMC. |
| **OPEC+ Core Meeting** | Reunión y publicación: 2026-09-06 | Los siete participantes mantuvieron para octubre la producción requerida de septiembre y fijaron la siguiente reunión para el 04/10. Fuente: [OPEP, comunicado específico](https://www.opec.org/pr-detail/613-6-september-2026.html). Consulta 12/09/2026. | V02 | `NO MATERIAL` para eventos activos | No altera los triggers físicos o aseguradores de Lloyd’s; se conserva el JMMC del 04/10 como próximo sensor de oferta. |
| **Canada Counter-Tariffs** | Orden: 2026-09-04; efectiva: 2026-09-08 | La Orden en Consejo **P.C. 2026-0785** hizo efectivos tipos del 15%, 25% y 50% sobre **27.600 M CAD** de importaciones estadounidenses. Fuentes: [Orden](https://orders-in-council.canada.ca/attachment.php?attach=48943&lang=en) y [lista oficial](https://www.canada.ca/en/department-finance/programs/international-trade-finance-policy/canadas-response-us-tariffs/complete-list-us-products-subject-to-counter-tariffs.html). Consulta 12/09/2026. | Tariff Stack · V04 | `MATERIAL` — Trigger B | Trigger B activado; Tariff Stack pasa de → a ↑. La respuesta de EE. UU. genera nuevas ventanas el 15 y 29/09. |
| **Japan Monthly Securities Flows (Agosto)** | Periodo: agosto 2026; publicación: 2026-09-08 | Inversores designados: **−¥143,0B** netos en deuda extranjera a largo plazo y **+¥136,6B** en cartera total. Fuente: [MOF, publicación mensual](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/monthEng.pdf). Consulta 12/09/2026. | Japón/Liquidez · V01 | `NO MATERIAL` para Trigger A | Un mes negativo en deuda larga no completa los dos meses consecutivos; el total de cartera fue positivo y falta verificar 15 días de diferencial cubierto. |
| **US Treasury 10Y/30Y Reopenings** | Subastas: 2026-09-09/10 | El calendario oficial confirma ambas subastas, pero en este corte no se recuperó un documento primario estable con todos los observables —BTC, indirectos, *tail* y *when-issued*— para las dos emisiones. Fuentes: [calendario oficial](https://home.treasury.gov/system/files/221/Tentative-Auction-Schedule.pdf) y [buscador de resultados](https://www.treasurydirect.gov/auctions/auction-query/). Consulta 12/09/2026. | V01 | `NO VERIFICABLE` en esta auditoría | La fila se retira de futuros por vencimiento, sin declarar Trigger 03 ni inferir fallo de absorción. |
| **TSMC Monthly Sales (Agosto)** | Periodo: agosto 2026; publicación: 2026-09-10 | Ingresos **514.806 M NT$**, +10,1% mensual y +53,3% interanual; enero-agosto **3.386.870 M NT$**, +39,3%. Fuente: [TSMC, publicación específica](https://pr.cld.tsmc.com/english/news/3340). Consulta 12/09/2026. | CoWoS · V03 | `NO MATERIAL` para A–D | Confirma demanda agregada, pero no desglosa capacidad CoWoS, AP7, *yields*, entregas Blackwell ni *lead times*. |
| **ECB Monetary Policy Decision** | Decisión: 2026-09-10; efectiva: 2026-09-16 | Alza de 25 pb: depósito **2,50%**, MRO **2,65%** y marginal **2,90%**. Fuente: [BCE, decisión específica](https://www.ecb.europa.eu/press/pr/date/2026/html/ecb.mp260910~314e508016.en.html). Consulta 12/09/2026. | V01 | `MATERIAL` como señal de tipos; sin trigger de evento | Endurece el punto de partida europeo y justifica admitir la reunión del 28–29/10 por su canal a coste soberano y fragmentación; no modifica por sí solo la carga primaria. |

---

## 4. COBERTURA POR VECTOR

| Vector | Filas en tabla | Prioridad Crítica | Prioridad Régimen | Ventana Enriquecida | Observatorio activo | Diagnóstico de cobertura |
| :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **V01: Arquitectura monetaria global** | 15 | 7 | 1 | 0 | No; seguimiento mediante la ficha Japón y filas V01 | Cobertura calendarizada: TGA, FOMC, BoJ, BCE, TIC, flujos MOF, recompras y Refunding. |
| **V02: Energía y nodos geoeconomicos** | 1 | 0 | 0 | 0 | Sí (2: Lloyd's y Grid Stress) | Cobertura continua en Observatorios; única fila futura vía JMMC del 04/10. |
| **V03: Semiconductores y soberanía tech** | 3 | 0 | 0 | 0 | Sí (CoWoS & HBM) | Facturación agregada TSMC y *earnings* Micron; la visita Xi–EE. UU. no cuenta hasta obtener fecha oficial. |
| **V04: Reconfiguración del comercio** | 4 | 3 | 0 | 0 | No | Alta potencia jurídica: ejecución Section 338 el 15/29-sep y balanzas de agosto/septiembre. La visita Xi–EE. UU. queda en cuarentena sin fecha. |
| **V05: Transformación industrial y demografía** | 0 | 0 | 0 | 0 | No | **HUECO REAL DECLARADO:** Sin hitos de 60 días capaces de activar sus triggers seculares. |
| **V06: Orden geopolítico y esferas** | 2 | 0 | 0 | 0 | Sí (Geopolítica / Sanciones) | Cobertura institucional (listings UE-Rusia, elecciones intermedias de EE. UU.). |
| **TOTALES CONSOLIDADOS** | **25** | **10** | **1** | **0** | **4** | **1 hueco estructural y 1 candidato sin fecha declarados** |

---

## 5. COBERTURA POR EVENTO ACTIVO

| Evento Activo del Sistema | Próximo hito sensor en Radar | Fecha programada | Trigger observado | Nivel de cobertura analítica |
| :--- | :--- | :--- | :--- | :--- |
| **`Evento_E0_2026_07_08_Grid_Stress_IA`** | Resoluciones administrativas continuas FERC / DOE | Observatorio continuo | Triggers A, B y C (Órdenes 202c, paradas y moratorias) | Seguimiento previsto en cada revisión mediante Observatorio Estructural 2 |
| **`Evento_E0_2026_08_16_Japon_Carry_Trade_y_Liquidez_Septiembre`** | Liquidación fiscal corporativa EE. UU. / TIC / BoJ | 2026-09-15 / 16 / 17–18 | Triggers B y A; diferencial de carry | Cobertura crítica inmediata; flujos MOF mensuales del 08/10 y 10/11 permiten comprobar persistencia sin confundir stock TIC con flujo. |
| **`Evento_E0_2026_CoWoS_Capacity`** | Earnings Micron / ventas TSMC | 2026-09-30 / 2026-10-08 / 2026-11-10 | Sensores de HBM y demanda agregada; no triggers directos de capacidad | *Lead times*, AP7 y *yields* permanecen en Observatorio 3; la facturación no se promueve a evidencia CoWoS. |
| **`Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb`** | Despachos continuos OMI y avisos UKMTO | Observatorio continuo | Triggers A, B y D (Primas $\ge 1,5\%$, daño a VLCC/LNG, corte >5 Mb/d) | Seguimiento previsto en cada revisión mediante Observatorio Estructural 1; sin fecha fija para incidentes cinéticos |
| **`Evento_E1_2026_07_24_US_Tariff_Stack`** | Ejecución de proclamaciones Section 338 / balanzas comerciales | 2026-09-15 / 29 y 2026-10-06 / 11-04 | Continuación A/B y Trigger D | Trigger B ya consumado; las próximas filas observan alcance aduanero y transmisión física. La visita Xi–EE. UU. no se usa hasta que tenga fecha oficial. |

---

## 6. HUECOS REALES DE COBERTURA

1. **Vector 05 (Transformación Industrial y Demografía):**
   - No contiene filas en la tabla futura de los próximos 60 días.
   - **Razón epistemológica:** Los triggers canónicos de V05 exigen verificar: fuga masiva de CAPEX industrial fuera de economías centrales durante varios trimestres, cuotas de importación que compriman cuota industrial durante más de 6 meses, o deterioro anualizado de la ratio de soporte de pensiones. Estos procesos operan a escala secular y no se resuelven mediante series mensuales o eventos de 24 horas. Declarar el hueco evita introducir ruido o lecturas rutinarias que no alteran restricciones.
2. **Fricción Cinética en V02 (Estrecho de Ormuz y Bab el-Mandeb):**
   - Los ataques militares, lanzamientos de misiles y secuestros navales no tienen fecha predeterminada.
   - Se canalizan mediante el **Observatorio Estructural 1**, auditando fuentes primarias (OMI, UKMTO, CENTCOM, LMA) en cada corte semanal para detectar la activación de los Triggers A, B o D sin inventar fechas en la agenda.

---

## 7. Respaldo documental y límites de verificación

**Contraste efectuado:** 12/09/2026 a las 21:21 Europe/Madrid. Un resultado posterior al corte no se incorpora como si ya se conociera entonces; el precierre no cubre íntegramente el domingo 13.

- **Diez resultados consumidos:** cuatro heredados de W36 y seis incorporados en W37: OPEP+ 06/09, contramedidas canadienses 08/09, flujos MOF de agosto, reaperturas Treasury 10Y/30Y, TSMC agosto y BCE 10/09. La fila de subastas se clasifica `NO VERIFICABLE` porque no se recuperaron todos sus observables desde un documento primario estable; no se rellenó con cifras secundarias.
- **Fechas futuras contrastadas específicamente en TASK_099:** Section 338 de EE. UU. el 15 y 29/09 ([Casa Blanca](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/)); FOMC 15–16/09 y 27–28/10 ([Fed](https://www.federalreserve.gov/monetarypolicy.htm)); BoJ 17–18/09 y 29–30/10 ([BoJ](https://www.boj.or.jp/en/mopo/mpmsche_minu/m_ref/mref250731a.pdf)); BCE 28–29/10 ([BCE](https://www.ecb.europa.eu/press/calendars/mgcgc/html/index.en.html)); flujos MOF 08/10 y 10/11 ([MOF](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm)); y ventas TSMC 08/10 y 10/11 ([TSMC](https://investor.tsmc.com/english/financial-calendar)). Se confirman fechas o calendarios, no resultados futuros.
- **Resto de las filas futuras:** conserva respaldo y etiqueta de la revisión anterior; cada resultado deberá volver a contrastarse al consumirse. Una portada, hub o serie sin documento fechado no basta para validar cifras o actos.
- **Visita Xi–EE. UU.:** las fuentes oficiales de ambos países anuncian una visita de Estado en otoño, pero no fijan el 24/09. Se retira de la tabla y queda en cuarentena; no cuenta como fila ni Ventana Enriquecida hasta que exista fecha oficial específica.
- **Observatorios:** son instrucciones de seguimiento, no servicios de vigilancia continua ni prueba de comprobación en tiempo real. Los saldos, incidentes y lead times heredados necesitan su documento fechado para ser reutilizados como dato nuevo.
- **Control estructural:** 25/25 filas tienen los doce campos y un campo Fuente; IDs sin duplicados y cero fechas vencidas en la tabla futura. La presencia de referencias no significa 100% de respaldo factual auditado.

### Rectificaciones fechadas — TASK_090

El 06/09/2026 se sustituyeron en el estado vivo los NFP +142.000 / paro 4,2% / salarios +0,4% y +3,8% y el ISM 47,2 / precios 54,0, correspondientes a agosto de 2024 ([BLS 2024](https://www.bls.gov/news.release/archives/empsit_09062024.htm); [ISM 2024](https://www.ismworld.org/supply-management-news-and-reports/news-publications/inside-supply-management-magazine/blog/2024/2024-093/rob-roundup-august-2024-manufacturing-pmi/)). No se usan para diagnosticar 2026. Se corrigió además el déficit de julio de $78,8B a $88,6B con BEA. La versión previa se conserva íntegra en [[Radar_Eventos_2026_09__PRE_TASK090]] y no alimenta estados vigentes.

**Regla de reutilización:** dato + unidad + periodo observado + fecha de publicación + documento específico + fecha de consulta. Si falta respaldo, marcarlo pendiente; las inferencias deben identificarse como tales. Una actualización de formato o enlaces no renueva automáticamente la fecha de contraste factual.
