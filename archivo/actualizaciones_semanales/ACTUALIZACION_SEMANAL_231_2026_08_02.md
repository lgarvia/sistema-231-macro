# Actualización semanal del Sistema 231 — 02/08/2026

## Resultado ejecutivo

Ejecución parcial del protocolo manual candidato v0.2. Se completaron la línea base factual, los vectores, el radar y una primera revisión factual de eventos, pero el ciclo no se considera validado hasta que Front Office apruebe la propuesta explícita de decisiones sobre altas, mantenimiento, archivo, fusión y escalada.

- **Eventos activos:** 7 (6 E0 + 1 E1).
- **Decisión validada — altas / archivos de eventos / fusiones / escaladas:** 0 / 0 / 0 / 0.
- **Cambio operativo:** [[Evento_E0_2026_07_08_Grid_Stress_IA]] pasa de tendencia estable a acelerando por la Orden DOE 202-26-37 para SPP.
- **Radar vigente:** [[Radar_Eventos_2026_08]], 26 hitos únicos entre el 3-ago y el 24-sep.
- **Radar anterior:** [[archivo/Radar_Eventos_2026_07_r4]], archivado; agosto queda como único radar activo.
- **Dominancia:** V02 continúa dominante; V04 permanece como segundo vector de tensión.

## 1. Recalibración de vectores

| Vector | Presión | Tendencia | Triggers | Decisión |
|:--- |:---:|:---:|:---:|:--- |
| [[VECTOR_01_Arquitectura_monetaria_global]] | 🟡 Moderada | ↑ | 0 completos / 0 parciales | Mantener. Fed, BoE y BoJ sostienen tipos con disensos alcistas; PCE persistente sin ruptura repo o de subastas. |
| [[VECTOR_02_Energia_y_nodos_geoeconomicos]] | 🔴 Crítica | ↑ | 1 completo / 2 parciales | Mantener dominancia. Nueva Orden 202-26-37 y 62 incidentes marítimos confirmados. |
| [[VECTOR_03_Semiconductores_y_soberania_tecnologica]] | 🟠 Elevada | ↑ | 0 completos / 2 parciales | Mantener. Meta y Amazon confirman inversión física y presión sobre caja; los umbrales de guidance y lead times no se completan. |
| [[VECTOR_04_Reconfiguracion_del_comercio_global]] | 🔴 Crítica | ↑ | 1 completo / 1 parcial | Mantener. Section 301 queda consolidada tras vencer el tránsito; Section 338 Canadá sigue pendiente. |
| [[VECTOR_05_Transformacion_industrial_y_demografia]] | 🟡 Moderada | → | 0 completos / 0 parciales | Mantener. No existe liquidación actuarial nueva; datos industriales de junio todavía pendientes. |
| [[VECTOR_06_Orden_geopolitico_y_esferas_de_influencia]] | 🟠 Elevada | ↑ | 0 completos / 1 parcial | Mantener. Han Kuang 42 amplía la ventana de vigilancia, sin bloqueo ni zona de exclusión. |

## 2. Radar resultante

El nuevo [[Radar_Eventos_2026_08]] retira siete hitos ya ejecutados, incorpora la expiración de DOE 202-26-37 y corrige Han Kuang 42 a la ventana oficial del 5 al 14-ago. La cobertura final es V01 9, V02 5, V03 1, V04 4, V05 4 y V06 3.

Puntos de control principales:

1. **3–7 ago:** DOE SPP, Quarterly Refunding, Han Kuang 42 y NFP.
2. **11–12 ago:** EIA STEO e IPC estadounidense.
3. **17–22 ago:** FERC grandes cargas, Section 338 Canadá y expiración Eddystone.
4. **26–29 ago:** PCE, NVIDIA y Jackson Hole.

La reunión OPEP+ del 2-ago queda como proceso abierto: no se anticipa resultado sin comunicado oficial.

## 3. Decisión sobre eventos activos

| Evento | Decisión 02/08/2026 |
|:--- |:--- |
| [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb]] | Mantener E1 / P4 / ↑. El LAVINE es LPG, no LNG; Trigger B inactivo. |
| [[Evento_E0_2026_07_08_Grid_Stress_IA]] | Mantener E0 / P4; elevar → a ↑. La orden SPP no impone obligación específica a CPDs. |
| [[Evento_E0_2026_06_07_GNSS_Spoofing_Maritimo]] | Mantener E0 / P4 / →. Sin accidente o restricción operativa que complete trigger. |
| [[Evento_E0_2026_CoWoS_Capacity]] | Mantener E0 / P4 / ↑. CAPEX acelera, sin retraso AP7, deterioro de yields, recorte o sobrecapacidad. |
| [[Evento_E0_2026_05_20_Taiwan_Riesgo_Estrecho]] | Mantener E0 / P4 / ↑. Ventana Han Kuang, sin bloqueo o exclusión. |
| [[Evento_E0_2026_06_15_Spain_Pensiones_Renta]] | Mantener E0 / P3 / →. Trigger actuarial inactivo. |
| [[Evento_E0_2026_07_24_US_Tariff_Stack]] | Mantener E0 / P4 / ↑. Tránsito vencido; transmisión material todavía pendiente. |

## 4. Validación del procedimiento

- **Cierre operativo:** actualización semanal cerrada por Front Office el 02/08/2026.
- **Validación del método:** este ciclo no computa como 1 de 2 de la v0.2, porque las exigencias formales sobre corpus propio y TESIS se añadieron una vez iniciada la ejecución.
- **Registro canónico:** [[Prompt_Actualizacion_Eventos]].
- **Decisión de eventos:** [[PROPUESTA_DECISION_EVENTOS_2026_08_02]] validada íntegramente y aplicada.
- **Siguiente ciclo:** aplicar la secuencia v0.2 completa desde el inicio, incluyendo corpus propio y TESIS_01–06.
- **Siguiente ejecución:** repetir la secuencia v0.2 la próxima semana, sin volver a diseñarla.
- **Condición de promoción:** si la repetición es satisfactoria, crear la skill `actualizacion-sistema-231`, incorporarla al índice de skills y añadirla a la liturgia semanal.

## 5. Fuentes primarias nuevas decisivas

- [Reserva Federal — FOMC del 29-jul](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260729a.htm)
- [BEA — PIB de Q2](https://www.bea.gov/news/2026/gdp-advance-estimate-2nd-quarter-2026)
- [BEA — Personal Income and Outlays de junio](https://www.bea.gov/news/2026/personal-income-and-outlays-june-2026)
- [Banco de Inglaterra — decisión de julio](https://www.bankofengland.co.uk/monetary-policy-summary-and-minutes/2026/july-2026)
- [Banco de Japón — decisión del 31-jul](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260731a.pdf)
- [DOE — órdenes 202(c) de 2026](https://www.energy.gov/ceser/2026-doe-202c-orders)
- [OMI — incidentes confirmados en Oriente Medio](https://www.imo.org/en/mediacentre/hottopics/pages/middle-east-highlighted-incidents.aspx)
- [Meta — resultados de Q2](https://investor.atmeta.com/investor-news/press-release-details/2026/Meta-Reports-Second-Quarter-2026-Results/)
- [Amazon — resultados de Q2](https://ir.aboutamazon.com/news-release/news-release-details/2026/Amazon-com-Announces-Second-Quarter-Results/)
- [Taiwán MND — planificación de Han Kuang 42](https://www.mnd.gov.tw/news/pressrelease/87171)
