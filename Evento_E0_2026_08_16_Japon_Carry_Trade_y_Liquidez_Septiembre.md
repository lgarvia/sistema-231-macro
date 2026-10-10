---
titulo: "Japón / liquidez"
fecha: 2026-08-16
source: Bank of Japan / Japan Ministry of Finance / U.S. Treasury TIC / Federal Reserve
url: https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260731a.pdf
vector: "[[VECTOR_01_Arquitectura_monetaria_global]]"
moc: "[[MOC_Politica_Monetaria]]"
tags: [liquidez, japon, jgb, carry-trade, treasuries, repo, srf, tga, banca-central]
tipo: evento
ultima_revision: 2026-10-10
corte_factual: "2026-10-10 20:38 Europe/Madrid"
aliases: [Evento_E0_2026_08_16_Japon_Carry_Trade_y_Liquidez_Septiembre, Evento_E0_Japon_Carry_Trade_y_Liquidez_Septiembre]
estado: E0
calibracion: aplicada
presion_numerica: 4
peso_estructural: 4.8
factor_tendencia: 1.2
tendencia_calibrada: "\u2191"
revision_semanal_pendiente: false
decision_aplicada: "Luis — A/B TASK_202, 10-oct-2026"
---

# Japón / liquidez

## 1. Estado actual — precierre W41

**E0 · P4 · peso 4,8 · ↑ (1,2) · carga 23,04 · V01.** Corte 2026-10-10 20:38 Europe/Madrid; nominal 11-oct. Decisión A/B aplicada 10-oct (TASK_202). Pesoordinal, presión y tendencia separados; no probabilidad.

## 2. Evidencia y alcance

