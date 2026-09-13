---
titulo: "Grid Stress e Infraestructura Hídrica / Centros de Datos e IA"
fecha: 2026-07-08
source: PJM / ERCOT / Utilities / DOE / Arizona Dept of Water Resources
url: https://www.ferc.gov/
vector: "[[VECTOR_02_Energia_y_nodos_geoeconomicos]]"
moc: "[[MOC_Tecnologia]]"
tags: [energía, agua, grid-stress, ia, cpd, infraestructura]
tipo: evento
aliases: [Evento_E1_2026_07_08_Grid_Stress_IA]
---

# EVENTO: E0_2026_07_08_Grid_Stress_IA

## 1. SNAPSHOT ACTUAL
- **Estado:** 🟠 En observación intensificada — E0; ESTRÉS FÍSICO DE RED / VÍNCULO CPD PARCIAL
- **Nivel de presión:** ELEVADA (P4)
- **Dirección de tendencia:** → Estable
- **Peso estructural:** 4
- **Última actualización:** 2026-09-12 (precierre W37; corte 21:21 CEST)
- **Contribución primaria:** 4 × 4 × 1,0 = **16,0**
- **Vector primario:** [[VECTOR_02_Energia_y_nodos_geoeconomicos]]
- **Vectores secundarios:** [[VECTOR_03_Semiconductores_y_soberania_tecnologica]], [[VECTOR_05_Transformacion_industrial_y_demografia]]
- **KPIs Actuales:**
  - Orden DOE 202-26-39: prolonga la disponibilidad obligatoria de J.H. Campbell desde el 17/08/2026 hasta el 14/11/2026.
  - Orden DOE 202-26-40: efectiva del 23/08/2026 al 20/11/2026, mantiene disponibles Eddystone 3 y 4 en PJM citando expresamente la carga de centros de datos e IA.
  - Orden DOE 202-26-25A: prolonga la disponibilidad de Wagner 4 del 20/08/2026 al 17/11/2026 a petición de PJM.
  - Orden DOE 202-26-38 (Stanton / Florida): expiró el 01/09/2026 sin colapso de red ni prórroga adicional requerida.
  - Orden DOE 202-26-41 (PJM): emitida el 01/09 y expirada el 08/09/2026; acredita una intervención temporal de fiabilidad, pero no atribuye la emergencia a CPDs ni impone reducción o autogeneración forzada a una gran carga.
  - Alerta sistémica: no se verifica una EEA2/EEA3 causada específicamente por la demanda conjunta de climatización y centros de datos.
  - FERC: el 14/08 concedió 90 días de suspensión a los seis expedientes EL26-67 a EL26-72; el proceso tarifario y de interconexión para grandes cargas sigue abierto sin resolución material en la semana.
  - Restricción hídrica / EED: no se verifica todavía un Trigger E o F en España, Irlanda o la UE.

## 2. CONDICIONES DE ACTIVACIÓN (TRIGGERS)
- **Trigger A (Electricidad):** Publicación de moratorias oficiales de energía o denegaciones de derechos de conexión en el corredor de Loudoun County (Virginia) para proyectos de CPDs de IA superiores a 50 MW. (Parcial)
- **Trigger B (Electricidad — NO VERIFICADO):** Emisión de alerta de emergencia eléctrica de Nivel 2 o superior por parte de PJM o ERCOT debido a sobrecarga generada por la demanda conjunta de climatización residencial y CPDs en picos de calor estivales.
- **Trigger C (Electricidad):** Emisión de una orden vinculante de DOE, FERC o un RTO/ISO que obligue explícitamente a operadores de CPDs o grandes cargas superiores a 50 MW —o a recursos de generación *behind the meter* asociados a esas instalaciones— a activar generación propia o reducir su consumo de red durante al menos cuatro horas. **Estado: no activado; las órdenes DOE 202(c) activas ordenan mantener generación en despacho económico a centrales de carbón/gas, sin imponer curtailment o autogeneración forzada a CPDs.**
- **Trigger D (Electricidad):** Entrada en vigor de protocolos de desconexión forzada (curtailment) por parte de Ofgem o EirGrid que limiten activamente la potencia de CPDs de IA en operación comercial por encima de los 100 MW conjuntos.
- **Trigger E (Agua):** Publicación de moratorias municipales o estatales de agua en España o Irlanda que impidan de facto la concesión de licencias hídricas a nuevos CPDs de IA superiores a 50 MW.
- **Trigger F (Agua):** Sanciones o demandas regulatorias de la Comisión Europea derivadas de datos del registro EED que demuestren un WUE del sector superior a 0.5 L/kWh promedio en el bloque.

