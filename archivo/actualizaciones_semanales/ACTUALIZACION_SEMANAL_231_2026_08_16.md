# ACTUALIZACIÓN SEMANAL — SISTEMA 231 (W33, revisada el 17/08/2026)

> **Corte factual original:** 16/08/2026  
> **Auditoría correctiva:** 17/08/2026  
> **Estado:** validada como nueva línea base canónica

## 1. Resultado ejecutivo

La revisión forense corrige una contaminación temporal: varias cifras de julio de 2024 se habían incorporado como si fueran de julio de 2026. La base oficial correcta es:

- IPC de EE. UU. de julio de 2026: **3,4% general y 2,5% subyacente** interanual.
- Nóminas no agrícolas de julio: **−23.000**; desempleo **4,1%**.
- Sahm Rule en tiempo real de julio: **−0,03**, no activada.
- ISM manufacturero de julio: **55,6**, expansión por séptimo mes consecutivo.
- El BoJ puso fin al tipo negativo y al control de curva en marzo de **2024**. En julio de 2026 mantuvo el tipo alrededor del 1,0%; no lo elevó ese día.
- La lista vigente del Joint War Committee es **JWLA-034**, revisada en julio de 2026.
- La Orden DOE **202-26-39**, emitida el 14/08 y vigente del 17/08 al 14/11, prolonga la disponibilidad obligatoria de J.H. Campbell y acelera la señal física de Grid sin activar su trigger específico de CPDs.
- TSMC publicó ingresos de julio de **467.580 M NT$**, +44,7% interanual; la presión de demanda aumenta, pero no se activa ningún trigger CoWoS.

Estas correcciones invalidan la anterior inferencia de recesión inmediata y la narrativa de desarme acelerado del carry trade. El sistema mantiene riesgos reales, pero vuelve a separar hechos, hipótesis y triggers.

## 2. Decisiones sobre eventos

| Evento | Decisión | Estado resultante | Razón |
|:---|:---|:---|:---|
| [[Evento_E0_2026_08_16_Japon_Carry_Trade_y_Liquidez_Septiembre]] | Corregir y mantener | E0 · P4 · → | Normalización japonesa verificable; repatriación y estrés repo aún no demostrados. |
| [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb]] | Corregir y mantener | E1 · P4 · → | JWLA-034 vigente; no aparece nueva evidencia primaria que active A–D. |
| [[Evento_E0_2026_07_08_Grid_Stress_IA]] | Actualizar y mantener | E0 · P4 · ↑ | DOE 202-26-39 prolonga la intervención hasta noviembre; no existe todavía obligación específica a CPDs que cruce trigger. |
| [[Evento_E0_2026_07_24_US_Tariff_Stack]] | Mantener | E0 · P4 · ↑ | Section 338 sigue pendiente del hito binario del 19/08. |
| [[Evento_E0_2026_CoWoS_Capacity]] | Reconciliar y mantener | E0 · P4 · → | Los ingresos de TSMC de julio confirman demanda, no ruptura; NVIDIA el 26/08 y TSMC el 10/09 son los siguientes cortes. |
| [[231_Eventos_Cerrados/Evento_E0_2026_05_20_Taiwan_Riesgo_Estrecho]] | Cerrar | Cerrado | Terminó la ventana Han Kuang; vigilancia transferida a V06. |
| [[231_Eventos_Cerrados/Evento_E0_2026_06_07_GNSS_Spoofing_Maritimo]] | Cerrar | Cerrado | Fricción persistente de fondo; sensor transferido a V02. |
| [[231_Eventos_Cerrados/Evento_E0_2026_06_15_Spain_Pensiones_Renta]] | Cerrar | Cerrado | Tema estructural sin evento acotado; transferido a V05 y TESIS_03. |

## 3. Presión reproducible

Se elimina el IPV anterior porque combinaba eventos y multiplicadores sin una regla de deduplicación reproducible. La métrica operativa pasa a ser:

**Contribución primaria por evento = nivel de presión × peso estructural × tendencia**

Escala: P4=4; ↑=1,2; →=1,0; ↓=0,8. Sólo cuenta el vector primario y cada ficha activa una sola vez.

| Vector | Eventos primarios activos | Cálculo | Carga bruta | Lectura |
|:---|---:|:---|---:|:---|
| V01 | 1 | Japón: 4×4×1,0 | 16,0 | Elevada, estable |
| V02 | 2 | Lloyd 4×4×1,0 + Grid 4×4×1,2 | 35,2 | Crítica por acumulación, acelerando |
| V03 | 1 | CoWoS 4×4×1,0 | 16,0 | Elevada, estable |
| V04 | 1 | Tariff Stack 4×4×1,2 | 19,2 | Crítica, acelerando |
| V05 | 0 | Sin evento activo primario | 0,0 | Presión estructural monitorizada en el vector |
| V06 | 0 | Sin evento activo primario | 0,0 | Presión estructural monitorizada en el vector |

