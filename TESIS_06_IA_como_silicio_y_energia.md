---
tipo: tesis_estructural
id: TESIS_06
estado: vigente
soporte: alto
ultima_actualizacion: 2026-09-19
corte_factual_actual: "2026-09-19 05:29 Europe/Madrid"
corte_factual_previo: "2026-09-12 21:21 Europe/Madrid"
alcance_actualizacion: "Precierre W38 TASK_116; revisión técnica autorizada, sin validación humana posterior implícita"
vector_dominante: "[[VECTOR_03_Semiconductores_y_soberania_tecnologica]]"
---

# 💡 TESIS_06: IA como silicio y energía

## 1. Definición

El despliegue de inteligencia artificial depende de una cadena industrial física: aceleradores, memoria HBM, empaquetado avanzado, litografía, redes, generación eléctrica, refrigeración y permisos. La capacidad algorítmica solo se convierte en capacidad económica cuando esa infraestructura puede fabricarse, conectarse y operar.

La tesis identifica una **restricción de cadena de conversión**: el cuello de botella puede desplazarse entre litografía, HBM, empaquetado, electricidad, red, refrigeración y permisos. No afirma que energía o CoWoS estén ya bloqueando de forma generalizada todo el despliegue de IA.

## 2. Restricción estructural asociada

- **Semiconductores:** concentración de fundición avanzada, litografía EUV y empaquetado.
- **Memoria:** disponibilidad de HBM y coordinación con plataformas de aceleradores.
- **Eléctrica:** generación firme, subestaciones, transmisión y tiempo de interconexión.
- **Térmica e hídrica:** disipación de calor, refrigeración y permisos ambientales.
- **Industrial:** plazos de construcción, equipamiento y mano de obra especializada.

## 3. Manifestaciones observables

- **TSMC:** ingresos Q2 de 40,20 B$, guía Q3 de 44,6–45,8 B$ e ingresos de julio de 467.580 M NT$ (+44,7% interanual), sin retraso oficial de AP7 que active el evento CoWoS.
- **ASML:** ventas Q2 de 9,3 B€ y beneficio neto de 2,9 B€, señal de inversión sostenida en capacidad litográfica.
- **Micron:** 41,456 B$ de ingresos anuales, HBM4 en producción de alto volumen y HBM4E prevista para 2027.
- **NVIDIA:** Q2 FY27 alcanzó 96,2 B$ de ingresos, 89,0 B$ en Data Center, margen bruto no-GAAP cercano al 75% y guía de 108 B$ para Q3. Rubin debería representar cerca del 20% del ingreso de Data Center de Q3; la dirección sigue calificando la oferta como cuello de botella hasta FY28.
- **Cómputo local:** Apple introduce M6 de 2 nm en Mac mini y ofrece hasta 512 GB de memoria unificada con M5 Ultra en Mac Studio. Es una rama complementaria para inferencia y ajuste local, con coste de energía y amortización aunque no exista precio externo medido por token.
- **Escala industrial:** Unitree asigna 4.200 M de yuanes a inversión tras su salida a bolsa y Alibaba compromete 80.000 M HK$ a IA. La señal confirma movilización de capital físico chino, pero no un bypass de litografía ni un alivio del cuello de botella de HBM/CoWoS.
- **Red:** FERC abrió procesos sobre integración y tarifas de grandes cargas en seis RTO/ISO y el 14/08 concedió 90 días de suspensión a los seis expedientes. Es continuidad regulatoria, no una reforma tarifaria material.
- **Emergencia física:** DOE 202-26-39 mantiene J.H. Campbell del 17/08 al 14/11, la 202-26-25A extiende Wagner del 20/08 al 17/11 y la 202-26-40 mantiene Eddystone del 23/08 al 20/11. La última cita en su contexto el crecimiento de demanda por centros de datos e IA, pero ninguna orden demuestra una emergencia causada exclusivamente por CPDs ni impone la obligación específica de cuatro horas definida por el evento.

## 4. Tensiones internas

- **Demanda frente a capacidad:** ingresos y CapEx altos pueden reflejar expansión suficiente, no escasez.
- **Eficiencia:** mejoras algorítmicas, inferencia local y nuevos diseños pueden reducir energía por unidad de servicio.
- **Causalidad eléctrica:** el estrés de red estival no puede atribuirse automáticamente a centros de datos.
- **Sustitución tecnológica:** nodos maduros, ASICs y técnicas de empaquetado pueden reducir dependencia de un único chokepoint.

## 5. Relación con VECTORES y EVENTOS

