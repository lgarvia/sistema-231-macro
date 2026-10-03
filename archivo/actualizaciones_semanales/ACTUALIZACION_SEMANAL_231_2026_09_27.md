---
tipo: actualizacion_semanal_231
semana: 2026-W39
fecha_nominal: 2026-09-27
estado: historico
modalidad: precierre
corte_factual: "2026-09-26 20:48 Europe/Madrid"
corte_previo: "2026-09-19 05:29 Europe/Madrid"
aplicacion: 2026-09-27
tarea: TASK_148
publicacion: github_main
---

# Sistema 231 — precierre W39

> Histórico sustituido por [[ACTUALIZACION_SEMANAL_231_2026_10_04]] el 03-oct. Corte y cifras W39 preservados.

**11 eventos activos (9 E0 / 2 E1), todos calibrados; carga primaria total 144,8.**

La revisión queda aplicada tras las decisiones de Luis. Se incorporan Francia, gas europeo y chips chinos; C22 financiación de CAPEX IA queda en V01 como observatorio. La actualización cubre evidencia publicada desde el corte anterior19-sep05:29 hasta26-sep20:48 Europe/Madrid, incluidos antecedentes recuperados identificados como tales. Las consultas27-sep no amplían el corte. No cubre el domingo27 completo.

## 1. Decisiones humanas y aplicación

| Paso | Propuesta presentada | Decisión de Luis | Aplicación |
|:---|:---|:---|:---|
| A | Pesos Japón5/Grid4/CoWoS3/Lloyd4/Tariff4/Xi4/midterms4/Unitree3 | «Valido los pesos» | Ocho pesos aplicados |
| B | Menú C1–C33: mantener8; altas C10 Francia,C13 gas,C33 chips; C22 observatorio; restantes integraciones/aplazamientos visibles | Francia y después «Dale con el resto de las autorizaciones» / «Abre todos los eventos propuestos» | Tres altas, ocho mantenidos; no33 altas ni cierres nuevos |
| Francia | P3/peso4/↑, carga14,4 | Aprobación tras propuesta y autorización general | Aplicada |
| Cinco calibraciones | Gas3/4/→; chips2/3/→; Xi2/4/→; midterms2/4/→; Unitree2/3/→ | Tras pedir ajustes, confirma «Perfecto todo. ¿Siguiente paso?» sin cifras alternativas | Aceptadas sin cambios; no pendiente humano |

Las decisiones de Luis son inventario/pesos/calibración. La evaluación de fuentes, cláusulas y soportes es trabajo técnico del agente. Se conserva la formulación de «Tesis (Luis)» en las fichas. La trazabilidad íntegra de propuestas y respuestas está en COMM del vault privado.

## 2. Inventario y carga reproducible

| Evento | Clase | P | Peso | Tendencia | Factor | Vector primario | Carga |
|:---|:---:|---:|---:|:---:|---:|:---:|---:|
| [[Evento_E0_2026_08_16_Japon_Carry_Trade_y_Liquidez_Septiembre\|Japón / liquidez]] | E0 | 4 | 5 | ↑ | 1,2 | V01 | 24,0 |
| [[Evento_E0_2026_07_08_Grid_Stress_IA\|Grid Stress IA]] | E0 | 4 | 4 | → | 1,0 | V02 | 16,0 |
| [[Evento_E0_2026_CoWoS_Capacity\|CoWoS]] | E0 | 4 | 3 | → | 1,0 | V03 | 12,0 |
| [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb\|Lloyd’s / riesgo marítimo]] | E1 | 4 | 4 | ↑ | 1,2 | V02 | 19,2 |
| [[Evento_E1_2026_07_24_US_Tariff_Stack\|US Tariff Stack]] | E1 | 4 | 4 | ↑ | 1,2 | V04 | 19,2 |
| [[Evento_E0_2026_09_19_Visita_Xi_EEUU\|Xi–EE. UU.]] | E0 | 2 | 4 | → | 1,0 | V06 | 8,0 |
| [[Evento_E0_2026_11_03_Midterms_EEUU\|Midterms]] | E0 | 2 | 4 | → | 1,0 | V06 | 8,0 |
| [[Evento_E0_2026_09_19_Robotica_Unitree\|Robótica / Unitree]] | E0 | 2 | 3 | → | 1,0 | V05 | 6,0 |
| [[Evento_E0_2026_09_26_Deuda_Francesa_y_Fragmentacion_Europea\|Deuda francesa]] | E0 | 3 | 4 | ↑ | 1,2 | V01 | 14,4 |
| [[Evento_E0_2026_09_26_Gas_Europeo_Invierno\|Gas europeo / invierno]] | E0 | 3 | 4 | → | 1,0 | V02 | 12,0 |
| [[Evento_E0_2026_09_26_Chips_Chinos_Alibaba\|Chips chinos / Alibaba]] | E0 | 2 | 3 | → | 1,0 | V03 | 6,0 |

