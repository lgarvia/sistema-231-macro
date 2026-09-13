> **ARCHIVO — versión anterior a TASK_090, conservada el 06/09/2026.** Contiene afirmaciones suplantadas; no usar como estado ni evidencia vigente. Véase [[Radar_Eventos_2026_09]]. El contenido anterior se conserva a continuación con enlaces históricos reparados. La copia exacta anterior está en scratch/task090_before.zip.

# RADAR DE EVENTOS — SEPTIEMBRE 2026 (RADAR 2.0)

> **Versión:** 2.0 — Canónica Post-W36 (Parche Forense de Integridad)  
> **Fecha de corte y generación:** 2026-09-06 00:00 Europe/Madrid (W36)  
> **Horizonte temporal canónico:** 2026-09-06 → 2026-11-05 inclusive (60 días)  
> **Filas en tabla calendarizada:** 25  
> **Distribución por prioridad:** Régimen: 2 | Crítico: 7 | Elevado: 10 | Latente: 6  
> **Ventanas Enriquecidas promovidas:** 1 ([VEN_2026_09_24_Cumbre_Xi_US])  
> **Observatorios Estructurales activos:** 4  
> **Hitos Ejecutados / Consumidos auditados:** 4  

---

## TABLA DE HITOS CALENDARIZADOS (RADAR 2.0)