- **Vector dominante:** [[VECTOR_03_Semiconductores_y_soberania_tecnologica]].
- **Vector energético:** [[VECTOR_02_Energia_y_nodos_geoeconomicos]].
- **Vector industrial:** [[VECTOR_05_Transformacion_industrial_y_demografia]].
- **Sensores activos:** [[Evento_E0_2026_CoWoS_Capacity]] y [[Evento_E0_2026_07_08_Grid_Stress_IA]].
- **Próximos sensores verificados:** ventas mensuales de TSMC el 08/10 y 10/11 en [[Radar_Eventos_2026_09]]; FERC/DOE se siguen mediante el observatorio y Grid, con consulta del instrumento específico antes de actuar.

## 6. Criterios de validación o refutación

**Refuerzan la tesis:**
- Retrasos oficiales de fundición, HBM o empaquetado que reduzcan entregas físicas.
- Recortes o aplazamientos de centros de datos por falta de conexión, generación, agua o permisos.
- Aumento persistente del peso de infraestructura y energía en CapEx y costes operativos.

**La debilitan o refutan:**
- Caída generalizada de lead times y utilización por sobrecapacidad.
- Reducciones de órdenes de magnitud en energía y hardware por unidad de inferencia.
- Despliegue masivo sin restricciones de interconexión, fabricación o refrigeración.
- Descenso sostenido del coste total por unidad de servicio de IA y mejoras de eficiencia energética que, junto con la expansión de capacidad, eviten congestión, aplazamientos y aumento de lead times a lo largo de la cadena.

## 7. Calibración actual — 19/09/2026 (precierre W38)

- **Soporte:** Alto; vigente.
- **A favor:** La nueva orden DOE acredita restricciones generales de energía; TSMC y NVIDIA sostienen como antecedentes la escala material de ingresos e inversión.
- **Contraevidencia y límites:** No se demuestra que la orden obligue a CPDs >50 MW durante ≥4 horas, ni deterioro nuevo de AP7/yields/entregas. La expansión de oferta puede aliviar la restricción.
- **Ambigüedad causal:** Ingresos son demanda agregada; una guía es prospectiva; tensión de red no demuestra causalidad exclusiva de IA ni saturación terminal.
- **Próxima falsación:** Contrastar Micron 30/09 y métricas directas de AP7, lead times y restricciones CPD. Capacidad suficiente, plazos menores y menores costes de despliegue debilitarían el cuello de botella.
- **Juicio técnico:** Se mantiene alto en su formulación física, sin nueva activación de Grid o CoWoS.