La diferencia frente al subtotal 90,4 del piloto es +54,4: +32,4 por tres altas y +22,0 por calibrar Xi, midterms y Unitree, ya admitidos. No es una variación semanal homogénea ni demuestra empeoramiento de 54,4 puntos. Las cinco fichas base conservan P/peso/tendencia y suman 90,4. La carga es ordinal, no probabilidad ni pérdida esperada; solo se imputa una vez por vector primario.

| Vector | Presión / tendencia conservadas | Carga primaria |
|:---|:---|---:|
| [[VECTOR_01_Arquitectura_monetaria_global]] | 🟠 Elevada · ↑ | 38,4 |
| [[VECTOR_02_Energia_y_nodos_geoeconomicos]] | 🔴 Crítica · ↑ | 47,2 |
| [[VECTOR_03_Semiconductores_y_soberania_tecnologica]] | 🟠 Elevada · → | 18,0 |
| [[VECTOR_04_Reconfiguracion_del_comercio_global]] | 🔴 Crítica · ↑ | 19,2 |
| [[VECTOR_05_Transformacion_industrial_y_demografia]] | 🟡 Moderada · → | 6,0 |
| [[VECTOR_06_Orden_geopolitico_y_esferas_de_influencia]] | 🟡 Moderada · → | 16,0 |

P3 gas responde a vulnerabilidad física; P2 chips/Xi/midterms/Unitree a seguimientos con transmisión económica por demostrar. → evita presumir aceleración sin serie comparable. Francia P3/↑ observa tensión soberana. Clases E0 prospectivas y E1 persistentes son decisiones distintas del valor P. No existen reclasificaciones automáticas por una carga elevada.

## 3. Evidencia y auditoría de eventos

### Japón / liquidez

BoJ: objetivo 1,25% vigente desde 24-sep, conforme a la decisión publicada el 18-sep. H.4.1 publicado 24-sep: al 23-sep TGA **947.317 M$** y reservas **2.969.922 M$**, frente a 991.708 y 2.921.536 M$ al 16-sep: −44.391 y +48.386 M$. La media semanal de reservas, 2.930.193 M$, cae 83.601 M$: distinguir saldo puntual de promedio. La recuperación puntual es contraevidencia de drenaje continuo.

SOFR 18/21/22/23/24-sep: **3,85/3,85/3,87/3,87/3,88%** frente a IORB 3,90% (−5/−5/−3/−3/−2 pb). El SOFR del 25-sep no estaba publicado al corte; su publicación corresponde al 28-sep. No se recuperó la serie diaria SRF reciente: no se imputa cero. MOF conserva como último dato recuperado +1.082,9 miles de millones de yenes, semana 06–12-sep. Su calendario fija para **1-oct** las semanas 13–19 y 20–26-sep; el retraso no prueba retirada de capital. Aún falta la serie del diferencial 30Y cubierto.