| ID | Fecha / ventana | Confirmación | Actor | Tipo | Vector | Evento sensor | Tesis | Observable / Trigger | Prioridad | Descripción factual | Fuente |
| :--- | :--- | :--- | :--- | :--- | :---: | :--- | :--- | :--- | :--- | :--- | :--- |
| `E_2026_09_06_OPEC_Plus_Core_Meeting` | 2026-09-06 | ANUNCIADO | OPEP+ (Secretaría / Delegaciones) | Reunión ministerial extraordinaria | V02 | Lloyd's / V02 — Oferta física | TESIS_03_Captura_de_Renta | 1) Decisión sobre restitución gradual de 2,2 Mb/d prevista para octubre; 2) Extensión de recortes voluntarios; 3) Compensación por sobreproducción | ELEVADO | Reunión telemática extraordinaria de los ocho miembros clave de la OPEP+. Pendiente de resolución oficial al corte de las 00:00 Madrid. | [OPEC Press Releases](https://www.opec.org/opec_web/en/press_room/28.htm) |
| `E_2026_09_08_Canada_Counter_Tariffs` | 2026-09-08 | CONFIRMADO | Gobierno de Canadá / CBSA | Decisión arancelaria | V04 | Tariff Stack — Trigger B | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Publicación de Customs Notice de la CBSA; 2) Tipos arancelarios efectivos (15%, 25%, 50%); 3) Cobertura de bienes (27.600 M$ CAD); 4) Cobro efectivo en aduana sin moratoria | CRÍTICO | Entrada en vigor formal de las contramedidas arancelarias de Canadá contra importaciones estadounidenses en represalia al arancel base de EE. UU. | [Canada Dept of Finance Notice](https://www.canada.ca/en/department-finance/news/2026/08/countermeasures-to-us-tariffs.html) / [CBSA Customs Notices](https://www.cbsa-asfc.gc.ca/publications/cn-ad/menu-eng.html) |
| `E_2026_09_08_Japan_Monthly_Securities_Flows` | 2026-09-08 | RECURRENTE OFICIAL | Ministerio de Finanzas de Japón | Estadística de flujos | V01 | Japón/Liquidez — Sensor flujos | TESIS_01_Dominancia_Fiscal | 1) Compras netas japonesas de deuda externa; 2) Inversión extranjera neta en JGBs; 3) Desglose entre banca privada y fondos de pensiones/aseguradoras | LATENTE | Publicación preliminar de flujos transfronterizos de agosto. Sensor de compras/ventas netas de valores exteriores y posible cambio en reciclaje del ahorro japonés. | [MOF Japan Securities Transactions](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/) |
| `E_2026_09_09_US_Treasury_Long_End_Buybacks` | 2026-09-09/11-04 | CONFIRMADO | U.S. Treasury / NY Fed | Operación de liquidez | V01 | V01 — Absorción y liquidez de deuda | TESIS_01_Dominancia_Fiscal | 1) Volumen ofertado/aceptado en tramos 10–20Y y 20–30Y (al menos $4B por operación); 2) Composición por tramos; 3) Spread bid-ask en deuda off-the-run; 4) Concesión de precios y liquidez de mercado (TGA/reservas como contexto posterior) | ELEVADO | Inicio del calendario ampliado de recompras del Tesoro en el tramo largo (10Y–30Y) para sostener liquidez del colateral off-the-run hasta el Refunding de noviembre. No es QE. | [U.S. Treasury Buyback Schedule](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding) |
| `E_2026_09_09_10_US_Treasury_10Y_30Y_Reopenings` | 2026-09-09/10 | RECURRENTE OFICIAL | U.S. Treasury | Subasta soberana | V01 | V01 — Absorción soberana de duración | TESIS_01_Dominancia_Fiscal | 1) Bid-to-cover ratio (alerta de Trigger 03 de V01 si BTC < 2,30x en emisión 1 de 2); 2) Demanda indirecta (foránea); 3) Tail de rendimiento (>1,5 bps); 4) High yield frente al mercado when-issued | ELEVADO | Subastas de reapertura de notas a 10 años ($38B) y bonos a 30 años ($22B). Sensor de absorción privada y externa del colateral soberano largo estadounidense. | [TreasuryDirect Upcoming Auctions](https://www.treasurydirect.gov/instit/annceresult/annceresult.htm) |
| `E_2026_09_10_TSMC_August_Sales` | 2026-09-10 | RECURRENTE OFICIAL | TSMC | Ingresos corporativos | V03 | V03 — Ciclo de fundición y demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación neta consolidada en NT$; 2) Crecimiento interanual (YoY); 3) Acumulado enero-agosto; 4) Trayectoria frente a la guidance trimestral (inferencia) | LATENTE | Sensor agregado de demanda y ciclo de fundición mediante la facturación no auditada de agosto de TSMC. No mide CoWoS ni producción de aceleradores. | [TSMC Monthly Revenue Reports](https://investor.tsmc.com/english/monthly-revenue) |
| `E_2026_09_15_US_Corporate_Tax_TGA_Drain` | 2026-09-15 | RECURRENTE OFICIAL | IRS / U.S. Treasury | Vencimiento fiscal | V01 | Japón/Liquidez — Trigger B | TESIS_01_Dominancia_Fiscal | 1) Saldo de caja TGA (> $900B); 2) Saldo de reservas bancarias en la Fed (< $3,1T); 3) Spread SOFR vs IORB; 4) Volumen de uso del Standing Repo Facility (SRF) | CRÍTICO | Liquidación de pagos fraccionados de impuestos corporativos. Drenaje mecánico masivo de reservas bancarias hacia la cuenta del Tesoro en la Fed. | [IRS Tax Calendar](https://www.irs.gov/businesses/small-businesses-self-employed/tax-calendar) / [Daily Treasury Statement](https://fiscaldata.treasury.gov/datasets/daily-treasury-statement/) |
| `E_2026_09_15_EU_Russia_Sanctions_Renewal` | 2026-09-15 | CONFIRMADO | Consejo de la Unión Europea | Decisión regulatoria | V06 | NINGUNO — Sensor V06 | TESIS_04_Multipolaridad_Logistica | 1) Aprobación formal de prórroga semestral; 2) Altas y bajas en listados individuales (aprox. 2.600 personas y entidades); 3) Cambios en alcance jurídico; 4) Plazo de vigencia | LATENTE | Revisión y vencimiento semestral de los listings individuales de la UE contra Rusia (congelación de activos y prohibición de viajar). | [Consilium EU Restrictive Measures](https://www.consilium.europa.eu/en/policies/sanctions/restrictive-measures-against-russia-over-ukraine/) |
| `E_2026_09_16_Fed_FOMC_Decision` | 2026-09-15/16 | CONFIRMADO | Reserva Federal | Decisión monetaria | V01 | V01 — Política monetaria y diferencial | TESIS_01_Dominancia_Fiscal | 1) Rango meta del tipo federal de fondos; 2) Dot plot de tipos para 2026–2027 en el SEP; 3) Ritmo de QT mensual; 4) Comentarios en rueda sobre liquidez de reservas y repo | ELEVADO | Decisión de tipos y publicación del Summary of Economic Projections (SEP). Calibra el diferencial de rendimientos EE. UU.–Japón y la absorción soberana. | [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| `E_2026_09_16_US_TIC_Securities_Data` | 2026-09-16 | RECURRENTE OFICIAL | U.S. Treasury | Estadística financiera | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Signo y magnitud de compras/ventas netas japonesas de Treasuries; 2) Composición disponible; 3) Stock total japonés (ref. $1.116,7B en junio); 4) Diferencial cubierto >15 días | CRÍTICO | Datos TIC de julio. Primer dato canónico para comprobar si julio registra compras netas negativas de inversores japoneses (posible mes 1 de Trigger A). | [Treasury TIC System Releases](https://home.treasury.gov/data/treasury-international-capital-tic-system) |
| `E_2026_09_18_BoJ_MPM` | 2026-09-17/18 | CONFIRMADO | Banco de Japón | Decisión monetaria | V01 | Japón/Liquidez — Carry trade | TESIS_01_Dominancia_Fiscal | 1) Mantener o modificar el objetivo del tipo overnight (~1,0%); 2) Magnitud en bps de cualquier cambio; 3) Guía de compras de JGBs; 4) Tono de Ueda sobre inflación y tipos de cambio | CRÍTICO | Reunión de política monetaria del Banco de Japón (17–18 sep; comunicado 18-sep). Determina el diferencial de rentabilidad del carry trade y tensión en bonos japoneses. | [Bank of Japan MPM Calendar](https://www.boj.or.jp/en/mopo/index.htm) |
| `VEN_2026_09_24_Cumbre_Xi_US` | 2026-09-24 | ANUNCIADO | Casa Blanca / MOFA China (en trámite) | Cumbre bilateral | V04 | Tariff Stack / CoWoS | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica, TESIS_06_IA_como_silicio_y_energia | 1) Modificación formal vinculante de aranceles; 2) Controles de exportación del BIS en GPUs/litografía; 3) Licencias de minerales críticos (MOFCOM); 4) Comunicado institucional | RÉGIMEN | Cumbre bilateral de alto nivel anunciada Washington-Pekín (VENTANA ENRIQUECIDA). Capacidad de alterar simultáneamente aranceles, flujos comerciales y restricciones tecnológicas. | [White House Statements](https://www.whitehouse.gov/briefing-room/statements-releases/) (anuncio unilateral EE. UU.); registro chino: sin confirmación formal localizada al corte |
| `E_2026_09_30_US_Quarter_End_Liquidity` | 2026-09-30 | RECURRENTE OFICIAL | Fed / NY Fed / Dealers | Cierre regulatorio | V01 | Japón/Liquidez — Trigger D | TESIS_01_Dominancia_Fiscal | 1) Uso del Standing Repo Facility (SRF > $20B diarios durante >2 días); 2) Spread SOFR frente a IORB; 3) Dispersión en percentil 99 de repo tri-party; 4) Saldo ON RRP | CRÍTICO | Cierre contable del 3T. Tensión de balance sheet window dressing bancario que contrae la intermediación en repo y prueba la disponibilidad de colateral. | [NY Fed Markets Data](https://www.newyorkfed.org/markets/reference-rates) |
| `E_2026_09_30_Micron_FY26_Q4_Earnings` | 2026-09-30 | CONFIRMADO | Micron Technology | Resultados corporativos | V03 | CoWoS — Sensor HBM | TESIS_06_IA_como_silicio_y_energia | 1) Horizonte de venta agotada (sold-out) en HBM3E y progreso de validación de HBM4; 2) Guía de CAPEX fabril FY2027; 3) Rendimiento de memoria para aceleradores | ELEVADO | Resultados del 4T fiscal de Micron. Termómetro directo del estrangulamiento de memoria de alto ancho de banda (HBM) en la cadena de suministro de hardware de IA. | [Micron Investor Relations Events](https://investors.micron.com/) |
| `E_2026_10_04_OPEC_Plus_JMMC` | 2026-10-04 | CONFIRMADO | OPEP+ (Comité JMMC) | Reunión de monitoreo | V02 | NINGUNO — Sensor V02 | TESIS_03_Captura_de_Renta | 1) Informe de conformidad de cuotas (conformity rate); 2) Planes de compensación por sobreproducción; 3) Recomendación estatutaria sobre condiciones de mercado | LATENTE | 68ª reunión del Comité Ministerial Conjunto de Seguimiento (JMMC) de la OPEP+. Monitoreo del cumplimiento y de balances físicos globales. | [OPEC Calendar of Meetings](https://www.opec.org/opec_web/en/press_room/28.htm) |
| `E_2026_10_06_US_International_Trade_August` | 2026-10-06 | RECURRENTE OFICIAL | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Identificar categorías aranceladas; 2) Variación interanual (YoY); 3) Comprobar si caída supera -15% YoY (posible mes 1); 4) Déficit bilateral | ELEVADO | Primer dato comercial post-arancel susceptible de constituir mes 1 del Trigger D si las importaciones en sectores cubiertos caen >15% YoY según Census/BEA. | [Census International Trade Data](https://www.census.gov/foreign-trade/data/index.html) |
| `E_2026_10_07_08_US_Treasury_10Y_30Y_Reopenings` | 2026-10-07/08 | RECURRENTE OFICIAL | U.S. Treasury | Subasta soberana | V01 | V01 — Absorción soberana de duración | TESIS_01_Dominancia_Fiscal | 1) Bid-to-cover ratio (si BTC < 2,30x tras septiembre, activa Trigger 03 de V01); 2) Tail frente al mercado when-issued; 3) Asignación indirecta | LATENTE | Reapertura de subastas a 10 y 30 años de octubre. Contraste de persistencia de absorción para evaluar si se consuma el Trigger 03 de V01 (<2,30x en 2 emisiones). | [TreasuryDirect Auctions](https://www.treasurydirect.gov/instit/annceresult/annceresult.htm) |
| `E_2026_10_08_TSMC_September_Sales` | 2026-10-08 | RECURRENTE OFICIAL | TSMC | Ingresos corporativos | V03 | V03 — Ciclo de fundición y demanda | TESIS_06_IA_como_silicio_y_energia | 1) Facturación mensual en NT$; 2) Crecimiento YoY; 3) Cierre consolidado del 3T vs guidance trimestral (inferencia); 4) Variación acumulada 2026 | LATENTE | Facturación de septiembre y cierre trimestral de TSMC. Sensor agregado de demanda; no desglosa nodos 3nm/5nm ni cuellos de botella CoWoS/HBM. | [TSMC Monthly Revenue Reports](https://investor.tsmc.com/english/monthly-revenue) |
| `E_2026_10_16_US_TIC_Securities_Data` | 2026-10-16 | RECURRENTE OFICIAL | U.S. Treasury | Estadística financiera | V01 | Japón/Liquidez — Trigger A | TESIS_01_Dominancia_Fiscal | 1) Comprobar si agosto presenta compras netas negativas japonesas condicionado a que julio haya sido negativo; 2) Cumplimiento acumulado de Trigger A | CRÍTICO | Datos TIC de agosto. Comprobación de si agosto constituye un segundo mes consecutivo de ventas netas japonesas, necesario para satisfacer el Trigger A. | [Treasury TIC System](https://home.treasury.gov/data/treasury-international-capital-tic-system) |
| `E_2026_10_28_Fed_FOMC_Decision` | 2026-10-27/28 | CONFIRMADO | Reserva Federal | Decisión monetaria | V01 | V01 — Política monetaria | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre tipo de fondos federales; 2) Tono del comunicado sobre riesgos de empleo e inflación; 3) Mensaje sobre estabilidad de reservas antes de elecciones | ELEVADO | Reunión de política monetaria intermedia (sin SEP). Calibra las condiciones de liquidez monetaria una semana antes de las elecciones legislativas estadounidenses. | [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| `E_2026_10_30_BoJ_MPM_Outlook` | 2026-10-29/30 | CONFIRMADO | Banco de Japón | Decisión monetaria | V01 | Japón/Liquidez — Carry trade | TESIS_01_Dominancia_Fiscal | 1) Decisión sobre objetivo del tipo overnight; 2) Proyecciones plurianuales de PIB e inflación 2026–2027 en el Outlook Report; 3) Evaluación del tipo de cambio | ELEVADO | Reunión trimestral con Outlook Report del BoJ. Determina la trayectoria esperada de tipos de interés para finales de 2026 e inicios de 2027. | [Bank of Japan Releases](https://www.boj.or.jp/en/mopo/index.htm) |
| `E_2026_11_02_US_Treasury_Financing_Estimates` | 2026-11-02 | RECURRENTE OFICIAL | U.S. Treasury | Estimación financiera | V01 | V01 — Necesidades de endeudamiento | TESIS_01_Dominancia_Fiscal | 1) Estimación oficial de endeudamiento neto para el 4T 2026 y 1T 2027; 2) Saldo objetivo de caja TGA al cierre de año; 3) Proporción estimada bills vs cupones | ELEVADO | Publicación de necesidades de financiación previas al Refunding. Fija la escala de liquidez requerida por el Tesoro de los mercados primarios. | [U.S. Treasury Refunding](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding) |
| `E_2026_11_03_US_Midterm_Elections` | 2026-11-03 | CONFIRMADO | Electorado de EE. UU. / Congreso | Elección política | V06 | NINGUNO — Sensor político-fiscal | TESIS_01_Dominancia_Fiscal, TESIS_04_Multipolaridad_Logistica | 1) Mayorías parlamentarias en Cámara y Senado; 2) Margen legislativo para sostener o modificar aranceles; 3) Perspectiva sobre prórroga fiscal y techo de deuda en 2027 | ELEVADO | Elecciones de mitad de mandato en EE. UU. Condicionan la arquitectura fiscal y el margen de ejecución de la política comercial y regulatoria federal. | [Federal Election Commission](https://www.fec.gov/) / [Congress.gov](https://www.congress.gov/) |
| `E_2026_11_04_US_Treasury_Quarterly_Refunding` | 2026-11-04 | CONFIRMADO | U.S. Treasury | Emisión soberana | V01 | V01 — Política de emisión y colateral | TESIS_01_Dominancia_Fiscal | 1) Tamaños de subastas en tramos 2Y, 5Y, 10Y y 30Y; 2) Cuota de financiación vía T-Bills respecto a deuda cupón; 3) Decisión sobre el programa de buybacks; 4) Informe TBAC | RÉGIMEN | Anuncio formal de política de refinanciación de la deuda de EE. UU. Determina si el tramo largo de la curva soberana sufre sobresaturación o racionamiento de colateral. | [U.S. Treasury Refunding](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding) |
| `E_2026_11_04_US_International_Trade_September` | 2026-11-04 | RECURRENTE OFICIAL | U.S. Census / BEA | Estadística comercial | V04 | Tariff Stack — Trigger D | TESIS_02_Frictionless_Stabilization, TESIS_04_Multipolaridad_Logistica | 1) Comprobar si septiembre presenta caída >15% YoY en sectores cubiertos Y si agosto ya cumplió >15% YoY; 2) Activación completa de Trigger D | CRÍTICO | Balanza comercial de septiembre. Punto resolutivo para la activación formal del Trigger D si se encadenan dos meses consecutivos con caída >15% YoY. | [Census Foreign Trade](https://www.census.gov/foreign-trade/data/index.html) |

---

## 1. VENTANAS ENRIQUECIDAS

### [VEN_2026_09_24_Cumbre_Xi_US] — Cumbre Bilateral Washington-Pekín

- **Fecha / ventana:** 2026-09-24
- **Estado de confirmación:** ANUNCIADO — confirmación bilateral pendiente (Anuncio unilateral de la Casa Blanca; registro oficial chino: sin confirmación formal localizada al corte de W36).
- **Vector primario:** [[VECTOR_04_Reconfiguracion_del_comercio_global]]
- **Vectores secundarios:** [[VECTOR_06_Orden_geopolitico_y_esferas_de_influencia]], [[VECTOR_03_Semiconductores_y_soberania_tecnologica]]
- **Evento(s) sensor:** [[Evento_E1_2026_07_24_US_Tariff_Stack]] · [[Evento_E0_2026_CoWoS_Capacity]]
- **Tesis conectadas:** [[TESIS_02_Frictionless_Stabilization]] · [[TESIS_04_Multipolaridad_Logistica]] · [[TESIS_06_IA_como_silicio_y_energia]]

#### Hipótesis ex ante
Se formula la hipótesis ex ante de si el encuentro posibilitará una estabilización táctica regulada en aranceles y controles frente a la inercia estructural de la fragmentación tecnológica. Bajo un escenario de estabilización transaccional, se evaluarían compromisos comerciales a cambio de congelar incrementos arancelarios, mientras se negociaría el alcance de los controles sobre aceleradores de IA y el suministro de minerales críticos. Bajo un escenario de divergencia, la falta de acuerdos formales consolidaría los aranceles vigentes e impulsaría nuevas listas de entidades restringidas.

#### Observables (1–4)
1. **Órdenes ejecutivas arancelarias:** Publicación en el *Federal Register* de enmiendas formales, exenciones sectoriales o congelación de los aranceles generales del 10% y tramos del Tariff Stack.
2. **Normativa de exportación del BIS:** Publicación o aplazamiento formal de nuevas normas del Departamento de Comercio de EE. UU. sobre memoria HBM, GPUs avanzadas o herramientas de litografía/EDA.
3. **Licencias de minerales críticos:** Resoluciones oficiales del Ministerio de Comercio de China (MOFCOM) sobre cuotas o levantamiento de restricciones de exportación de galio, germanio y antimonio.
4. **Instrumento institucional:** Existencia de un Comunicado Conjunto o Memorando de Entendimiento con compromisos normativos verificables frente a meras conferencias de prensa bilaterales separadas.

#### Resultado material si...
Se publica un acuerdo formal que modifique o suspenda aranceles de forma vinculante (descompresión en V04), se alteren de forma sustantiva las listas de entidades o controles del BIS (revisión en V03), o se formalicen cupos garantizados de exportación mineral. Exigiría revisión de presiones en V04 y V03.

#### Resultado no material si...
El encuentro concluye con declaraciones genéricas de gestión responsable de relaciones diplomáticas sin alteración de órdenes ejecutivas arancelarias, sin cambios en las listas de entidades del BIS y manteniendo intactas las restricciones a minerales críticos.

#### Qué NO significaría
Un tono diplomático constructivo no significaría el fin del desacoplamiento tecnológico ni el restablecimiento de la globalización multilateral previa a 2018. Tampoco un desacuerdo verbal constituiría un nuevo arancel automático sin acto legal formal en el *Federal Register*.

#### Acción al resolverse
Auditoría forense de los cuatro observables en fuentes primarias (Federal Register, White House, MOFCOM, Xinhua) en la revisión de W39; clasificación en `MATERIAL` o `NO MATERIAL`; y remisión a los eventos activos. Cero cambios ex ante en estados del sistema.

---

## 2. OBSERVATORIOS ESTRUCTURALES

### 1. Observatorio de Riesgo Marítimo y Seguridad de Chokepoints (Ormuz y Bab el-Mandeb)
- **Vectores:** [[VECTOR_02_Energia_y_nodos_geoeconomicos]], [[VECTOR_04_Reconfiguracion_del_comercio_global]], [[VECTOR_01_Arquitectura_monetaria_global]]
- **Evento conectado:** [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb]]
- **Variables monitoreadas:** 
  1. Recuento oficial de ataques y bajas marítimas por la OMI (actual: 72 incidentes confirmados, 21 fallecidos).
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
  2. Emisión de órdenes de emergencia bajo Sección 202(c) de la Federal Power Act por el Department of Energy (DOE).
  3. Declaraciones de alerta de emergencia de energía (EEA 1/2/3) en operadores regionales PJM, MISO y ERCOT.
  4. Moratorias locales formales o denegaciones de derechos de conexión a centros de datos de IA (ej. Loudoun County, Ohio, Texas).
  5. Solicitudes de suministro cautivo de agua o generación nuclear privada co-ubicada.