## 3. CONTEXTO Y SEÑAL DOMINANTE
El despliegue de grandes cargas de cómputo depende de capacidad de generación, transmisión, interconexión y refrigeración. La Orden 202-26-39 prolonga hasta el 14/11 la obligación de mantener disponible J.H. Campbell, la 202-26-25A prolonga Wagner 4 hasta el 17/11 y la 202-26-40 mantiene Eddystone hasta el 20/11 citando el crecimiento de centros de datos e IA en la previsión de carga de PJM. En W37, la Orden 202-26-41 para PJM expiró el 08/09: confirma estrés físico temporal, pero no demuestra causalidad específica de CPDs ni obliga a operadores de IA a reducir carga o autogenerar. FERC mantiene en suspensión de 90 días los procedimientos tarifarios EL26-67..72. Tampoco se verifica moratoria hídrica europea. La señal dominante sigue siendo restricción física activa con vínculo CPD parcial, sin aceleración incremental suficiente ni ejecución de A–F.

## 4. TESIS (Luis)
La IA no es una nube virtual desmaterializada; es cobre, subestaciones eléctricas y agua de refrigeración. La restricción de la computación avanzada ya no se mide en FLOPS, se mide en megavatios (MW) y en litros de agua. En un entorno donde las redes de distribución nacionales están saturadas y los recursos hídricos locales están protegidos, las restricciones físicas de red y de enfriamiento limitarán el ritmo de la IA mucho antes de que los modelos de software alcancen límites de datos. La transición digital requiere una sobreestructura física que Occidente no tiene la agilidad institucional para construir a tiempo.

## 5. IMPLICACIONES Y TRANSMISIÓN
- **Transmisión:** V02 → V03 (Disponibilidad física de centros de datos de IA) → V05 (Capex y desarrollo industrial).
- **Implicaciones:** El estrangulamiento de red y las exigencias de circuito cerrado (WUE nulo) obligan a adoptar sistemas de enfriamiento seco o refrigeración líquida directa, que aumentan el PUE y encarecen significativamente el CAPEX de IA, forzando pérdidas de eficiencia de capital.

## 6. HISTORIAL FACTUAL
- **07/06/2026**: Programación del evento en el radar mensual para el inicio del ciclo de calor estival.
- **21/06/2026**: Creación de la ficha de monitoreo de capacidad eléctrica del ecosistema de centros de datos de IA.
- **28/06/2026**: La FERC emitió una directiva ordenando a los operadores de red revisar y agilizar los procesos de interconexión para data centers de IA. Ofgem evalúa protocolos de "curtailment" mandatorio. Se inicia el monitoreo de la directiva EED de la Comisión Europea y moratorias de agua en Arizona.
- **01/07/2026 — entrada suplantada el 18/07/2026**: no se conserva como evidencia; mezclaba una medida fiscal/hídrica no acreditada con una moratoria operativa.
- **02/07/2026 — entrada suplantada el 18/07/2026**: no se conserva como evidencia; atribuía a la orden DOE obligaciones específicas a centros de datos que el texto oficial no contiene.
- **05/07/2026 — entrada suplantada el 18/07/2026**: no se conserva como evidencia; las órdenes FERC se emitieron el 18/06 y sus plazos eran de 30 y 60 días.