Fuentes consultadas 26–27-sep, publicaciones dentro del corte: [BoJ 18-sep](https://www.boj.or.jp/en/mopo/mpmdeci/mpr_2026/k260918a.pdf), [H.4.1 24-sep](https://www.federalreserve.gov/releases/h41/current/), [SOFR](https://fred.stlouisfed.org/series/SOFR), [IORB](https://fred.stlouisfed.org/series/IORB), [MOF calendario](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/schedule.htm). Se conserva ↑ aprobado: describe presión acumulada; no una nueva aceleración probada por esta semana.

| Cláusula | Evaluación al corte |
|:---|:---|
| A | NO ACREDITADO COMPLETO: faltan >15 días hábiles de diferencial 30Y cubierto favorable y dos meses consecutivos de flujos institucionales comparables. MOF publicará dos semanas el 1-oct; stock TIC no sustituye flujo. |
| B | PARCIAL: TGA >900 B$ y reservas <3,1 T$ observados; la causalidad exclusiva y el cruce por impuestos no están acreditados, pues ya existía la precondición y contribuye financiación. Recuperación puntual de reservas al 23-sep. |
| C | RAMA SOFR NO ACTIVADA con evidencia publicada: diferencias −5/−5/−3/−3/−2 pb, no >+8 durante tres días. La rama GC p99 carece de referencia canónica inequívoca y de serie comparable; no verificable. |
| D | PERIODO INCOMPLETO: ventana 25–30-sep en curso. Serie SRF diaria reciente no recuperada; no se acredita >20 B$ por más de dos días ni se presume cero. |

### Grid Stress IA

DOE: las órdenes **202-26-46 (Schahfer 17/18, MISO)** y **47 (Culley 2, MISO)** se emitieron el 18-sep y rigen 20-sep–18-dic. La **48 (Duke)** rigió 18–21-sep y contempla respaldo antes/durante EEA3; autorización no acredita despacho efectivo ni obligación CPD >50 MW durante ≥4 horas. La **49 (Craig 1, SPP)** se publicó 25-sep y empieza **27-sep**, todavía futura al corte.

Loudoun: decisión de 15-sep para considerar una resolución el **20-oct**, noticia publicada 17-sep y actualizada 24-sep. La pausa legislativa propuesta no es una moratoria energética ya adoptada ni afecta automáticamente solicitudes administrativas. La Comisión Europea propuso el 21-sep un sistema de clasificación de centros de datos >500 kW sujeto a control institucional; no es sanción por WUE sectorial >0,5 L/kWh.

Fuentes consultadas 27-sep: [DOE46](https://www.energy.gov/documents/doe-order-no-202-26-46), [DOE47](https://www.energy.gov/documents/doe-order-no-202-26-47), [DOE48](https://www.energy.gov/documents/doe-order-no-202-26-48), [DOE49](https://www.energy.gov/documents/doe-order-no-202-26-49), [Loudoun](https://www.loudoun.gov/m/newsflash/home/detail/10874), [Comisión, 21-sep](https://commission.europa.eu/news-and-media/news/making-data-centres-energy-efficient-thanks-new-eu-rating-system-2026-09-21_en). Se conserva P4/→: restricción general persistente, sin acreditar el impedimento específico exigido por A–F.

| Cláusula | Evaluación al corte |
|:---|:---|
| A | NO ACREDITADO COMPLETO: Loudoun considerará una pausa de solicitudes legislativas el 20-oct; no es moratoria energética vigente ni denegación documentada a CPD >50 MW. |
| B | NO ACREDITADO: la nueva orden Duke no corresponde a PJM/ERCOT ni prueba EEA≥2 por demanda conjunta climatización/CPDs. |
| C | NO ACREDITADO COMPLETO: órdenes 46–49 no acreditan conjuntamente sujeto CPD/gran carga >50 MW, obligación operativa y duración ≥4 horas. |
| D | NO VERIFICABLE: sin acto Ofgem/EirGrid recuperado que documente curtailment comercial de CPDs >100 MW conjuntos. |
| E | NO VERIFICABLE: sin moratoria hídrica española/irlandesa recuperada que impida licencias CPD >50 MW. |
| F | NO ACREDITADO: propuesta CE del 21-sep no equivale a sanción/demanda EED basada en WUE sectorial >0,5 L/kWh; no se recuperó tal acto. |

### CoWoS

No se recuperó nueva prueba primaria de retraso de AP7, caída de rendimiento CoWoS-L, plazos generalizados o incumplimiento físico de entregas. No equivale a certificar ausencia de problemas. Los resultados TSMC Q2 y su guía Q3 son antecedentes; facturación y guía agregadas no miden capacidad de empaquetado.

[Calendario TSMC](https://investor.tsmc.com/english/financial-calendar), contrastado 27-sep: ventas septiembre **8-oct**, resultados Q3 **15-oct**, ventas octubre **10-nov**, sujetos a cambios. Son hitos futuros. La transcripción Q2 no se recuperó en esta consulta; no se rellenan yields o lead times desde estimaciones secundarias. [Resultados Q2](https://investor.tsmc.com/english/quarterly-results/2026/q2). Se conserva P4/→ con cobertura directa limitada. Alibaba se sigue en ficha propia por sustitución tecnológica, sin duplicar la carga del empaquetado.

| Cláusula | Evaluación al corte |
|:---|:---|
| A | NO VERIFICABLE: no se recuperó comunicado oficial de retraso AP7 más allá de H1 2027; tampoco se certifica cumplimiento del plazo. |
| B | PERIODO INCOMPLETO / NO VERIFICABLE: sin serie de yields CoWoS-L y entregas Blackwell que pruebe recorte físico >20% frente a guía Q4 2026. |
| C | NO ACREDITADO COMPLETO: falta agregado homogéneo de guía CAPEX Q3/Q4 y nexo de reducción >10% con ralentización física de aceleradores; no mezclar trimestres fiscales. |
| D | NO VERIFICABLE: sin plazo generalizado <20 semanas atribuible a sobrecapacidad; no se sustituye por ingresos TSMC. |

### Lloyd’s / riesgo marítimo

OMI al **24-sep**: **85 incidentes confirmados y 24 marinos fallecidos**, frente a 80/22 en la base anterior al 16-sep. El incremento acumulado +5/+2 no significa que todos ocurrieran en esta semana. La relación incluye daños a AL MARYAH y LR STEPHANIE el 21-sep y CAPE DAO el 23-sep; no documenta por sí sola hundimiento de VLCC/GNL ni cierre de Ormuz >5 Mb/d durante >48 h.

La circular vigente recuperada sigue siendo JWLA-035. JWC delimita áreas; no fija una prima universal. No se han obtenido las dos cotizaciones independientes exigidas por A. Fuentes consultadas 27-sep: [OMI, relación de incidentes](https://www.imo.org/en/mediacentre/hottopics/pages/middle-east-highlighted-incidents.aspx), [LMA/JWC](https://lmalloyds.com/specialist_area/marine/). Se conserva E1/P4/↑ por recurrencia física; la intensidad económica queda incompletamente medida.

| Cláusula | Evaluación al corte |
|:---|:---|
| A | NO VERIFICABLE: no se recuperaron dos cotizaciones independientes/circular verificable de prima ≥1,5% por casco y corredor comparable, ni retirada de cobertura ≥48 horas. |
| B | NO ACREDITADO COMPLETO: OMI registra daños e incidentes, sin acreditar aquí hundimiento de buque crítico VLCC/GNL en el corredor requerido. |
| C | NO VERIFICABLE: sin declaración portuaria primaria de imposibilidad de bunkering por saturación en puertos africanos. |
| D | NO VERIFICABLE: sin prueba de cierre de Ormuz con impacto >5 Mb/d durante >48 horas. |

### US Tariff Stack

El [CSMS 69851916 de CBP, 11-sep](https://content.govdelivery.com/bulletins/gd/USDHSCBP-429db0c) confirma instrucciones de implementación desde 15-sep para partidas afectadas: antecedente recuperado, no nueva recaudación observada. [Canada Gazette, publicación 23-sep](https://gazette.gc.ca/rp-pr/p2/2026/2026-09-23/html/sor-dors186-eng.html) publica el acto del 8-sep; no se fecha la represalia como nueva el 23. La base canadiense de 27.600 M CAD no se expresa como dólares estadounidenses.

Las prohibiciones estadounidenses anunciadas para **29-sep** son futuras al corte. Las recomendaciones comerciales Xi–EE. UU. no prueban rebajas ya aplicadas. [Casa Blanca, 8-sep](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/), consulta 26–27-sep. Se conserva E1/P4/↑ sobre la escalada jurídica vigente; no se atribuye todavía el umbral de costes, comercio o inflación a esa escalada.

| Cláusula | Evaluación al corte |
|:---|:---|
| A | PARCIAL JURÍDICO: instrucciones CBP respaldan implementación, pero no acreditan íntegramente cobro material del 50% en los tres grupos y ausencia de suspensión. No se confunde guía con recaudación. |
| B | ACTIVO HEREDADO de la represalia canadiense del 8-sep sobre base de 27.600 M CAD; publicación Gazette 23-sep no crea otra activación. Mantener unidad CAD y no duplicar con Xi. |
| C | NO ACREDITADO COMPLETO: faltan dos fabricantes con impacto >5% y atribución causal documentada, o relocalización física conforme a la cláusula. |
| D | PERIODO INCOMPLETO: datos agosto y septiembre previstos 6-oct y 4-nov; aún no prueban caída sectorial >15% interanual dos meses consecutivos. |
| E | NO ACREDITADO COMPLETO: sin dos publicaciones oficiales que atribuyan ≥0,3 pp a bienes por los aranceles. |

### Nuevas altas y tres seguimientos completados

- **Francia:** TEC10 AFT18/25-sep4,47/4,63%; Bund de referencia3,50/3,58%. Proxy97→105 pb (+8); pico110 pb24-sep. Diferencia TEC de vencimiento constante frente a bono alemán de referencia: no spread homogéneo ni prueba de contagio italiano. [AFT](https://www.aft.gouv.fr/fr/tec-10-du-jour) y [Bundesbank, serie](https://www.bundesbank.de/resource/blob/772218/c2957e9a34b596c0c5bb11811de0ff9e/472B63F073F071307366337C94F8C870/rendbund-data.pdf), consultados26-sep. Vigilar absorción y financiación; sin E1 por precio aislado.
- **Gas:** GIE mostraba26-sep06CEST UE797,20 TWh/70,45%; Alemania57,07%, Países Bajos56,83%. Una instantánea no acredita tendencia ni racionamiento. [GIE](https://www.gie.eu/), consulta26-sep. Flujos, demanda ajustada y restricciones industriales pendientes de series comparables; umbrales futuros no inventados.
- **Chips chinos:** Alibaba22-sep anunció V900 con producción/comercialización Q1 2027; >650 clientes corresponde a la familia Zhenwu, no a entregas de V900. [Comunicado](https://www.alibabacloud.com/en/press-room/alibaba-unveils-roadmap-on-full-stack-ai-strategy?_p_lc=1), consulta26-sep. Declaración de fabricante, sin auditoría de rendimiento/utilización. Horizonte Q1 2027 fuera del radar60d.
- **Xi:** reunión24-sep confirmada25-sep; recomendaciones para30.000 M$ de bienes por dirección y mecanismos bilaterales no equivalen a aplicación ni canal operativo. [China](https://eu.china-mission.gov.cn/eng/mhs/202609/t20260925_12031181.htm) y [Casa Blanca](https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-advances-a-fair-and-reciprocal-relationship-with-china-while-hosting-historic-state-visit/), consulta26-sep. Ventana resuelta; ficha E0 sigue implementación.
- **Midterms:** elecciones3-nov confirmadas por [FEC](https://www.fec.gov/introduction-campaign-finance/election-results-and-voting-information/), consulta27-sep. No se proyecta resultado electoral ni transmisión fiscal como hecho.
- **Unitree:** >5.500 entregas y >6.500 unidades producidas en2025 según [declaración de22-ene](https://shop.unitree.com/blogs/news/clarification-regarding-unitrees-2025-sales-data), consulta26-sep. Antecedente del fabricante, no prueba de uso productivo2026 ni sustitución laboral. E0 permanece como hipótesis a observar.

Las seis fichas utilizan paneles de evidencia y condiciones de revisión; no se inventan umbrales cuantitativos de activación. Intensificación/E1 requiere transmisión atribuible documentada y nueva decisión humana. Ausencia de confirmación no equivale a cero ni autoriza una baja silenciosa.

## 4. Vectores: auditoría propia y antisolapamiento

Los semáforos se conservan. Los contadores estructurales antiguos no se presentan como nuevas activaciones W39. Un trigger de vector no activa por sí mismo el de una ficha. Evaluación de las25 cláusulas propias:

### V01

- 01 — NO VERIFICABLE: spread interbancario >15 pb por cinco días requiere definir serie; SOFR–IORB negativo es sensor, no sustituto universal.
- 02 — NO VERIFICABLE: no se recuperó SRF diaria >50 B$ durante más de cinco días; umbral distinto del evento Japón.
- 03 — NO VERIFICABLE: falta secuencia comparable de dos emisiones 10Y/30Y con cobertura <2,3; la subasta JGB 30Y de 3-sep no la sustituye.
- 04 — NO ACREDITADO COMPLETO: TEC10 francés 4,63% al 25-sep no supera 5%; sin serie completa del benchmark y duración >10 sesiones.

### V02

- 01 — PARCIAL HEREDADO; NO VERIFICABLE cuantitativamente en W39: falta prima comparable >0,5% del casco por tránsito.
- 02 — PARCIAL HEREDADO; NO VERIFICABLE cuantitativamente: recuento OMI no mide caída de tránsito energético >20% en media móvil de 14 días.
- 03 — NO VERIFICABLE: incidentes no acreditan daño en terminales con reducción global >1 Mb/d.
- 04 — NO VERIFICABLE: sin serie de desvío >30% del volumen nominal.
- 05 — ACTIVO ESTRUCTURAL HEREDADO: órdenes 202(c) preservan generación fuera del régimen ordinario y autorizan respaldo. Las nuevas órdenes confirman continuidad institucional; no prueban despacho realizado ni activan el trigger C del evento Grid.

### V03

- 01 — PARCIAL HEREDADO; NO VERIFICABLE agregado: falta guía trimestral homogénea de hyperscalers y desviación >15%; Oracle aislado no basta.
- 02 — NO VERIFICABLE: no se recuperó serie de plazos >24 semanas generalizados.
- 03 — NO ACREDITADO NUEVO: sin nuevo registro formal recuperado sobre nodos/arquitecturas de vanguardia; anuncio comercial Alibaba no es sanción.
- 04 — NO ACREDITADO: V900 anunciado para Q1 2027 no es auditoría de procesamiento comercial sub-5nm sin litografía occidental.

### V04

- 01 — ACTIVO JURÍDICO HEREDADO: marco arancelario extraordinario sectorial >20%; instrucciones CBP y represalia documentan continuidad, sin certificar recaudación.
- 02 — PARCIAL HEREDADO; NO VERIFICABLE: falta SCFI frente a media móvil de 90 días para desviación sostenida >20%.
- 03 — NO VERIFICABLE: anuncios de compras o mecanismos bilaterales no prueban liquidaciones sin USD >50 B$ anuales.
- 04 — NO VERIFICABLE: sin IED industrial homogénea hacia jurisdicciones puente que pruebe aumento >30% interanual.

### V05

- 01 — NO VERIFICABLE: no se incorpora serie anual homogénea de déficit neto previsional >2% PIB G7/eurozona.
- 02 — NO VERIFICABLE: falta ratio comparable cotizantes/pensionistas <1,4 durante ejercicio completo.
- 03 — NO VERIFICABLE: CAPEX Oracle no equivale a salida neta industrial de una jurisdicción >5 B$ anuales.
- 04 — NO ACREDITADO COMPLETO: ACEA mide matriculaciones por propulsión, no cuota importada de nueva generación >25% por seis meses; no confundir BEV con origen chino.

### V06

- 01 — NO VERIFICABLE: sin liquidación no hegemónica en plataformas alternativas >100 B$ mensuales sostenidos.
- 02 — PARCIAL HEREDADO; NO VERIFICABLE W39: falta comparación de dos presupuestos consecutivos con aumento >15% anual; no se vuelve a certificar la base antigua.
- 03 — NO ACREDITADO NUEVO: sin concesión/uso militar nuevo de base dual soberana en estrecho estratégico recuperado.
- 04 — NO ACREDITADO: prórroga de listados individuales UE no acredita congelación de >50 B$ de banco central extranjero en un decreto.

C22 permanece sin ficha/carga: Oracle Q1 FY27, trimestre terminado31-ago y publicado10-sep, caja operativa23.103 M$, CAPEX28.499 M$, flujo libre−5.396 M$. CAPEX neto ajustado17.966 M$ es otra métrica; anticipos de clientes11.363 M$ dentro de la caja operativa. Un emisor no prueba insolvencia sectorial. [Oracle, comunicado](https://investor.oracle.com/files/content_files/1q27-pressrelease-September_FINAL.pdf), consulta26-sep. Panel canónico en V01.

V05 incorpora ACEA enero–agosto UE, publicado24-sep: BEV1.641.333/21,7%; PHEV758.082/10,0%. [ACEA](https://www.acea.auto/files/Press_release_car_registrations_August_2026.pdf), consulta26-sep. No mezclar con H1 ni confundir propulsión con cuota china importada. La evidencia actual de V06 incluye prórroga de listados individuales por36meses hasta22-sep-2029, [Consejo UE22-sep](https://www.consilium.europa.eu/en/press/press-releases/2026/09/22/ukraine-s-territorial-integrity-eu-extends-individual-listings-for-further-three-years/), consulta26-sep; no todos los regímenes sancionadores.

## 5. Revisión de las seis tesis

| Tesis | Soporte conservado | Lectura W39 |
|:---|:---|:---|
| [[TESIS_01_Dominancia_Fiscal]] | Moderado | Francia y Japón refuerzan la restricción de financiación. El diferencial francés es proxy no homogéneo y faltan flujos cubiertos. |
| [[TESIS_02_Frictionless_Stabilization]] | Alto | La combinación de medidas canadienses selectivas y mecanismos Xi–EE. UU. respalda coerción modular. La modularidad jurídica no mide estabilidad económica alcanzada. |
| [[TESIS_03_Captura_de_Renta]] | Moderado-alto | Se conserva el corpus previo; ACEA y Unitree aportan sensores industriales. No hay esta semana series homogéneas que prueben desplazamiento fiscal, demográfico o de renta por esos sensores. |
| [[TESIS_04_Multipolaridad_Logistica]] | Moderado-alto | La recurrencia física OMI y la exposición de gas europeo apoyan dependencia de rutas y nodos. Incidentes no cuantifican cierre, prima o caída de flujos; inventario gas aislado no mide deterioro. |
| [[TESIS_05_Tokenizacion_del_Colateral]] | Moderado | Se conserva en validación; la semana no aporta nueva prueba directa. Faltan admisibilidad, haircut y liquidación operativa comparable. |
| [[TESIS_06_IA_como_silicio_y_energia]] | Alto | Las órdenes de red y el calendario industrial Alibaba confirman dependencia de infraestructura; C22 añade restricción financiera diferenciada. Guía, producción anunciada, entrega y utilización no son equivalentes; Oracle es un emisor. |

**T01 — Moderado.** Apoyo: Francia y Japón refuerzan la restricción de financiación. Contraevidencia: La recuperación puntual de reservas y SOFR inferior a IORB contradicen un drenaje continuo; las alzas de tipos no acreditan subordinación fiscal. Ambigüedad: El diferencial francés es proxy no homogéneo y faltan flujos cubiertos. Próxima falsación: Contrastar repatriación, absorción y respuesta efectiva del banco central al conflicto fiscal.

**T02 — Alto.** Apoyo: La combinación de medidas canadienses selectivas y mecanismos Xi–EE. UU. respalda coerción modular. Contraevidencia: Las prohibiciones futuras pueden romper, en vez de estabilizar, intercambios. Ambigüedad: La modularidad jurídica no mide estabilidad económica alcanzada. Próxima falsación: Observar aplicación, flujos y persistencia de canales; ruptura sostenida debilitaría la tesis.

**T03 — Moderado-alto.** Apoyo: Se conserva el corpus previo; ACEA y Unitree aportan sensores industriales. Contraevidencia: Adopción de vehículos o robots también puede elevar productividad y renta disponible. Ambigüedad: No hay esta semana series homogéneas que prueben desplazamiento fiscal, demográfico o de renta por esos sensores. Próxima falsación: Comparar renta, inversión, vivienda y pensiones en universos compatibles; sin validación incremental W39.

**T04 — Moderado-alto.** Apoyo: La recurrencia física OMI y la exposición de gas europeo apoyan dependencia de rutas y nodos. Contraevidencia: Diplomacia bilateral e inventarios disponibles permiten amortiguar la transmisión. Ambigüedad: Incidentes no cuantifican cierre, prima o caída de flujos; inventario gas aislado no mide deterioro. Próxima falsación: Contrastar tránsito, seguros, fletes y restricciones industriales con duración y causalidad.

**T05 — Moderado.** Apoyo: Se conserva en validación; la semana no aporta nueva prueba directa. Contraevidencia: Digitalizar un pasivo o mantener T-bills en una stablecoin no prueba colateral corporativo nuevo utilizable. Ambigüedad: Faltan admisibilidad, haircut y liquidación operativa comparable. Próxima falsación: Exigir operación de repo/garantía ejecutada con activo tokenizado y condiciones auditables; sin subir soporte por vínculos.

**T06 — Alto.** Apoyo: Las órdenes de red y el calendario industrial Alibaba confirman dependencia de infraestructura; C22 añade restricción financiera diferenciada. Contraevidencia: Inversión y expansión continúan; no se acredita fallo CoWoS ni curtailment CPD conforme a triggers. Ambigüedad: Guía, producción anunciada, entrega y utilización no son equivalentes; Oracle es un emisor. Próxima falsación: Contrastar entregas, rendimiento, utilización, electricidad y caja; capacidad disponible sin fricción material debilitaría la restricción fuerte.

## 6. Radar y ciclo de vida

24 hitos abiertos (1 Régimen / 6 Crítico / 13 Elevado / 4 Latente), seis observatorios, cero ventanas enriquecidas y 19 resoluciones. Horizonte 26-sep–25-nov; fechas prospectivas y calendarios heredados identificados en el radar. 22 previas−3 resueltas+5 nuevas=24. UE22-sep, BoJ24-sep y Xi24-sep resueltos con fuentes y filas originales preservadas. Nuevos sensores: Craig27-sep; MOF1-oct; TSMC15-oct; Loudoun20-oct; Eddystone20-nov. Una fecha normativa futura no acredita despacho, restricción ni resultado.

Los calendarios consultados19-sep permanecen identificados como heredados; los nuevos/contrastados26–27-sep llevan fuente específica. TSMC y subastas tentativas conservan provisionalidad. V05 no tiene hito con fecha primaria; Francia/gas/Alibaba siguen paneles sin inventar fechas. C22 es el sexto observatorio. No se crea automatización ni vigilancia continua. [[Radar_Eventos_2026_09]].

## 7. Límites, controles y siguiente revisión

- Faltan SRF diaria reciente, diferencial japonés cubierto, primas comparables, tránsito/fletes y series físicas CoWoS. Estos huecos impiden conclusiones específicas; se registran por cláusula.
- MOF13–26-sep se publicará1-oct; SOFR25-sep, el28-sep. No se interpreta falta de publicación como ausencia del fenómeno.
- Francia usa proxy metodológicamente imperfecto; gas una instantánea; Alibaba/Unitree declaraciones del fabricante. Anuncio, normativa, producción y uso se mantienen separados.
- Las fuentes dinámicas se citan con fecha de observación/publicación/consulta; pueden revisarse. La base previa permanece archivada, sin reetiquetar evidencia antigua.
- Inventario11, clase9/2, cargas/vectores144,8, tablas y enlaces internos comprobados. Radar24 IDs únicos/12 columnas; horizonte60d; seis observatorios/19 resoluciones. El informe anterior se archiva al verificar este.
- Solo bloques231 de Dashboard/Snapshot actualizados; validez global y otros sistemas preservados. Publicación de este precierre en `lgarvia/sistema-231-macro`, rama `main`, autorizada por Luis después de TASK_148.

Próximas comprobaciones materiales: implementación arancelaria29-sep, cierre de liquidez y Micron30-sep, flujos MOF1-oct. Nuevas altas, bajas o recalibraciones se propondrán a Luis conforme al protocolo; las autorizaciones ya resueltas no se repiten.

Conecta con [[VECTOR_00_Indice]] · [[TESIS_00_Indice]] · [[SALUD_DEL_SISTEMA]] · [[MAPA_TRANSMISIONES]] · [[Radar_Eventos_2026_09]].