[MOF, publicado 08-oct](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/monthEng.pdf): septiembre 2026, deuda exterior larga neta −14.260 unidades de 100 MJPY = **−1,426 billones JPY**; cartera total −219,7 miles de millones JPY. [MOF semanal 08-oct](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/week.pdf): 27-sep–03-oct, deuda larga −347,6 BJPY y cartera total +821,0 BJPY. Las poblaciones/comparaciones institucionales y destinos exigen auditoría; stock TIC no es flujo. [Fed H.4.1 08-oct](https://www.federalreserve.gov/releases/h41/20261008/): media semanal al 07-oct, reservas 3.029.659 MUSD (+81.569), TGA 880.253 MUSD (−68.421); miércoles reservas 3.022.066/TGA 885.783 MUSD. [NYFed SOFR](https://www.newyorkfed.org/markets/reference-rates/sofr): 01/02/05/06/07-oct 3,87/3,88/3,89/3,90/3,88%, IORB 3,90%; diferencial −3/−2/−1/0/−2 pb. Recuperación de reservas no demuestra desaparición de la cuestión japonesa.

Fuentes consultadas 10-oct; solo documentos anteriores al corte. Antecedentes, proyecciones y observaciones se distinguen. Cobertura limitada no prueba ausencia.

## 3. Condiciones y sensores vigentes

| Condición | Auditoría W41 |
|---|---|
| A | NO ACREDITADO COMPLETO: septiembre negativo y agosto antecedente; falta auditar dos meses institucionales comparables y diferencial JGB 30 Y–UST 30 Y cubierto favorable >15 días hábiles. |
| B | PARCIAL HEREDADO: saldos y quincena de impuestos 15-sep documentados; causalidad completa no demostrada. Datos 07-oct no borran historia ni reactivan ventana. |
| C | Rama SOFR NO ACTIVADA CON EVIDENCIA en cinco observaciones recuperadas (≤IORB); no se acredita >8 pb/3 días. Rama GCp 99 NO VERIFICABLE, referencia y serie pendientes. Oct 8/9 no rellenados por inferencia. |
| D | NO VERIFICABLE: ventana 25–30-sep vencida; falta serie diaria SRF que pruebe >20 BUSD/día durante más de 2 días consecutivos. No periodo incompleto ni cero. |


Las condiciones canónicas no se reducen ni cambian por este corte. Umbral, duración, población y causalidad pendientes permanecen explícitos; la selección E0 no activa triggers.

## 4. Transmisión y continuidad

Imputación exclusiva a [[VECTOR_01_Arquitectura_monetaria_global]]. Los canales secundarios no duplican carga. Luis aprueba el paquete con «Acepto todo esto. Dale y sigue con el siguiente paso» (10-oct, TASK_202). Alta España E0/P2/peso 4,2/→/V01; Alibaba absorbido en V03; Francia y aranceles pasan de ↑ a →. Los tres pesos previamente decididos permanecen. Sin nuevas E1.

[[ACTUALIZACION_SEMANAL_231_2026_10_11]] · [[Radar_Eventos_2026_10]] · [[VECTOR_00_Indice]].


<details>
<summary>Estado anterior W40 y memoria previa; sustituido por W41</summary>

# EVENTO: E0_2026_08_16_Japon_Carry_Trade_y_Liquidez_Septiembre

## 1. Estado actual — precierre W40

**E0 · P4 · peso 4,8 · ↑ (1,2) · carga 23,04 · V01.** Decisiones A/B de Luis aplicadas el 03-oct; corte 2026-10-03 02:06 Europe/Madrid. Ajuste decimal solicitado por incidencia semanal relativa, con alcance estructural como ancla; no medición empírica. Clase, presión y tendencia conservadas.

[H.4.1, publicado 01-oct](https://www.federalreserve.gov/releases/h41/current/): al 30-sep TGA 984.046 M USD (+36.729 frente a 23-sep) y reservas 2.881.686 M USD (−88.236); media semanal de reservas 2.948.090 M USD (+17.897), distinta del saldo puntual. [SOFR](https://fred.stlouisfed.org/series/SOFR) 25/28/29/30-sep y 01-oct: 3,90/3,90/3,88/3,90/3,87%, frente a [IORB](https://fred.stlouisfed.org/series/IORB) 3,90%: 0/0/−2/0/−3 pb. No activa la rama SOFR (>8 pb durante tres días). SRF diario y GC p99 no verificables; el repo en balance de 1.200 M USD no es volumen diario SRF. SOFR 02-oct se publica fuera del corte. [MOF, publicado 01-oct](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/week.pdf): ventas netas de deuda exterior larga de 1.904,9 y 684,5 miles de millones JPY en 13–19 y 20–26-sep. Revisión 06–12-sep: +1.082,9 → +1.091,0 (+8,1). Dos semanas no cumplen dos meses; falta diferencial 30Y cubierto >15 días hábiles. B parcial por saldos y causalidad incompleta; D, ventana vencida, NO VERIFICABLE sin SRF diario. Peso baja dos décimas por menor incidencia tras el cierre, manteniendo relevancia alta.

Fuentes consultadas 03-oct; solo publicaciones anteriores al corte. Condiciones no acreditadas completas no se marcan como activadas. Las secciones históricas mantienen su fecha; prevalece este snapshot y [[ACTUALIZACION_SEMANAL_231_2026_10_04]]. Radar activo [[Radar_Eventos_2026_10]].

<details>
<summary>Snapshot W39 sustituido; se conserva la calibración anterior</summary>

## 1. SNAPSHOT ACTUAL — precierre W39

**E0 · P4 · peso 5 · ↑ (1,2) · carga 24,0 · V01.** Calibración conservada conforme a A/B; aplicación 27-sep, corte 2026-09-26 20:48 Europe/Madrid.

BoJ: objetivo 1,25% vigente desde 24-sep, conforme a la decisión publicada el 18-sep. H.4.1 publicado 24-sep: al 23-sep TGA **947.317 M$** y reservas **2.969.922 M$**, frente a 991.708 y 2.921.536 M$ al 16-sep: −44.391 y +48.386 M$. La media semanal de reservas, 2.930.193 M$, cae 83.601 M$: distinguir saldo puntual de promedio. La recuperación puntual es contraevidencia de drenaje continuo.

SOFR 18/21/22/23/24-sep: **3,85/3,85/3,87/3,87/3,88%** frente a IORB 3,90% (−5/−5/−3/−3/−2 pb). El SOFR del 25-sep no estaba publicado al corte; su publicación corresponde al 28-sep. No se recuperó la serie diaria SRF reciente: no se imputa cero. MOF conserva como último dato recuperado +1.082,9 miles de millones de yenes, semana 06–12-sep. Su calendario fija para **1-oct** las semanas 13–19 y 20–26-sep; el retraso no prueba retirada de capital. Aún falta la serie del diferencial 30Y cubierto.

Fuentes consultadas 26–27-sep, publicaciones dentro del corte: [BoJ 18-sep](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf), [H.4.1 24-sep](https://www.federalreserve.gov/releases/h41/current/), [SOFR](https://fred.stlouisfed.org/series/SOFR), [IORB](https://fred.stlouisfed.org/series/IORB), [MOF calendario](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm). Se conserva ↑ aprobado: describe presión acumulada; no una nueva aceleración probada por esta semana.

Auditoría de cláusulas en §2 e informe [[ACTUALIZACION_SEMANAL_231_2026_09_27]].

</details>

## 2. CONDICIONES DE ACTIVACIÓN (TRIGGERS)

- **Trigger A (Flujos de Ahorro Japonés y Deuda Exterior):** El diferencial de rentabilidad entre el JGB a 30 años y el U.S. Treasury a 30 años cubierto a yenes se mantiene favorable al bono japonés durante más de 15 días hábiles consecutivos, acompañado por dos meses consecutivos de compras netas negativas (o desinversión/no reinversión) de bonos extranjeros por parte de inversores institucionales japoneses según datos del Ministerio de Finanzas de Japón o el Treasury International Capital (TIC). **Estado al corte: NO ACREDITADO COMPLETO: faltan >15 días hábiles de diferencial 30Y cubierto favorable y dos meses consecutivos de flujos institucionales comparables. MOF publicará dos semanas el 1-oct; stock TIC no sustituye flujo.**
- **Trigger B (Drenaje Fiscal TGA y Reservas):** Los pagos de impuestos corporativos del 15 de septiembre elevan la Treasury General Account (TGA) por encima de 900 B$, provocando un drenaje de reservas bancarias agregadas por debajo de los 3,1 billones de dólares en la misma quincena. **Estado al corte: PARCIAL: TGA >900 B$ y reservas <3,1 T$ observados; la causalidad exclusiva y el cruce por impuestos no están acreditados, pues ya existía la precondición y contribuye financiación. Recuperación puntual de reservas al 23-sep.**
- **Trigger C (Stress en Mercados Monetarios / SOFR):** El tipo de interés garantizado a un día (SOFR) cotiza por encima del tipo de interés sobre saldos de reservas (IORB) en más de 8 puntos básicos durante 3 días hábiles consecutivos, o la dispersión del percentil 99 en repo general collateral supera los 25 bps. **Estado al corte: RAMA SOFR NO ACTIVADA con evidencia publicada: diferencias −5/−5/−3/−3/−2 pb, no >+8 durante tres días. La rama GC p99 carece de referencia canónica inequívoca y de serie comparable; no verificable.**
- **Trigger D (Uso de Facilidad de Respaldo SRF):** La Standing Repo Facility (SRF) de la Reserva Federal registra operaciones de provisión de liquidez superiores a 20 B$ diarios durante más de dos días consecutivos alrededor del cierre de trimestre (25–30 de septiembre). **Estado al corte: PERIODO INCOMPLETO: ventana 25–30-sep en curso. Serie SRF diaria reciente no recuperada; no se acredita >20 B$ por más de dos días ni se presume cero.**

---

## 3. CONTEXTO Y SEÑAL DOMINANTE

La lectura vigente es §1 y la auditoría §2. Se conserva clase, P y tendencia aprobadas; el histórico no añade activaciones. La diferencia frente al subtotal 90,4 del piloto es +54,4: +32,4 por tres altas y +22,0 por calibrar Xi, midterms y Unitree, ya admitidos. No es una variación semanal homogénea ni demuestra empeoramiento de 54,4 puntos. Las cinco fichas base conservan P/peso/tendencia y suman 90,4. La carga es ordinal, no probabilidad ni pérdida esperada; solo se imputa una vez por vector primario.

## 4. TESIS (Luis)

La política monetaria en 2026 ya no se juega en las ruedas de prensa sobre tipos de interés, sino en la microestructura de la fontanería financiera:
1. **La Dominancia Fiscal exige compradores inelásticos de duración.** Cuando el ahorro japonés deja de cruzar el Pacífico porque en Tokio el dinero vuelve a tener precio, la prima por plazo (*term premium*) de la deuda soberana occidental tiene que subir para compensar la retirada del comprador marginal.
2. **La liquidez no es una masa homogénea, es una red de distribución.** La fragilidad del sistema bancario no depende del volumen total de reservas impresas, sino de la velocidad y fricción regulatoria con la que esas reservas llegan a los balances de los *dealers* en momentos de estrés. Septiembre 2026 pondrá a prueba los amortiguadores institucionales creados tras 2019 (la SRF).

---

## 5. IMPLICACIONES Y TRANSMISIÓN

- **Transmisión Principal:** V01 (Tipos BoJ / JGB 30Y) → V01 (Term Premium en Treasuries / Absorción de subastas) → V01 (Mercado Repo / Drenaje TGA) → V04 (Flujos de capital y tipo de cambio USD/JPY).
- **Canal de Deuda Soberana:** Aumento de rentabilidades exigidas en emisiones a 10 y 30 años de EE. UU., Alemania y Francia, encareciendo el servicio de la deuda pública.
- **Canal de Financiación Privada:** El encarecimiento de la deuda soberana arrastra los tipos hipotecarios y corporativos a largo plazo, limitando el efecto expansivo de eventuales recortes de tipos a corto plazo de la Reserva Federal.
- **Canal de Desarme de Carry Trade:** Volatilidad cambiaria súbita en activos de riesgo apalancados en yenes baratos.

---

## 6. HISTORIAL FACTUAL

- **19/03/2024**: El Banco de Japón puso fin al tipo de interés negativo y al marco de control de la curva. Fuente: [BoJ — decisión de marzo de 2024](https://www.boj.or.jp/en/mopo/mpmdeci/state_2024/k240319a.htm).
- **05/08/2024**: Se produjo el episodio de referencia de desarme global del *yen carry trade*. Fuente: [BIS Bulletin 90](https://www.bis.org/publ/bisbull90.pdf).
- **17/06/2026**: El BoJ elevó el tipo oficial alrededor del 1,0%.
- **31/07/2026**: El BoJ **mantuvo** el tipo alrededor del 1,0% por 8 votos a 1; Takata propuso 1,25%. Fuente: [BoJ — decisión de julio de 2026](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260731a.pdf).
- **06/08/2026**: La subasta oficial del JGB a 30 años registró rendimiento medio de 3,937%, mínimo aceptado de 3,952% y cupón de 4,0%. Fuente: [Ministerio de Finanzas de Japón](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260806.htm).
- **03/09/2026**: La subasta oficial del JGB a 30 años (Issue 91) cortó a un rendimiento medio de **4,079%** (yield mínimo aceptado 4,100%, cupón 4,0%) con una cobertura competitiva de **3,79x** (¥1.728,1B ofertados / ¥456,2B aceptados), confirmando consolidación del rendimiento largo nipón sobre el 4% con absorción ordenada. Fuente: [MOF Japón](https://www.mof.go.jp/).

---

## 7. ACTUALIZACIÓN FACTUAL RECIENTE

- **16/08/2026 — entrada suplantada el 17/08/2026**: la versión inicial mezclaba la normalización de 2024 con decisiones de 2026 y trataba un stock TIC como flujo. No se usa como evidencia.
- **17/08/2026**: Auditoría forense completada. El BoJ mantuvo el 31-jul el tipo alrededor del 1,0%; el JGB 30 años se adjudicó el 06-ago a 3,937% de rendimiento medio; y Japón tenía 1.143,1 mil millones de dólares en Treasuries en mayo. No existe todavía evidencia suficiente de ventas persistentes, tensión repo o uso de SRF que active A–D. **Acción: mantener E0, P4 y ajustar tendencia a →.** Fuentes: [BoJ](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260731a.pdf), [MOF Japón](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260806.htm), [Treasury TIC](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table5.html).
- **23/08/2026**: El TIC de junio registró una entrada neta total de **133,5 B$** y compras extranjeras netas de valores estadounidenses a largo plazo de **207,1 B$**. Dentro del stock por país, Japón bajó a **1.116,7 B$**, desde 1.143,1 B$ en mayo y 1.209,9 B$ en abril: la secuencia es compatible con menor reinversión, pero el TIC no permite atribuirla por sí sola a repatriación y no se verificó el diferencial cubierto durante 15 días. El 19/08 la TGA estaba en 936,406 B$ y las reservas bancarias en 2.930,817 B$, precondición del Trigger B antes de su ventana temporal; del 17 al 20/08 el SOFR permaneció alrededor de IORB y la SRF no mostró uso material. La deuda bruta cruzó 40 T$ el 18/08 y el Tesoro duplicó a al menos 4 B$ las recompras de apoyo de liquidez por operación en los tramos largos desde el 09/09. **Acción: actualizar y mantener E0 · P4; elevar tendencia a ↑ por acumulación de precondiciones, sin activar A–D.** Fuentes: [Treasury TIC — comunicado de junio](https://home.treasury.gov/news/press-releases/sb0606/), [TIC — principales tenedores](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table5.html), [Fed H.4.1 — 20/08](https://www.federalreserve.gov/releases/h41/current/h41.htm), [NY Fed — SOFR](https://markets.newyorkfed.org/api/rates/secured/sofr/search.json?startDate=2026-08-17&endDate=2026-08-21&type=rate), [NY Fed — repo/SRF](https://www.newyorkfed.org/markets/desk-operations/repo), [FiscalData — Debt to the Penny](https://fiscaldata.treasury.gov/datasets/debt-to-the-penny/), [Tesoro — recompras de apoyo de liquidez](https://home.treasury.gov/news/press-releases/sb0607).
- **29/08/2026**: El H.4.1 publicado el 27/08 situó, a 26/08, la **TGA en 959,435 B$** y las reservas en **2.916,824 B$**: la precondición cuantitativa del Trigger B se estrecha, pero sigue faltando el nexo temporal de los pagos fiscales del 15/09. La NY Fed sólo mostró el 25/08 un ejercicio de pequeño valor de 3 M$ en la primera operación SRF y cero en la segunda; no hay uso material ni evidencia nueva que active C o D. No se ha publicado otro TIC mensual ni se ha probado el diferencial cubierto del Trigger A. **Acción: mantener E0 · P4 · ↑; A–D sin activación completa.** Fuentes: [Fed H.4.1 — 27/08](https://www.federalreserve.gov/releases/h41/current/), [NY Fed — operaciones repo](https://www.newyorkfed.org/markets/desk-operations/repo), [Treasury TIC — principales tenedores](https://ticdata.treasury.gov/Publish/slt_table5.html).
- **06/09/2026 — W36**: Auditoría y corrección forense de la subasta del JGB 30Y (Issue 91): el yield medio oficial fue de **4,079%** (yield cutoff 4,100%) con ratio de cobertura competitiva de **3,79x** (¥1.728,1B demandados frente a ¥456,2B aceptados), descartando el dato preliminar erróneo de 2,34%. En EE. UU., el H.4.1 sitúa la TGA en **959,380 B$** y las reservas bancarias en **2.912,000 B$** (Deuda total: 40,031 T$). El SOFR opera en 3,63%–3,64% vs IORB de 3,65% y el uso de la SRF permanece en **0 M$**, confirmando ausencia de fricción en la fontanería monetaria. La persistencia de las precondiciones sin aceleración material de liquidez ni fallos de absorción justifica ajustar la tendencia de acelerando (↑) a estable (→). Las fechas clave (15-sep impuestos/TGA, 16-sep FOMC, 18-19-sep BoJ) quedan registradas como horizontes futuros. **Acción en W36: mantener E0 · P4; ajustar tendencia de ↑ a →; Trigger A parcial, Trigger B precursor, Triggers C y D inactivos.** Fuentes: [MOF Japón](https://www.mof.go.jp/), [Federal Reserve H.4.1](https://www.federalreserve.gov/releases/h41/), [NY Fed Markets Data](https://markets.newyorkfed.org/).
- **12/09/2026 — precierre W37**: La subasta JGB 10Y del 01/09 cortó con rendimiento medio de **2,995%** y rendimiento al precio mínimo de **3,011%**; el 30Y del 03/09 quedó en 4,079%/4,100%, no cerca del 5%. En agosto, los inversores designados por MOF fueron vendedores netos de deuda extranjera a largo plazo por **¥143,0B**, pero compradores netos de cartera total por **¥136,6B**; la semana 30/08–05/09 registró además **+¥111,9B** en deuda extranjera a largo plazo. Al 09/09, H.4.1 sitúa TGA en **843,705 B$** y reservas en **3.036,508 B$**; SOFR está en 3,64% frente a IORB de 3,65%. El dato semanal completo de W37 no se publicará hasta el 17/09. **Acción: mantener E0 · P4 · →; A–D inactivos y conservar el 15/09 como test futuro.** Fuentes: [MOF — subasta JGB 10Y](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260901.htm), [MOF — flujos mensuales](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/monthEng.pdf), [MOF — flujos semanales](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/week.pdf), [Fed H.4.1](https://www.federalreserve.gov/releases/h41/Current/).

---

## 8. VALIDACIÓN FRONT OFFICE
- **16/08/2026:** Alta de la ficha en E0 · P4 · ↑ aprobada por Front Office para monitorizar la absorción de deuda soberana, flujos japoneses y la fontanería de liquidez de septiembre.
- **17/08/2026:** corrección factual, mantenimiento E0 · P4 y tendencia → aprobados por instrucción de puesta a punto integral.
- **23/08/2026:** actualización W34, mantenimiento E0 · P4 y tendencia ↑ ejecutados por instrucción de Front Office.
- **29/08/2026:** actualización W35, mantenimiento E0 · P4 y tendencia ↑ ejecutados por instrucción de Front Office.
- **06/09/2026:** corrección de datos JGB (yield 4,079%, ratio 3,79x) y ajuste de tendencia a → ejecutados por instrucción de Front Office en auditoría canónica W36.
- **12/09/2026:** precierre W37 y mantenimiento E0 · P4 · → ejecutados por instrucción de Front Office; A–D permanecen inactivos.

## Rectificación y reconciliación — 06/09/2026 (TASK_090)

El calendario oficial sitúa la reunión en **17–18 sep**, no 18–19 sep ([BoJ](https://www.boj.or.jp/en/mopo/mpmsche_minu/index.htm)). El resultado MOF acredita yield medio/corte e importes ofertados/adjudicados, pero no identifica por sí solo al comprador final: queda suplantada cualquier atribución de «absorción doméstica» basada exclusivamente en esa tabla. Fuente: [MOF, subasta 03/09](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260903.htm); consulta 06/09. No se cambian clase, presión, tendencia ni triggers.

## Revisión W38 — 19/09/2026 (TASK_116)

- BoJ: decisión del 18/09 de elevar el objetivo a **1,25%**, efectiva el **24/09**; al corte sigue en torno al **1,00%**. [BoJ, decisión y anexo](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf).
- Fed: alza de 25 pb a **3,75–4,00%**; IORB **3,90%** desde el 17/09. [FOMC](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260916a.htm) y [implementación](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260916a1.htm).
- H.4.1 publicado el 17/09, observación puntual del 16/09: TGA **991,708 B$**, reservas **2.921,536 B$**. No son promedios semanales. [Fed H.4.1](https://www.federalreserve.gov/releases/h41/Current/).
- DTS: caja al cierre del 14/09 **871,224 B$**, 15/09 **991,557 B$**, 16/09 **991,708 B$**, 17/09 **972,675 B$**. El 15/09 entran **51,579 B$** de impuestos corporativos; la emisión neta de deuda aporta también **43,261 B$**. [DTS caja](https://api.fiscaldata.treasury.gov/services/api/fiscal_service/v1/accounting/dts/operating_cash_balance?filter=record_date:gte:2026-09-14,record_date:lte:2026-09-17&page[size]=100) y [DTS flujos](https://api.fiscaldata.treasury.gov/services/api/fiscal_service/v1/accounting/dts/deposits_withdrawals_operating_cash?filter=record_date:eq:2026-09-15&page[size]=500).
- SOFR–IORB: **−3, −1, −3 y −5 pb** para 14–17/09. SRF: **0, 102, 254, 2 y 1 M$** diarios, 14–18/09, sumando las dos operaciones de cada día. SOFR del 18/09 todavía no disponible al corte. [SOFR](https://markets.newyorkfed.org/api/rates/secured/sofr/search.json?startDate=2026-09-12&endDate=2026-09-18&type=rate) y [repo/SRF](https://markets.newyorkfed.org/api/rp/results/search.json?startDate=2026-09-14&endDate=2026-09-18&operationTypes=Repo).
- TIC julio publicado el 16/09: stock japonés **1.103,9 B$** frente a **1.116,7 B$** en junio; variación **−12,8 B$**, que no equivale a ventas netas. Entrada TIC agregada **83,7 B$**; no es flujo japonés. [TIC julio](https://home.treasury.gov/news/press-releases/sb0631/) y [tenencias por país](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table5.html).
- MOF publicado el 17/09: compras netas japonesas de deuda exterior a largo plazo de **1.082,9 miles de millones de yenes**, semana 06–12/09; la anterior queda revisada a **111,4**, frente a 111,9 en W37. Agosto mensual sigue en **−143,0**. [MOF semanal](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/week.pdf) y [MOF mensual](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/monthEng.pdf).

La tendencia pasa de → a ↑ por el aumento observado de TGA y la caída de reservas dentro de la ventana fiscal, junto a la nueva decisión japonesa. La clase sigue E0 porque B está parcialmente acreditado y A/C/D no alcanzan activación completa. La señal no equivale a desarme de carry ni a crisis repo.

Ejecución autorizada por Luis el 19/09; juicio técnico del agente, sin atribuir validación posterior al Front Office. Detalle: [[ACTUALIZACION_SEMANAL_231_2026_09_20]].

<details>
<summary>Snapshot y contexto sustituidos de W37 — memoria, no estado vigente</summary>

### Snapshot anterior
- **Estado:** 🟠 En observación intensificada — E0; NORMALIZACIÓN JAPONESA / TEST DE LIQUIDEZ DE SEPTIEMBRE
- **Nivel de presión:** ELEVADA (P4)
- **Dirección de tendencia:** → Estable
- **Peso estructural:** 4
- **Última actualización:** 2026-09-12 (precierre W37; corte 21:21 CEST)
- **Contribución primaria:** 4 × 4 × 1,0 = **16,0**
- **Vector primario:** [[VECTOR_01_Arquitectura_monetaria_global]]
- **Vectores secundarios:** [[VECTOR_04_Reconfiguracion_del_comercio_global]], [[VECTOR_02_Energia_y_nodos_geoeconomicos]]
- **KPIs Actuales:**
  - JGB a 30 años: la subasta oficial del 03/09/2026 (Issue 91) cortó con rendimiento medio de **4,079%**, yield al precio mínimo aceptado de **4,100%** (precio de corte 98,65), precio medio de 98,93 y cupón nominal del 4,0%. La cobertura competitiva se situó en **3,79x** (oferta de ¥1.728,1B frente a ¥456,2B aceptados), con demanda competitiva superior al importe aceptado. La tabla no identifica la residencia del comprador final. Fuente específica: [MOF, 03/09/2026](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260903.htm).
  - JGB a 10 años: la subasta oficial del 01/09/2026 registró rendimiento medio de **2,995%** y rendimiento al precio mínimo aceptado de **3,011%**; el 30Y está alrededor del 4,1%, no cerca del 5%.
  - Tipo oficial del BoJ: alrededor de **1,0% desde el 17/06/2026**; confirmado en 1,0% el 31/07. Próxima reunión MPM el **17–18 de septiembre**, según [calendario BoJ](https://www.boj.or.jp/en/mopo/mpmsche_minu/index.htm).
  - Tenencias japonesas de Treasuries: **1.116,7 mil millones de dólares** (TIC junio 2026, publicado en agosto). Próxima entrega de datos TIC a mediados de septiembre.
  - TIC de junio: entrada neta total de 133,5 B$ y compras extranjeras netas de valores estadounidenses a largo plazo de 207,1 B$; no existe retirada extranjera agregada.
  - Flujos MOF de agosto: los inversores designados registraron **−¥143,0B** netos en deuda extranjera a largo plazo, pero el total de inversión de cartera fue **+¥136,6B**; en la semana 30/08–05/09 la deuda extranjera a largo plazo volvió a **+¥111,9B**. Hay un mes negativo, no dos meses consecutivos acreditados.
  - Liquidez al 09/09 (Fed H.4.1): TGA en **843,705 B$** y reservas bancarias en **3.036,508 B$**. El umbral doble del Trigger B ya no se cumple simultáneamente y la ventana causal del 15/09 aún no ha ocurrido.
  - Repo / Fontanería: SOFR en **3,64%** frente a IORB de **3,65%** hasta el 09/09; sin uso material de la SRF ni señal que active C o D.
  - Ventana de estrés identificada: 15 al 30 de septiembre (pagos fiscales corporativos, absorción de emisiones Treasury, recarga de TGA y cierre de trimestre Q3).

---


### Contexto anterior

Durante décadas, los tipos japoneses muy bajos incentivaron la búsqueda de rendimiento exterior y la financiación en yenes. El BoJ puso fin al tipo negativo y al marco de control de curva el **19/03/2024**, no en 2026. En 2026 la señal relevante es una fase posterior de normalización: tipo oficial en torno al 1,0% y rendimientos largos próximos al 4%.

La subida de los rendimientos de los bonos a muy largo plazo modifica el retorno relativo de los activos domésticos:
> **Japón no necesita que su ahorro vuelva de golpe; le basta con que deje de salir.**

Cuando la deuda pública estadounidense ofrece cerca del 5% pero el coste de cobertura cambiaria del dólar cuesta varios puntos, el retorno neto cubierto para un inversor japonés pasa a ser inferior al de sus propios bonos soberanos domésticos. El mecanismo de ajuste no requiere una liquidación forzosa de carteras; basta con no reinvertir los vencimientos de deuda foránea y canalizar el nuevo ahorro hacia activos japoneses.

Eso puede reducir el incentivo marginal a adquirir duración exterior cubierta, pero el stock TIC no prueba ventas ni permite inferir una retirada automática del comprador japonés. La ficha mide esa hipótesis mediante flujos oficiales y separa el canal japonés del posible estrés estacional de la TGA, el repo y el cierre trimestral en Estados Unidos.

En Estados Unidos, la deuda bruta federal cruzó los **40 billones de dólares** el 18/08. El Tesoro anunció el 19/08 que duplicaría, como mínimo, las recompras de apoyo de liquidez en los tramos nominales de 10–20 y 20–30 años desde el 09/09. Es una señal de gestión de liquidez del tramo largo, no una reducción de deuda ni una operación de la Reserva Federal. Al 09/09, la TGA ha bajado a 843,705 B$ y las reservas ascienden a 3.036,508 B$; la fontanería no muestra tensión y el test causal posterior a los impuestos del 15/09 continúa en el futuro.

---


</details>

**Rectificación de redacción (19/09):** el Trigger D decía «operaciones de absorción de liquidez». Una repo SRF provee liquidez contra colateral. Solo se corrige la dirección del flujo; >20 B$, >2 días y ventana 25–30/09 se conservan. La alternativa p99 de C queda metodológicamente pendiente; no se inventa un denominador retrospectivo.

## Calibración humana — TASK_118, 19/09/2026

Luis acepta peso 5. Estado técnico anterior: peso 4 y contribución 19,2; nuevo valor 24,0. Diferencia por juicio de importancia, sin nuevo deterioro factual. Los restantes pesos acordados se recogen en [[VECTOR_00_Indice]].

<details>
<summary>Snapshot y evaluación W38 sustituidos el 27-sep; umbrales canónicos conservados</summary>

## 1. SNAPSHOT ACTUAL
- **Estado:** E0 — En observación intensificada
- **Nivel de presión:** ELEVADA (P4)
- **Dirección de tendencia:** ↑ Acelerando
- **Peso estructural:** 5 (Luis, TASK_118; 19/09)
- **Última actualización:** 2026-09-19 (precierre W38; corte 05:29 Europe/Madrid)
- **Contribución primaria:** 4 × 5 × 1,2 = **24,0**
- **Recalibración humana:** 19/09, posterior al corte factual 05:29; cambia solo el peso, no la evidencia, P ni tendencia.
- **Vector primario:** [[VECTOR_01_Arquitectura_monetaria_global]]
- **Vectores secundarios:** [[VECTOR_04_Reconfiguracion_del_comercio_global]], [[VECTOR_02_Energia_y_nodos_geoeconomicos]]
- **Alcance:** evidencia publicada antes de 2026-09-19 05:29 Europe/Madrid; no cubre el domingo 20/09.

- BoJ: decisión del 18/09 de elevar el objetivo a **1,25%**, efectiva el **24/09**; al corte sigue en torno al **1,00%**. [BoJ, decisión y anexo](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf).
- Fed: alza de 25 pb a **3,75–4,00%**; IORB **3,90%** desde el 17/09. [FOMC](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260916a.htm) y [implementación](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260916a1.htm).
- H.4.1 publicado el 17/09, observación puntual del 16/09: TGA **991,708 B$**, reservas **2.921,536 B$**. No son promedios semanales. [Fed H.4.1](https://www.federalreserve.gov/releases/h41/Current/).
- DTS: caja al cierre del 14/09 **871,224 B$**, 15/09 **991,557 B$**, 16/09 **991,708 B$**, 17/09 **972,675 B$**. El 15/09 entran **51,579 B$** de impuestos corporativos; la emisión neta de deuda aporta también **43,261 B$**. [DTS caja](https://api.fiscaldata.treasury.gov/services/api/fiscal_service/v1/accounting/dts/operating_cash_balance?filter=record_date:gte:2026-09-14,record_date:lte:2026-09-17&page[size]=100) y [DTS flujos](https://api.fiscaldata.treasury.gov/services/api/fiscal_service/v1/accounting/dts/deposits_withdrawals_operating_cash?filter=record_date:eq:2026-09-15&page[size]=500).
- SOFR–IORB: **−3, −1, −3 y −5 pb** para 14–17/09. SRF: **0, 102, 254, 2 y 1 M$** diarios, 14–18/09, sumando las dos operaciones de cada día. SOFR del 18/09 todavía no disponible al corte. [SOFR](https://markets.newyorkfed.org/api/rates/secured/sofr/search.json?startDate=2026-09-12&endDate=2026-09-18&type=rate) y [repo/SRF](https://markets.newyorkfed.org/api/rp/results/search.json?startDate=2026-09-14&endDate=2026-09-18&operationTypes=Repo).
- TIC julio publicado el 16/09: stock japonés **1.103,9 B$** frente a **1.116,7 B$** en junio; variación **−12,8 B$**, que no equivale a ventas netas. Entrada TIC agregada **83,7 B$**; no es flujo japonés. [TIC julio](https://home.treasury.gov/news/press-releases/sb0631/) y [tenencias por país](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table5.html).
- MOF publicado el 17/09: compras netas japonesas de deuda exterior a largo plazo de **1.082,9 miles de millones de yenes**, semana 06–12/09; la anterior queda revisada a **111,4**, frente a 111,9 en W37. Agosto mensual sigue en **−143,0**. [MOF semanal](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/week.pdf) y [MOF mensual](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/monthEng.pdf).

**Decisión técnica:** La tendencia pasa de → a ↑ por el aumento observado de TGA y la caída de reservas dentro de la ventana fiscal, junto a la nueva decisión japonesa. La clase sigue E0 porque B está parcialmente acreditado y A/C/D no alcanzan activación completa. La señal no equivale a desarme de carry ni a crisis repo.

Matriz de evidencia, fuentes y límites: [[ACTUALIZACION_SEMANAL_231_2026_09_20]].


## 2. CONDICIONES DE ACTIVACIÓN (TRIGGERS)

- **Trigger A (Flujos de Ahorro Japonés y Deuda Exterior):** El diferencial de rentabilidad entre el JGB a 30 años y el U.S. Treasury a 30 años cubierto a yenes se mantiene favorable al bono japonés durante más de 15 días hábiles consecutivos, acompañado por dos meses consecutivos de compras netas negativas (o desinversión/no reinversión) de bonos extranjeros por parte de inversores institucionales japoneses según datos del Ministerio de Finanzas de Japón o el Treasury International Capital (TIC). **Estado al corte: NO ACREDITADO COMPLETO. Falta una serie de >15 días hábiles del diferencial 30Y cubierto y dos meses consecutivos de flujo institucional comparable. El descenso de stock TIC no suple el flujo; MOF semanal positivo es contraevidencia de retirada inmediata, no refuta por sí solo dos meses negativos.**
- **Trigger B (Drenaje Fiscal TGA y Reservas):** Los pagos de impuestos corporativos del 15 de septiembre elevan la Treasury General Account (TGA) por encima de 900 B$, provocando un drenaje de reservas bancarias agregadas por debajo de los 3,1 billones de dólares en la misma quincena. **Estado al corte: PARCIAL. Umbrales cuantitativos simultáneos y ventana temporal cumplidos al 16/09. Los impuestos contribuyen a la caja, pero también la financiación; las reservas ya estaban bajo 3,1 T$ antes del pago. No se acredita íntegramente la causalidad y el cruce exigidos por la redacción canónica. No se rebaja el umbral ni se declara inactivo.**
- **Trigger C (Stress en Mercados Monetarios / SOFR):** El tipo de interés garantizado a un día (SOFR) cotiza por encima del tipo de interés sobre saldos de reservas (IORB) en más de 8 puntos básicos durante 3 días hábiles consecutivos, o la dispersión del percentil 99 en repo general collateral supera los 25 bps. **Estado al corte: RAMA SOFR NO ACTIVADA en los cuatro días publicados. La alternativa de dispersión del percentil 99 de repo GC no es plenamente evaluable: el protocolo no define contra qué referencia medirla. El rango p99–mediana de SOFR es solo diagnóstico y no se sustituye por GC.**
- **Trigger D (Uso de Facilidad de Respaldo SRF):** La Standing Repo Facility (SRF) de la Reserva Federal registra operaciones de provisión de liquidez superiores a 20 B$ diarios durante más de dos días consecutivos alrededor del cierre de trimestre (25–30 de septiembre). **Estado al corte: VENTANA PENDIENTE (25–30/09). Fuera de ella, el máximo diario observado de 254 M$ no cruza 20 B$. Se corrige «absorción» por «provisión» de liquidez, conservando importe y duración.**

---

</details>

</details>