- **Condición de promoción a tabla calendarizada:** Fijación de fecha formal para votación de órdenes de tarificación en sesión pública de la FERC o vencimiento formal de órdenes administrativas del DOE.

### 3. Observatorio de Capacidad Física de Empaquetado Avanzado y Silicio (CoWoS & HBM)
- **Vectores:** [[VECTOR_03_Semiconductores_y_soberania_tecnologica]], [[VECTOR_02_Energia_y_nodos_geoeconomicos]]
- **Evento conectado:** [[Evento_E0_2026_CoWoS_Capacity]]
- **Variables monitoreadas:**
  1. Hitos de construcción, entrega de salas limpias y ensamblaje de toolings en la gigafab AP7 de TSMC en Chiayi.
  2. Lead times de empaquetado avanzado CoWoS-S/L/R y disponibilidad de sustratos ABF (rango actual: 20–24 semanas).
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

## 3. HITOS EJECUTADOS / CONSUMIDOS (AUDITORÍA W36)

| ID / Hito | Fecha real | Resultado primario verificado | Evento / Vector | Resolución | Acción tomada |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **US ISM Manufacturing PMI** | 2026-09-01 | PMI en 47,2 (vs 46,8 previo), manteniéndose en contracción por quinto mes consecutivo. Precios pagados suben a 54,0. Fuente: ISM. | V05 | `NO MATERIAL` | Retirado de futuros. Diagnóstico de estancamiento manufacturero sin activación de triggers. |
| **Japan 30Y JGB Auction** | 2026-09-03 | Subasta Issue 91 adjudicada por el MOF: cupón 4,0%, precio medio 98,93, **yield medio 4,079%**, precio mínimo aceptado 98,65, **yield cutoff 4,100%**, competitive bids ¥1.728,1B, competitive accepted ¥456,2B, cobertura competitiva calculada 3,788x (~3,79x). Fuente: Ministry of Finance Japan. | Evento Japón · V01 | `NO MATERIAL` | Retirado de futuros. Confirma absorción exitosa de duración por inversores domésticos sin dislocación ni fallo. No activa Trigger A. |
| **US International Trade (Julio)** | 2026-09-03 | Déficit comercial de bienes y servicios se amplió a -$78,8B en julio. Importaciones se mantuvieron firmes antes del despliegue arancelario. Fuente: BEA / Census Bureau. | Evento Tariff Stack · V04 | `NO MATERIAL` | Retirado de futuros. No acredita contracción de flujos pre-aranceles; sienta base de comparación para agosto y septiembre. |
| **US Non-Farm Payrolls (Agosto)** | 2026-09-04 | Creación de empleo no agrícola en +142.000 puestos; tasa de desempleo desciende al 4,2%; salarios medios por hora repuntan +0,4% MoM (+3,8% YoY). Fuente: BLS. | V01 · V05 | `NO MATERIAL` | Retirado de futuros. Despeja recesión abrupta; consolida expectativa de recorte ordenado de 25 bps en FOMC. |