La carga es una suma de sensores, no una probabilidad ni una magnitud económica comparable entre periodos si cambia el número de fichas. Por eso se publican juntos el número de eventos y el cálculo.

## 4. Radar

[[Radar_Eventos_2026_08_r1]] queda ampliado con **29 hitos únicos** entre el 17/08 y el 30/09. A la base reparada se añaden TIC de junio, producción industrial de la eurozona, subasta JGB 30Y, flujos mensuales japoneses, ventas de TSMC, ventana de liquidez estadounidense y semana de alto nivel de la Asamblea General de la ONU. La fila aislada de Eddystone se convierte en una secuencia consolidada de vencimientos DOE 202(c). Cada fila conserva fecha, ID y fuente primaria; no se fuerza una cuota artificial por vector.

Próximos cortes:

- 17/08: FERC y TIC de junio.
- 19/08: actas FOMC, producción industrial de la eurozona, Section 338 Canadá e inicio de la secuencia DOE 202(c).
- 26/08: PCE y NVIDIA.
- 27–29/08: Jackson Hole.
- 01–18/09: ISM, subasta JGB 30Y, NFP, OPEP+, flujos japoneses, EIA, TSMC, BCE, CPI, ventana de liquidez, FOMC, BoE y BoJ.
- 22–28/09: semana de alto nivel de la Asamblea General de la ONU.

## 5. Revisión de tesis

| Tesis | Decisión | Nota |
|:---|:---|:---|
| [[TESIS_01_Dominancia_Fiscal]] | Mantener con corrección | Se retira el apoyo falso de CPI/Sahm; soporte moderado. |
| [[TESIS_02_Frictionless_Stabilization]] | Mantener | Tariff Stack sigue siendo sensor central; resultado del 19/08 pendiente. |
| [[TESIS_03_Captura_de_Renta]] | Mantener | Pensiones pasa a evidencia estructural, no a evento activo. |
| [[TESIS_04_Multipolaridad_Logistica]] | Mantener | Lloyd continúa activo; GNSS se trata como observatorio. |
| [[TESIS_05_Tokenizacion_del_Colateral]] | Mantener | Japón y septiembre son sensores, no evidencia de ruptura. |
| [[TESIS_06_IA_como_silicio_y_energia]] | Mantener | Grid y CoWoS siguen activos; FERC/NVIDIA son próximos puntos de control. |

## 6. Fuentes de la corrección

- [BLS — CPI](https://www.bls.gov/news.release/cpi.nr0.htm)
- [BLS — Employment Situation](https://www.bls.gov/news.release/empsit.nr0.htm)
- [FRED — Sahm Rule](https://fred.stlouisfed.org/series/SAHMREALTIME)
- [ISM — julio de 2026](https://www.ismworld.org/supply-management-news-and-reports/reports/ism-pmi-reports/pmi/july/)
- [BoJ — marzo de 2024](https://www.boj.or.jp/en/mopo/mpmdeci/state_2024/k240319a.htm)
- [BoJ — julio de 2026](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260731a.pdf)
- [MOF Japón — subasta JGB 30Y](https://www.mof.go.jp/english/policy/jgbs/auction/calendar/eresul/eresul20260806.htm)
- [LMA — Joint War Committee](https://lmalloyds.com/committee/joint-war-committee/)
- [DOE — órdenes 202(c) de 2026 y Orden 202-26-39](https://www.energy.gov/ceser/2026-doe-202c-orders)
- [Tesoro de EE. UU. — calendario TIC](https://home.treasury.gov/data/treasury-international-capital-tic-system/release-dates-of-tic-data)
- [Eurostat — producción industrial](https://ec.europa.eu/eurostat/en/web/products-euro-indicators/w/4-15072026-ap)
- [MOF Japón — flujos internacionales](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm)
- [TSMC — ingresos mensuales y calendario](https://investor.tsmc.com/english/financial-calendar)
- [ONU — 81.ª Asamblea General](https://www.un.org/en/ga/81/meetings/)

## 7. Regla canónica resultante

**FUENTES/HECHOS → VECTORES → RADAR → PROPUESTA DE EVENTOS → EVENTOS VALIDADOS → TESIS → SUPERFICIES Y LOG**

El corpus propio puede aportar hipótesis y preguntas, pero no sustituye la evidencia primaria.