Fuentes y alcance: [[ACTUALIZACION_SEMANAL_231_2026_09_20]]. [doe](https://www.energy.gov/documents/doe-order-no-202-26-45) · [tsmc](https://pr.cld.tsmc.com/english/news/3340) · [nv](https://investor.nvidia.com/news/press-release-details/2026/NVIDIA-Announces-Financial-Results-for-Second-Quarter-Fiscal-2027/default.aspx) · [micron](https://investors.micron.com/news/press-release/2026/Micron-Technology-to-Report-Fiscal-Fourth-Quarter-Results-on-September-30-2026/default.aspx)

## 8. Fuentes de seguimiento

- [TSMC — resultados del segundo trimestre de 2026](https://investor.tsmc.com/english/quarterly-results/2026/q2)
- [ASML — resultados del segundo trimestre de 2026](https://live.euronext.com/en/products/equities/company-news/2026-07-15-asml-reports-eu93-billion-total-net-sales-and-eu29)
- [Micron — resultados fiscales de 2026](https://investors.micron.com/node/50671)
- [DOE — Order 202-26-35 para PJM](https://www.energy.gov/ceser/federal-power-act-section-202c-pjm-interconnection-llc-pjm-order-no-202-26-35)
- [DOE — Order 202-26-24 para PJM, vigente hasta el 22-ago-2026](https://www.energy.gov/ceser/federal-power-act-section-202c-pjm-interconnection-llc-pjm-order-no-202-26-24)
- [DOE — órdenes 202(c) de 2026 y Order 202-26-39](https://www.energy.gov/ceser/2026-doe-202c-orders)
- [TSMC — ingresos mensuales de 2026](https://investor.tsmc.com/english/monthly-revenue/2026)
- [FERC — integración de grandes cargas](https://www.ferc.gov/news-events/news/ferc-launches-aggressive-targeted-action-speed-large-load-integration)
- [DOE — extensión de Wagner mediante Orden 202-26-25A](https://www.energy.gov/articles/energy-secretary-acts-protect-mid-atlantic-grid)
- [FERC — PJM EL26-67, suspensión de 90 días](https://elibrary.ferc.gov/eLibrary/filelist?accession_number=20260814-3059)
- [NVIDIA — resultados de Q2 FY27, 26-ago-2026](https://investor.nvidia.com/news/press-release-details/2026/NVIDIA-Announces-Financial-Results-for-Second-Quarter-Fiscal-2027/default.aspx)
- [NVIDIA — transcripción oficial de resultados de Q2 FY27](https://investor.nvidia.com/files/content_files/TRANSCRIPT_-NVIDIA-Corp-NVDA-US-Q2-2027-Earnings-Call-26-August-2026-5_00-PM-ET.pdf)
- [NVIDIA — 10-Q de Q2 FY27](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000075/nvda-20260726.htm)
- [Apple — M6 de 2 nm en Mac mini](https://www.apple.com/newsroom/2026/08/apple-introduces-m6-and-m5-ultra-for-a-big-leap-in-performance-and-ai-compute/)
- [Apple — Mac Studio con M5 Ultra y hasta 512 GB](https://www.apple.com/newsroom/2026/08/apple-introduces-new-mac-studio-with-m5-max-and-m5-ultra/)
- [DOE — Orden 202-26-40 para Eddystone](https://www.energy.gov/documents/doe-order-no-202-26-40)
- [Shanghai Stock Exchange — salida a bolsa y plan de inversión de Unitree](https://english.sse.com.cn/news/newsrelease/voice/c/c_20260811_10828578.shtml)
- [Alibaba — inversión de 80.000 M HK$ en IA](https://home.alibabagroup.com/en-US/document-2028384807859257344)
- **Corpus propio incorporado:** [[50 Archivo/52 LinkedIn/2026_08_27_NVIDIA_ya_no_vende_chips]], [[50 Archivo/52 LinkedIn/2026_08_28_Apple_se_sube_al_tren_de_la_IA]] y [[50 Archivo/52 LinkedIn/2026_08_26_Unitree__Alibaba_con_Europa_como_espejo]].

## Rectificación y reconciliación — 06/09/2026 (TASK_090)

Grid y CoWoS permanecen E0 · P4 · →; la persistencia de inversión y cuellos de botella no se cuenta como aceleración nueva semanal. Anthropic anunció su presentación confidencial el **01/06/2026** ([comunicado](https://www.anthropic.com/news/confidential-draft-s1-sec)): antecedente corporativo, no hecho nuevo W36 ni salida a bolsa ya consumada. No es una medida de capacidad CoWoS. Soporte alto sin cambio. Los antecedentes estructurales conservan sus periodos; ninguna fecha de modificación sustituye la consulta de su fuente.

## Revisión W37 — 12/09/2026 (TASK_099, fase 5)

- **Estado / soporte:** vigente · alto; sin cambio de grado.
- **Refuerzo W37:** TSMC publica 514.806 M NT$ de ingresos en agosto (+53,3% interanual), confirmando la escala de demanda física. La Orden DOE 202-26-41 añade otro episodio temporal de intervención de fiabilidad en PJM.
- **Contraevidencia y límites:** la facturación no desglosa CoWoS, AP7, *yields*, entregas ni *lead times*; la orden DOE no atribuye causalidad exclusiva a centros de datos ni impone el *curtailment* definido por Grid. El Banco de Inglaterra identifica riesgo potencial de competencia por financiación, pero poca o ninguna evidencia actual de desplazamiento.
- **Juicio:** W37 refuerza la cadena silicio–red–capital, no la existencia de un bloqueo generalizado. CoWoS y Grid permanecen E0 · P4 · → y el soporte de TESIS_06 continúa alto, sin promoción adicional.

## Revisión W38 — TASK_116

Se mantiene alto en su formulación física, sin nueva activación de Grid o CoWoS. El soporte resulta de la revisión explícita de §7, no de una instrucción de conservarlo. Los grados históricos no se reinterpretan como nueva evidencia.

<details>
<summary>Calibración anterior sustituida</summary>

### Calibración anterior — 29/08/2026

- **Estado:** vigente.
- **Grado de soporte:** alto.
- **Evidencia favorable:** NVIDIA confirma escala y aceleración de demanda, Rubin eleva el mix y los compromisos de capacidad muestran contratación anticipada; Apple amplía la frontera de inferencia local; tres órdenes DOE prolongan generación firme y FERC mantiene abierto el proceso de grandes cargas.
- **Evidencia contradictoria:** ningún trigger CoWoS está activado; la oferta restringida no ha provocado retraso oficial AP7 ni incumplimiento de guidance. Las órdenes DOE no prueban causalidad exclusiva de CPDs y FERC ha diferido 90 días una respuesta sustantiva.
- **Cambio de esta revisión:** el soporte permanece alto y la tendencia de V03 pasa a ↑. Se rechazan dos simplificaciones del corpus: «HBM/CoWoS sin cuellos de botella» contradice la guía de NVIDIA y «token a coste marginal cero» sólo es válido como ausencia de tarifa cloud, no como coste económico total.


</details>