---

## 4. COBERTURA POR VECTOR

| Vector | Filas en tabla | Prioridad Crítica | Prioridad Régimen | Ventana Enriquecida | Observatorio activo | Diagnóstico de cobertura |
| :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **V01: Arquitectura monetaria global** | 14 | 5 | 1 | 0 | Sí (Monetario/Liquidez) | Cobertura exhaustiva: subastas soberanas, TGA, FOMC, BoJ, TIC y Refunding. |
| **V02: Energía y nodos geoeconomicos** | 2 | 0 | 0 | 0 | Sí (2: Lloyd's y Grid Stress) | Cobertura en Observatorios continuos; presencia en tabla vía reunión OPEP+ y JMMC. |
| **V03: Semiconductores y soberanía tech** | 3 | 0 | 0 | 0 | Sí (CoWoS & HBM) | Facturación agregada TSMC y earnings Micron; cumbre bilateral Xi-US. |
| **V04: Reconfiguración del comercio** | 4 | 2 | 1 | 1 | No | Alta potencia cualitativa: contramedidas Canadá, balanzas de agosto/septiembre y Cumbre bilateral. |
| **V05: Transformación industrial y demografía** | 0 | 0 | 0 | 0 | No | **HUECO REAL DECLARADO:** Sin hitos de 60 días capaces de activar sus triggers seculares. |
| **V06: Orden geopolítico y esferas** | 2 | 0 | 0 | 0 | Sí (Geopolítica / Sanciones) | Cobertura institucional (listings UE-Rusia, elecciones intermedias de EE. UU.). |
| **TOTALES CONSOLIDADOS** | **25** | **7** | **2** | **1** | **4** | **1 hueco estructural declarado honestamente** |

---

## 5. COBERTURA POR EVENTO ACTIVO

| Evento Activo del Sistema | Próximo hito sensor en Radar | Fecha programada | Trigger observado | Nivel de cobertura analítica |
| :--- | :--- | :--- | :--- | :--- |
| **`Evento_E0_2026_07_08_Grid_Stress_IA`** | Resoluciones administrativas continuas FERC / DOE | Observatorio continuo | Triggers A, B y C (Órdenes 202c, paradas y moratorias) | Cubierto permanentemente vía Observatorio Estructural 2 |
| **`Evento_E0_2026_08_16_Japon_Carry_Trade_y_Liquidez`** | Liquidación fiscal corporativa EE. UU. (TGA Drain) | 2026-09-15 | Trigger B (TGA > $900B / Salto masivo de caja) | Cobertura máxima: 6 hitos específicos en ventana (TGA, TIC M1, BoJ MPM, Cierre 3T, TIC M2) |
| **`Evento_E0_2026_CoWoS_Capacity`** | Facturación TSMC (Agosto) / Earnings Micron | 2026-09-10 / 2026-09-30 | Sensores agregados de demanda física y memoria HBM | Seguimiento corporativo en agenda; lead times y CoWoS en Observatorio 3 |
| **`Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb`** | Despachos continuos OMI y avisos UKMTO | Observatorio continuo | Triggers A, B y D (Primas $\ge 1,5\%$, daño a VLCC/LNG, corte >5 Mb/d) | Cubierto en tiempo real por Observatorio Estructural 1; sin fecha fija para incidentes cinéticos |
| **`Evento_E1_2026_07_24_US_Tariff_Stack`** | Contramedidas arancelarias de Canadá / Cumbre bilateral | 2026-09-08 / 2026-09-24 | Triggers B (Represalia formal) y D (Contracción física >15% YoY en 2 meses) | Cobertura crítica: entrada en vigor de represalias canadienses, cumbre Xi-EE. UU. y balanzas |

---

## 6. HUECOS REALES DE COBERTURA

1. **Vector 05 (Transformación Industrial y Demografía):**
   - No contiene filas en la tabla futura de los próximos 60 días.
   - **Razón epistemológica:** Los triggers canónicos de V05 exigen verificar: fuga masiva de CAPEX industrial fuera de economías centrales durante varios trimestres, cuotas de importación que compriman cuota industrial durante más de 6 meses, o deterioro anualizado de la ratio de soporte de pensiones. Estos procesos operan a escala secular y no se resuelven mediante series mensuales o eventos de 24 horas. Declarar el hueco evita introducir ruido o lecturas rutinarias que no alteran restricciones.
2. **Fricción Cinética en V02 (Estrecho de Ormuz y Bab el-Mandeb):**
   - Los ataques militares, lanzamientos de misiles y secuestros navales no tienen fecha predeterminada.
   - Se canalizan mediante el **Observatorio Estructural 1**, auditando fuentes primarias (OMI, UKMTO, CENTCOM, LMA) en cada corte semanal para detectar la activación de los Triggers A, B o D sin inventar fechas en la agenda.

---

## 7. FUENTES Y AUDITORÍA DE ESPECIFICIDAD

- **Fecha de corte de auditoría y contraste:** 2026-09-06 00:00 Europe/Madrid.
- **Desglose riguroso del tipo de respaldo primario:**
  - **A. Publicación o notice primario específico (10 filas — 40%):** Enlace directo al documento legal, orden ejecutiva, informe de balance o serie histórica concreta.
    - `E_2026_09_08_Canada_Counter_Tariffs`: [Canada Dept of Finance Notice](https://www.canada.ca/en/department-finance/news/2026/08/countermeasures-to-us-tariffs.html) / [CBSA Customs Notices](https://www.cbsa-asfc.gc.ca/publications/cn-ad/menu-eng.html)
    - `E_2026_09_15_US_Corporate_Tax_TGA_Drain`: [IRS Business Tax Calendar](https://www.irs.gov/businesses/small-businesses-self-employed/tax-calendar) / [Daily Treasury Statement](https://fiscaldata.treasury.gov/datasets/daily-treasury-statement/)
    - `E_2026_09_15_EU_Russia_Sanctions_Renewal`: [Consilium Restrictive Measures](https://www.consilium.europa.eu/en/policies/sanctions/restrictive-measures-against-russia-over-ukraine/)
    - `E_2026_09_16_US_TIC_Securities_Data`: [U.S. Treasury TIC Historical Releases](https://home.treasury.gov/data/treasury-international-capital-tic-system)
    - `E_2026_09_30_US_Quarter_End_Liquidity`: [NY Fed Reference Rates & Operating Policy](https://www.newyorkfed.org/markets/reference-rates)
    - `E_2026_10_06_US_International_Trade_August`: [Census Foreign Trade Release Schedule](https://www.census.gov/foreign-trade/data/index.html)
    - `E_2026_10_16_US_TIC_Securities_Data`: [U.S. Treasury TIC Releases](https://home.treasury.gov/data/treasury-international-capital-tic-system)
    - `E_2026_11_02_US_Treasury_Financing_Estimates`: [U.S. Treasury Quarterly Refunding Schedule](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding)
    - `E_2026_11_04_US_Treasury_Quarterly_Refunding`: [U.S. Treasury Quarterly Refunding Announcements](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding)
    - `E_2026_11_04_US_International_Trade_September`: [Census Foreign Trade Schedule](https://www.census.gov/foreign-trade/data/index.html)
  - **B. Calendario oficial primario (Hub institucional fechado) (14 filas — 56%):** Calendario oficial formal del organismo que programa la fecha del hito:
    - `E_2026_09_06_OPEC_Plus_Core_Meeting`: [OPEC Calendar of Meetings & Press Releases](https://www.opec.org/opec_web/en/press_room/28.htm)
    - `E_2026_09_08_Japan_Monthly_Securities_Flows`: [MOF Japan Balance of Payments Release Schedule](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/)
    - `E_2026_09_09_US_Treasury_Long_End_Buybacks`: [U.S. Treasury Buyback Operating Schedule](https://home.treasury.gov/policy-issues/financing-the-government/quarterly-refunding)
    - `E_2026_09_09_10_US_Treasury_10Y_30Y_Reopenings`: [TreasuryDirect Tentative Auction Schedule](https://www.treasurydirect.gov/instit/annceresult/annceresult.htm)
    - `E_2026_09_10_TSMC_August_Sales`: [TSMC Monthly Revenue Reports](https://investor.tsmc.com/english/monthly-revenue)
    - `E_2026_09_16_Fed_FOMC_Decision`: [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm)
    - `E_2026_09_18_BoJ_MPM`: [Bank of Japan Schedule of MPMs](https://www.boj.or.jp/en/mopo/index.htm)
    - `E_2026_09_30_Micron_FY26_Q4_Earnings`: [Micron Investor Relations Events Calendar](https://investors.micron.com/)
    - `E_2026_10_04_OPEC_Plus_JMMC`: [OPEC Calendar of Meetings](https://www.opec.org/opec_web/en/press_room/28.htm)
    - `E_2026_10_07_08_US_Treasury_10Y_30Y_Reopenings`: [TreasuryDirect Tentative Auction Schedule](https://www.treasurydirect.gov/instit/annceresult/annceresult.htm)
    - `E_2026_10_08_TSMC_September_Sales`: [TSMC Monthly Revenue Reports](https://investor.tsmc.com/english/monthly-revenue)
    - `E_2026_10_28_Fed_FOMC_Decision`: [Federal Reserve FOMC Calendar](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm)
    - `E_2026_10_30_BoJ_MPM_Outlook`: [Bank of Japan Schedule of MPMs](https://www.boj.or.jp/en/mopo/index.htm)
    - `E_2026_11_03_US_Midterm_Elections`: [Federal Election Commission 2026 Election Dates](https://www.fec.gov/) / [U.S. Congress Calendar](https://www.congress.gov/)
  - **C. Anuncio unilateral oficial con confirmación bilateral pendiente (1 fila — 4%):**
    - `VEN_2026_09_24_Cumbre_Xi_US`: Anuncio unilateral de la Presidencia de EE. UU. ([White House Statements and Releases](https://www.whitehouse.gov/briefing-room/statements-releases/)); *registro oficial chino: sin confirmación formal localizada al corte de W36*.
  - **D. Sin fuente oficial localizada (0 filas — 0%).**
- **Respaldo institucional oficial total:** **25 / 25 (100%)**.