## 7. ACTUALIZACIÓN FACTUAL RECIENTE
- **18/07/2026**: Corrección forense: la orden federal operativa es la **DOE 202-26-35**, emitida el **14/07/2026** y vigente hasta el 21/07. Ordena a PJM despachar unidades especificadas y autoriza la operación de generación de respaldo como último recurso antes o durante una EEA3. Esto constituye señal física de estrés de red, pero **no activa el Trigger C** reformulado, porque la orden no acredita por sí sola una obligación específica impuesta a operadores de CPDs; tampoco demuestra una EEA2 causada por CPDs, por lo que el Trigger B queda sin verificar. Las órdenes *show cause* de FERC se emitieron el **18/06**, no el 05/07: los seis RTO/ISO disponen de 30 días para informar sobre suficiencia de generación y 60 días para justificar o reformar tarifas. **Acción: reclasificar de E1 a E0 y reformular el Trigger C, autorizadas por Front Office el 18/07/2026.** Fuentes: [DOE](https://www.energy.gov/ceser/federal-power-act-section-202c-pjm-interconnection-llc-pjm-order-no-202-26-35), [FERC](https://www.ferc.gov/news-events/news/ferc-launches-aggressive-targeted-action-speed-large-load-integration).
- **26/07/2026**: La Orden **DOE 202-26-35 expiró el 21-jul** sin prórroga oficial localizada. Sigue vigente la Orden **202-26-24**, que mantiene disponibles las unidades 3 y 4 de Eddystone y exige su oferta en despacho económico hasta el 22-ago, pero no identifica CPDs ni obliga a una gran carga concreta a autogenerar o reducir consumo durante cuatro horas. Por tanto, no activa el Trigger C; tampoco hay EEA2 atribuida a CPDs, moratoria hídrica europea o curtailment comercial verificado. El siguiente punto de decisión es la respuesta de los RTO/ISO a FERC el **17-ago**. **Acción: mantener E0, P4 y estable; Triggers A–F sin activación completa.** Fuentes: [DOE 202-26-24](https://www.energy.gov/ceser/federal-power-act-section-202c-pjm-interconnection-llc-pjm-order-no-202-26-24), [DOE 202-26-35](https://www.energy.gov/ceser/federal-power-act-section-202c-pjm-interconnection-llc-pjm-order-no-202-26-35), [FERC](https://www.ferc.gov/news-events/news/ferc-launches-aggressive-targeted-action-speed-large-load-integration).
- **02/08/2026**: El DOE emitió el **26-jul la Orden 202-26-37 para SPP**, vigente hasta el 3-ago, que obliga a despachar generación especificada y autoriza recursos de respaldo como último recurso antes o durante una EEA3. La orden refuerza el Trigger 05 completo de V02, pero no activa el Trigger C de esta ficha porque no identifica CPDs ni acredita una obligación de reducción o autogeneración de cuatro horas para una gran carga concreta. **Acción: mantener E0 intensificado y P4; elevar tendencia a ↑ por recurrencia regional; Triggers A–F sin activación completa.** Fuente: [DOE — órdenes 202(c) de 2026](https://www.energy.gov/ceser/2026-doe-202c-orders).
- **16/08/2026**: Expirada la Orden DOE 202-26-37. La Orden **DOE 202-26-24 (PJM / Eddystone)** sigue vigente hasta el **22/08**. El plazo de 60 días de las órdenes FERC alcanza el 17/08. Fuentes: [DOE 202-26-24](https://www.energy.gov/ceser/federal-power-act-section-202c-pjm-interconnection-llc-pjm-order-no-202-26-24), [FERC](https://www.ferc.gov/news-events/news/ferc-launches-aggressive-targeted-action-speed-large-load-integration).
- **17/08/2026 — primera revisión**: El hito FERC entra en fecha de decisión; la respuesta material de los seis RTO/ISO se evaluará a partir de expedientes o comunicados específicos, no de la portada institucional. A esta hora no se incorpora desde FERC un resultado que active A–F.
- **17/08/2026 — contraste externo posterior**: Localizada la **Orden DOE 202-26-39**, emitida el 14/08 y efectiva del 17/08 al 14/11, que obliga a MISO a mantener disponible J.H. Campbell y prolonga sin interrupción la intervención anterior. La orden refuerza la recurrencia y duración del estrés físico, pero no identifica CPDs ni obliga a una gran carga concreta a autogenerar o reducir consumo durante cuatro horas; por tanto, el Trigger C sigue inactivo. **Acción: mantener E0/P4 y restaurar tendencia ↑.** Fuente: [DOE — órdenes 202(c) de 2026](https://www.energy.gov/ceser/2026-doe-202c-orders).
- **23/08/2026 — parcialmente suplantada el 29/08/2026**: El DOE emitió el 19/08 la **Orden 202-26-25A**, efectiva del 20/08 al 17/11, para que PJM mantenga disponible Wagner 4 ante necesidades previstas de fiabilidad. La afirmación de que Eddystone venció sin prórroga queda suplantada por la Orden 202-26-40 localizada el 29/08; el resto de la entrada se conserva. En paralelo, FERC concedió el 14/08 una suspensión de 90 días en los seis expedientes de grandes cargas, de modo que el hito del 17/08 fue procedimental y no una reforma tarifaria material. **Acción en W34: mantener E0 · P4 · ↑.** Fuentes: [DOE — órdenes 202(c) de 2026](https://www.energy.gov/ceser/2026-doe-202c-orders), [DOE — Wagner 202-26-25A](https://www.energy.gov/articles/energy-secretary-acts-protect-mid-atlantic-grid), [FERC — EL26-67](https://elibrary.ferc.gov/eLibrary/filelist?accession_number=20260814-3059) y expedientes correlativos.
- **29/08/2026**: Localizada la **Orden DOE 202-26-40**, emitida el 21/08 y efectiva del 23/08 al 20/11, que sucede a la 202-26-24 y mantiene disponibles Eddystone 3 y 4. El texto incorpora el crecimiento de centros de datos e IA a la previsión de demanda de PJM, pero no ordena a un CPD o gran carga concreta autogenerar o reducir consumo durante cuatro horas. Por tanto, refuerza la causalidad parcial y la tendencia ↑, pero no activa C; tampoco aparecen EEA2 atribuida a CPDs, *curtailment* comercial o moratoria hídrica que active B o D–F. **Acción: mantener E0 · P4 · ↑; A–F sin activación completa.** Fuente: [DOE — Orden 202-26-40](https://www.energy.gov/documents/doe-order-no-202-26-40).
- **06/09/2026 — W36**: Se mantiene la vigencia de las tres órdenes federales de emergencia concurrentes: **DOE 202-26-39** (MISO / Campbell, hasta 14/11), **202-26-25A** (PJM / Wagner 4, hasta 17/11) y **202-26-40** (PJM / Eddystone 3 y 4, hasta 20/11). La orden temporal **202-26-38** (Stanton / Florida) expiró el 01/09/2026 conforme a calendario sin colapso de red ni extensiones de emergencia requeridas. En el plano regulatorio, FERC mantiene congelados bajo suspensión de 90 días los expedientes EL26-67..72 sobre interconexión de grandes cargas. Al no haber nuevas órdenes de emergencia emitidas en la semana, ni alertas EEA2/EEA3, ni órdenes vinculantes de reducción directa a CPDs, la situación representa persistencia de la restricción sin aceleración incremental en W36. **Acción en W36: mantener E0 · P4; ajustar tendencia de ↑ a →; Triggers A–F sin activación completa.** Fuentes: [DOE — órdenes 202(c) de 2026](https://www.energy.gov/ceser/2026-doe-202c-orders), [FERC eLibrary](https://elibrary.ferc.gov/).
- **12/09/2026 — precierre W37**: La Orden **DOE 202-26-41**, emitida el 01/09 para PJM, expiró el 08/09. El acto acredita necesidad temporal de fiabilidad y tensión física de red, pero no identifica la demanda de CPDs como causa necesaria ni obliga a un CPD o gran carga superior a 50 MW a autogenerar o reducir consumo durante cuatro horas. Las órdenes 202-26-39, 202-26-25A y 202-26-40 continúan vigentes; no se verifica en W37 una EEA2/EEA3 atribuida conjuntamente a climatización y CPDs, una nueva resolución FERC material, *curtailment* comercial europeo o moratoria hídrica que active B–F. **Acción: mantener E0 · P4 · →; A parcial y B–F inactivos.** Fuente: [DOE — Orden 202-26-41](https://www.energy.gov/ceser/federal-power-act-section-202c-pjm-interconnection-llc-pjm-order-no-202-26-41).

## 8. VALIDACIÓN FRONT OFFICE
- **02/08/2026:** actualización, mantenimiento en E0 · P4 y cambio de tendencia de → a ↑ aprobados.
- **09/08/2026:** actualización W32 y mantenimiento en E0 · P4 · ↑ aprobados.
- **16/08/2026:** actualización W33 y mantenimiento en E0 · P4 · ↑ aprobados.
- **17/08/2026:** corrección de antecedentes y tendencia → aprobadas por instrucción de puesta a punto integral.
- **17/08/2026:** revisión externa posterior y cambio de tendencia a ↑ aprobados por Front Office, sin promoción a E1.
- **23/08/2026:** actualización W34 y mantenimiento E0 · P4 · ↑ ejecutados por instrucción de Front Office.
- **29/08/2026:** corrección Eddystone y mantenimiento E0 · P4 · ↑ ejecutados por instrucción de Front Office.
- **06/09/2026:** actualización W36, mantenimiento E0 · P4 y ajuste de tendencia a → ejecutados por instrucción de Front Office en auditoría canónica.
- **12/09/2026:** precierre W37 y mantenimiento E0 · P4 · → ejecutados por instrucción de Front Office; sin promoción de la Orden 202-26-41 a trigger CPD.
