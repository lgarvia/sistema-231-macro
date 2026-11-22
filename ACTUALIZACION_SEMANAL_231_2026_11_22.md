---
tipo: "actualizacion_semanal_231"
semana: "2026-W47"
fecha_nominal: "2026-11-22"
corte_factual: "2026-11-21 18:11:49 Europe/Madrid"
modalidad: "precierre"
estado: "cerrada_publicacion_autorizada"
eventos_activos: 13
eventos_calibrados: 13
carga_subtotal_conocido: 171.76
carga_total: 171.76
task: "TASK_390_ACTUALIZACION_231_W47"
calibracion_C23: "aprobada_aplicada"
calibracion_final_aplicada: "2026-11-22T00:41:56+01:00"
publicacion: "autorizada_por_Luis_2026_11_22"
fecha_autorizacion_publicacion: "2026-11-22T00:58:27+01:00"
---

# Actualización del Sistema231 — W47

> Precierre W47 · nominal 22-nov-2026 · corte factual 2026-11-21 18:11:49 Europe/Madrid. Aplicación local 2026-11-22T00:33:37+01:00; TASK390. A y selección de inventario aprobadas por Luis: «Perfecto. Adelante con todo». C23: alta y calibración aprobadas por Luis22nov («Si»); P3/peso4,30/→factor1, carga12,90. Aplicación final 2026-11-22T00:41:56+01:00. No incorpora hechos posteriores al corte. Publicación autorizada por Luis22nov («Perfecto. Publica»); recepción remota verificada por separado.

**13 eventos activos (10 E0 / 3 E1), todos calibrados; carga primaria total 171,76.** Puente respecto a W46: 160,16 − 1,30 por los pesos aprobados + 12,90 del alta C23. Calibración C23 aprobada por Luis22nov («Si») y aplicada; no equivale a una activación E1 ni a efectos materiales demostrados.

| Evento | Clase | P | Peso | Tendencia | Factor | Primario | Carga |
|---|---|---|---|---|---|---|---|
| [[Evento_E0_2026_07_08_Grid_Stress_IA\|Grid IA]] | E0 | 4 | 4,70 | ↑ | 1.2 | V02 | 22,56 |
| [[Evento_E0_2026_08_16_Japon_Carry_Trade_y_Liquidez_Septiembre\|Japón / liquidez]] | E0 | 3 | 4,60 | → | 1 | V01 | 13,80 |
| [[Evento_E0_2026_09_19_Visita_Xi_EEUU\|EE. UU.–China / ejecución]] | E0 | 2 | 3,60 | → | 1 | V06 | 7,20 |
| [[Evento_E0_2026_09_26_Deuda_Francesa_y_Fragmentacion_Europea\|Deuda francesa]] | E0 | 3 | 4,30 | → | 1 | V01 | 12,90 |
| [[Evento_E0_2026_09_26_Gas_Europeo_Invierno\|Gas europeo / invierno]] | E0 | 3 | 4,00 | → | 1 | V02 | 12,00 |
| [[Evento_E0_2026_10_16_China_Controles_Exportacion_Tecnologica\|China: registro y controles de exportación de tecnologías estratégicas]] | E0 | 2 | 3,50 | → | 1 | V04 | 7,00 |
| [[Evento_E0_2026_11_11_NVIDIA_Sucesion_y_Continuidad_Operativa\|NVIDIA / sucesión y continuidad operativa]] | E0 | 2 | 3,10 | → | 1 | V03 | 6,20 |
| [[Evento_E0_2026_11_29_Elecciones_Espana_Gobernabilidad_Fiscal\|España / elecciones y ejecución fiscal]] | E0 | 2 | 3,20 | → | 1 | V01 | 6,40 |
| [[Evento_E0_2026_CoWoS_Capacity\|CoWoS]] | E0 | 4 | 4,50 | ↑ | 1.2 | V03 | 21,60 |
| [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb\|Riesgo marítimo]] | E1 | 4 | 4,60 | → | 1 | V02 | 18,40 |
| [[Evento_E1_2026_07_24_US_Tariff_Stack\|Tariff Stack]] | E1 | 4 | 4,10 | → | 1 | V04 | 16,40 |
| [[Evento_E1_2026_11_05_Ajuste_Valoraciones_IA_y_Transmision_Financiera\|Ajuste de valoraciones IA y transmisión financiera]] | E1 | 3 | 4,80 | → | 1 | V01 | 14,40 |
| [[Evento_E0_2026_11_19_US_Acceso_Remoto_Computo_Avanzado\|EE. UU. / acceso remoto a cómputo avanzado]] | E0 | 3 | 4,30 | → | 1 | V04 | 12,90 |

## Carga por vector y antisolapamiento

| Vector | Presión estructural | Tendencia estructural | Carga primaria |
|---|---|---|---|
| [[VECTOR_01_Arquitectura_monetaria_global]] | 🟠 ELEVADA | ↑ Acelerando | 47,50 |
| [[VECTOR_02_Energia_y_nodos_geoeconomicos]] | 🔴 CRÍTICA | ↑ Acelerando | 52,96 |
| [[VECTOR_03_Semiconductores_y_soberania_tecnologica]] | 🟠 ELEVADA | → Estable | 27,80 |
| [[VECTOR_04_Reconfiguracion_del_comercio_global]] | 🔴 CRÍTICA | → Estable | 36,30 |
| [[VECTOR_05_Transformacion_industrial_y_demografia]] | 🟡 MODERADA | → Estable | 0,00 |
| [[VECTOR_06_Orden_geopolitico_y_esferas_de_influencia]] | 🟡 MODERADA | → Estable | 7,20 |

Cada evento tiene un solo vector primario. C23 no se carga como cero; C60 no es evento. Semáforos/tendencias estructurales no se deducen de sumas.

## Cambios aplicados

Cinco pesos cambian y siete se mantienen tras revisión individual; altas1, bajas0, fusiones0, reclasificaciones0. Se conservan P/factores con justificación explícita por ficha; ninguna↑ se vende como nueva aceleración semanal.

| Evento | Vector | Peso W46 | Peso aprobado W47 | Carga previa | Carga aplicada | Justificación |
|---|---|---|---|---|---|---|
| Grid IA | V02 | 4,70 | 4,70 | 22,56 | 22,56 | Mantener: capacidad firme/conexión difíciles de sustituir, condicionan varias cadenas y exigen activos/permisos plurianuales. Alcance regional documentado no equivale a toda red mundial. |
| Japón / liquidez | V01 | 4,60 | 4,60 | 13,80 | 13,80 | Mantener: asignación global de duración/divisa/colateral. Absorción y repo contenidos afectan tensión actual; el canal estructural sigue global y de transmisión múltiple. |
| EE. UU.–China / ejecución | V06 | 3,30 | 3,60 | 6,60 | 7,20 | Subir transmisión3→4: el marco bilateral vuelve a mostrar un canal de coordinación estratégica/IA autónomo del arancel. No incluye el peso de toda la trilateral. |
| Deuda francesa | V01 | 4,00 | 4,30 | 12,00 | 12,90 | Subir transmisión4→5: riesgo soberano conectado a absorción internacional, inversores apalancados y crédito, además del presupuesto nacional. No es una subida por TEC10. |
| Gas europeo / invierno | V02 | 4,40 | 4,00 | 13,20 | 12,00 | Recalibrar a4/4/4/4: exposición europea elevada; distintas vías de suministro con costes y fricción. No equiparar el episodio estacional/recarga con dependencia prácticamente insustituible e irreversible. |
| China / registro48 | V04 | 3,50 | 3,50 | 7,00 | 7,00 | Mantener: mecanismo de registro/transferencia delimitado, con excepciones. Ni49–51 ni BIS se imputan automáticamente a esta ficha. |
| NVIDIA / sucesión | V03 | 3,60 | 3,10 | 7,20 | 6,20 | Reducir transmisión4→3 y sustitución3→2: ficha de gobierno/ejecución con dirección interina; no todo el riesgo del ecosistema. Publicación de resultados no prueba operación posrelevo. |
| España / elecciones-fiscal | V01 | 3,50 | 3,20 | 7,00 | 6,40 | Reducir transmisión4→3: evento de gobernabilidad→decisión→ejecución; no es todo el balance soberano o la productividad española. Cercanía electoral no amplía el canal. |
| CoWoS | V03 | 4,50 | 4,50 | 21,60 | 21,60 | Mantener: cuello de empaquetado específico, sustitución difícil y transmisión crítica. Capacidad/roadmaps alternativos no prueban normalización ni dependencia inmutable. |
| Riesgo marítimo | V02 | 4,60 | 4,60 | 18,40 | 18,40 | Mantener: corredores energéticos de alcance global y transmisión amplia; desvíos tienen costes pero existen. Incidentes nuevos no sustituyen primas/volúmenes/duración. |
| Tariff Stack | V04 | 4,10 | 4,10 | 16,40 | 16,40 | Mantener: régimen comercial de alcance global, transmisión por sectores y sustitución parcial; cambios de partidas/pausas no retiran toda fricción persistente. BIS tiene otro objeto. |
| IA / transmisión financiera | V01 | 4,80 | 4,80 | 14,40 | 14,40 | Mantener: alcance y transmisión globales, obligaciones plurianuales; financiación efectiva conserva alternativas. No asignar5 absoluto por toda noticia IA. |

## Diagnóstico factual de los seis vectores

| Vector | Novedad | Contrapeso o límite | Seguimiento tras aplicación |
|---|---|---|---|
| V01 — monetario | Red financiera IA mejor documentada; nuevos flujos y subastas. | Repo contenido y captación cerrada; sin contagio generalizado probado. | Revisar Japón, Francia y C22 por separado. |
| V02 — energía/nodos | Órdenes de fiabilidad y decisión urbanística Loudoun. | No corte comercial CPD con conjunciones exigidas; gas alemán mantiene flujos. | Separar disponibilidad de despacho y escasez de racionamiento. |
| V03 — silicio | Primera prueba de resultados NVIDIA bajo dirección interina. | Ventas agregadas no miden yields, plazos ni causalidad de sucesión. | No escalar tres fichas por la misma noticia. |
| V04 — comercio | Acceso remoto BIS y entrada china49–51. | Sin medición de licencias denegadas, entregas perdidas o cobro neto. | C23 incorporado E0/V04; objetos China48, otros controles y OISP separados. |
| V05 — industria/demografía | Industria europea y producción robótica china. | No prueba uso productivo, efecto laboral IA o desequilibrio anual neto. | Conservar cobertura pese a cero fichas. |
| V06 — geopolítica | Bilateral y cumbre trilateral celebradas. | Texto político sin ejecución comercial ni cambio militar acreditados. | Probar actos y flujos; C60 integrado en observatorio V06. |

### 2.1. V01: liquidez, absorción soberana y transmisión financiera

S01–S03 permiten calcular SOFR−IORB: **0/+3/+2/0/+1 pb**, días13/16/17/18/19nov. No completa J-C1 ni el proxy V01-01 en la muestra. Falta20nov; GCp99 es otra alternativa. S04: reservas promedio **2.979.656 MUSD**, +19.053 semanal; posición del miércoles **3.001.790 MUSD**. TGA promedio **916.613 MUSD**, posición892.310. Repo promedio16 MUSD, posición1 MUSD. No mezclar frecuencias ni identificar ese agregado con serie diaria íntegra SRF. Noviembre no reconstruye el mecanismo fiscal de septiembre.

S05,8–14nov: deuda exterior larga neta **−4.407 unidades de100 millones JPY =−440.700 MJPY**. Semana1–7nov revisada de−5.376 a−5.341 unidades: **+3.500 MJPY**. No usar el total de activos como deuda larga ni una semana como dos meses institucionales. S06 publica18nov sobre **septiembre**: entrada TIC261 BUSD, privada267 y oficial−6. Custodia no equivale a propietario último ni demuestra repatriación japonesa.

S07: TEC10 francés16–20nov **4,930/4,913/4,836/4,884/4,874%**, todas bajo5%. Frente13nov4,888%, **−1,4 pb**. No es spread OAT–Bund. S08: adjudicación19nov de11.996 MEUR en cuatro vencimientos2030–2034, coberturas **2,83/2,82/2,63/3,05**; liquidación23nov futura y posibles ONC2 no conciliadas.

Se recuperan PDFs oficiales que faltaban en W46: S57 UST10Y10nov **5,020% /cobertura2,46**; S58 UST30Y12nov **5,441% /2,36**. Ambos sobre2,3. S59,3Y9nov **4,627% /2,53**, no pertenece al universo V01-03. Emisión16nov no convierte subastas anteriores al corte base en nuevas adjudicaciones W47. S60: UST10Y13/16/17/18/19nov **5,15/5,12/5,10/5,07/5,04%**; cinco observaciones no acreditan más de diez sesiones de persistencia.

S09: Nasdaq Composite **−5,00% del13 al19nov**, sin cierre20nov recuperado. No es semana completa ni caída ininterrumpida:18nov sube. S10 describe conexiones deuda/valoraciones IA/no bancos y mantiene como contrapeso resistencia bancaria. Su ejemplo de venta forzada Situational Awareness corresponde a **julio**, no nueva liquidación semanal. S11 expone deuda y obligaciones fuera de balance; previsión de deuda de siete grandes emisores >800 BUSD antes de fin de año sigue siendo **proyección**. Mecanismo de vulnerabilidad no equivale a impago generalizado actual.

### 2.2. NVIDIA: negocio, cobro y exposición contingente

S12 registra8-K17nov; anexos aportados como *furnished*, estados S13 **no auditados**. S14 anuncia presentación del10-Q en semanas siguientes: no se recupera un10-Q nuevo que cierre las lagunas.

S13: ingresos trimestrales **115.844 MUSD**, beneficio65.287 y flujo operativo48.253. Cuentas por cobrar81.033 al25oct frente38.466 al25ene; inventario39.724 frente21.403: comparación de balances, no variación trimestral. Tres clientes directos son14%+11%+11% =**36% del trimestre**; cuatro13%+12%+12%+11% =**48% de nueve meses**. No hay nombres ni se sustituye la medición por61% de otro relato/periodo. Crecimiento y caja son contrapesos; concentración y cobros requieren seguimiento. No prueban ventas ficticias ni cobro final de cada operación.

S14 distingue **518 BUSD de compromisos estratégicos plurianuales**,32 adicionales condicionados a financiación/despliegue/aceptación y **118 BUSD de exposición máxima bruta en garantías**. Dentro de estas,105 corresponden a apoyo SB Energy pactado en agosto, activado por fases; primera esperadaFY2029. No hay pagos por garantías declarados al25oct. No sumar perímetros como deuda exigible, pérdida o caja consumida. Guía Q4FY2027 **130 BUSD±3%**, prospectiva y sin cómputo Data Center de China.

Hipótesis a probar: financiación del cliente → despliegue/aceptación → compra/cobro → obligaciones o garantías del proveedor. Las pruebas decisivas son caja por contraparte, condiciones, garantías exigidas y cancelaciones. Documentar la red mejora el mecanismo; no acredita su colapso.

### 2.3. Anthropic: cierre efectivo y composición de fondos

S15 es folleto; S16 acredita **cotización19nov y cierre20nov**, con opción completa. Se supera W46/oferta condicionada. Para cantidades finales prevalece cierre sobre escenario base.

| Tramo cerrado | Acciones | Bruto aritmético a83 USD | Destinatario |
|---|---:|---:|---|
| OPV primaria | 1.103.351.354 | 91.578.162.382 USD | Anthropic |
| OPV secundaria | 23.648.646 | 1.962.837.618 USD | Accionistas vendedores |
| OPV total | 1.127.000.000 | 93.541.000.000 USD | Ambos tramos |
| Privada concurrente | 313.253.007 | 25.999.999.581 USD | Anthropic |

Secundario: **2,10% de acciones OPV**. Bruto conjunto incluido secundario≈119.541 millones USD; de la sociedad primaria+privada≈117.578 millones. Antes de comisiones/gastos: no efectivo neto libre ni retorno de inversión. Estimación neta del folleto no es neto final auditado. S16 identifica proveedores entre compradores privados.

**Inferencia:** financiación efectiva y vínculos proveedor/cliente permiten estudiar dependencia y concentración. La composición limita la lectura de salida principalmente destinada a socios y el agotamiento general del capital privado. No demuestra rentabilidad futura de infraestructura. Esas proposiciones necesitan pruebas distintas.

### 2.4. CAPEX: comparar emisores antes de agregar

Cuatro documentos de octubre: **antecedentes recontrastados**, no noticias W47. Evitan convertir un operador en recorte agregado.

| Emisor /fuente | Periodo/base | Dato | Guía/comparación | Límite |
|---|---|---|---|---|
| Microsoft S17 | Q1FY2027 termina septiembre; leases al inicio | Capex45,2 BUSD; leases7,4; caja PPE39,4 | Calendario2026≈170; Q2 esperado>50; retrasos de terceros | Guía no ejecución; no causa única ni yields CoWoS. |
| Amazon S18 | Doce meses hasta septiembre; caja | PPE bruto215,192 BUSD; ventas/incentivos4,535; neto210,657; FCF−42,4 | Guía anual homogénea previa/actual no recuperada | TTM realizado no sumable a guía calendario ajena. |
| Alphabet S19 | Q3 calendario y guía anual | Capex51,4 BUSD | 2026 195–205, mantenida | Guía anual no desviación trimestral. |
| Meta S20 | Q3; incluye principal de finance leases | Capex34,91 BUSD | 2026 135–145 frente130–145; punto medio+1,82% | Suelo mayor no recorte; definición distinta de Microsoft. |

**C-C/V03-01 siguen sin agregado comparable.** Falta universo fijo, guías del mismo trimestre, criterio leases/caja, perímetro y atribución física. Una suma heterogénea no responde al trigger. La comparación contiene contrapesos a contracción uniforme, sin descartar retrasos concretos.

### 2.5. V02: electricidad, gas y transporte

S24: pausa de solicitudes legislativas CPD/subestaciones aprobada17nov, hasta doce meses y retroactiva15sep, con excepciones. Proceso administrativo distinto. No acredita moratoria energética o conexión denegada a IA>50MW. Fricción urbanística sí; conservar su ámbito.

S25: propuesta PJM sobre comportamiento ante perturbaciones de grandes cargas, subgrupo computacional desde25MW; vigencia solicitada16ene2027, sin aprobación acreditada. S27 resume propuestas MISO de costes/garantías16nov. S26 describe procedimiento FERC, no resultados. S28 acredita comentarios NERC por índice PJM, sin texto recuperado. No convertir pasos en obligación de corte>=4h.

S31 Campbell51, emitida13nov, **efectiva15nov–12feb2027**. S30 Wagner25B, emitida17nov, **18nov–31dic**. S29 Eddystone52, emitida20nov, **21nov–18feb2027**: disponibilidad/despacho en horas necesarias; información de disponibilidad para5dic. **V02-05 activo jurídico**, operación diaria separada. No se han contrastado todos los informes ni G-C/G-D completos.

S32 Alemania: **57,1% /141,4 TWh** almacenado; flujos tubería12–18nov19,1 TWh, GNL2,1. Regulador describe suministro estable y riesgo bajo. Colchón bajo y alivio de flujos coexisten. No extrapolar a toda UE, racionamiento o renta de cada hogar español.

S33: **138 incidentes/25 fallecidos acumulados al17nov**. Daño AL DHANNAH15nov no prueba VLCC/LNG crítico en corredores definidos. Incidente13nov es anterior al corte base, aunque se lea ahora. Acumulado no es ataques semanales ni medición de primas, tráfico14d o capacidad de terminal. Esas lagunas permanecen.

### 2.6. V03/V04: capacidad y acceso jurídico

S21 ASML:113 sistemas litográficos nuevos vendidosQ3; mezcla tecnológica, no113EUV ni producción anual industrial. Capacidad futura2027/28 no distribución de lead times. S22 SK hynix comunica HBM/contratos futuros; S23 es demostración. No yields auditados, plazo de todo hardware ni comercialidad sub5nm sin equipos occidentales.

S34 China48: consulta hasta15nov y preregistro transitorio vinculado a futuro catálogo. **Fin de consulta no significa expiración ni texto final acreditado**; anexos WPS sin auditar. S35–S37 confirman entrada18nov de49/drones,50/maquinaria de túneles y51/dragas. Licencias y, en50, diferencias por destino; no prohibición mundial indiferenciada ni extensión automática de48. Faltan expedientes/entregas.

S38 anuncia16nov; S39 publica y hace efectiva **19nov** regla BIS sobre acceso remoto a cómputo significativo: entidades D:5/Macao y requisitos en Indonesia, Malasia, Singapur, Tailandia y Brasil, con excepciones/transición90d para determinadas operaciones existentes. Comentarios hasta **19ene2027**. No prohibición inmediata de toda nube ni bloqueos ejecutados. Primario **V04/acceso comercial**; objeto técnico nuevo V03-03 todavía parcial. C23 incorporado con calibración aprobada y aplicada, sin duplicarlo; OISP/C50 distinto.

S52 recontrasta modificación canadiense efectiva30oct: retira partidas y añade otras al50%; jurídico V04-01, no T-A material completo. S51 resume **27.600 millones CAD** de cobertura y varias tasas; tabla informativa sin sanción oficial. CAD no USD, cobertura no recaudación; faltan Gazette/actos/neutralizaciones. T-B heredado con revalidación parcial. S53 calendario no aporta datos sectoriales; S54 no atribución causal requerida.

### 2.7. V05: producción no equivale a productividad

S41 publica16nov sobre **septiembre**: industria eurozona+0,2% mensual/−1,5% anual; UE+0,5%/−0,8%. Agosto revisado, sin reconstruir diferencia contra original no recuperado. Índice no salida neta CAPEX, productividad o daño arancelario atribuible a fabricantes.

S42 publica17nov sobre **octubre**: valor añadido industrial chino+4,8% real anual; **82.846 robots industriales producidos,+26% anual**; enero–octubre874.141,+32,3%. Servicios−4,9% octubre: no expansión de todo robot. Producción no instalaciones Unitree, horas productivas, sustitución laboral o productividad cliente.

S43, antecedente27oct:10.565.782 pensiones,≈9,6 millones de personas, nómina mensual14.540 MEUR. Denominadores distintos. No anualizar nómina para probar déficit neto>2%PIB ni combinar afiliación de otro periodo para ratio<1,4 durante ejercicio completo. S44 matriculaciones por propulsión/territorio no cierra origen importado/cuota sostenida6meses.

V05 tiene evidencia recuperable C3/C4/C5/C24/C25/C26 pese a cero fichas. Próxima prueba útil: cliente/planta/tarea/horas/fallos/recompra, inversión física neta por jurisdicción y cuentas personas/año. Cero carga no significa cero riesgo.

### 2.8. V06: avance institucional y ejecución

S48 confirma bilateral19nov. S49/S50, cumbre EE.UU.–Rusia–China enShenzhen19nov y declaración: reforma ONU, intención de aumentar refinados, inmunidades/jurisdicción y diálogo nuclear. No volumen, calendario de entrega, base militar o presupuesto ejecutado. Mismo texto publicado por dos participantes corrobora existencia/contenido, no dos análisis independientes de efectos.

**Inferencia:** mayor interlocución institucional; probar actos/flujos. No acredita nuevo orden operativo, cada compromiso bilateral, aumento material de suministro o eliminación de rivalidad. X01/APEC21nov sin hora acreditada queda fuera; no hace falta para acreditar cumbre19nov.

S45 calendario español; campaña/elección futura no bloqueo fiscal realizado. X02/AIReF localizado en extracto, documento no leído por error de acceso: cifras no consolidadas. S46 confirma candidaturas Hernández de Cos/Klaas Knot y procedimiento, sin nombramiento ni preferencias nacionales probadas. S47: salida7feb2027, fuera de20ene; selección anterior necesita fecha propia.

S55 acredita lanzamiento Pontes y participación inicial, superior a mero concepto; no serie de volumen/eficiencia/demanda neta nueva. S56 convocatoria ETSG hasta27nov, no estándar aprobado. Alimentan V01/T05, no los umbrales comerciales no-USD V04/V06.

## Condiciones y cobertura

24 condiciones de eventos y25 de vectores conservadas íntegras. Siete seguimientos cualitativos actualizados; altaC23 añade pruebas cualitativas propias. E1 heredadas no pierden procedencia porque falte revalidación semanal de algún sensor. Tablas canónicas en las fichas y vectores; detalle de esta revisión:

### 24 condiciones de eventos

Formulaciones extraídas del bloque vigente de cada ficha; no se rebajan para acomodar resultados. Las E1 conservan procedencia: no revalidar una condición esta semana no borra un episodio anterior.

### Grid — seis condiciones

| ID | Condición vigente | Evaluación W47 | Evidencia y requisito pendiente |
|---|---|---|---|
| G-A | Moratoria energética oficial o denegación de conexiónLoudoun,CPDIA>50MW. | **PARCIAL** | Pausa urbanística aprobada con excepciones; no demuestra el acto energético requerido. Faltan denegación/moratoria eléctrica, proyecto IA y potencia >50 MW unidos causalmente. Fuentes: S24. |
| G-B | PJM/ERCOT EEA≥2 por climatización yCPD en pico estival. | **NO VERIFICABLE** | Las reformas y órdenes de noviembre no resuelven el sensor retrospectivo estival. Faltan registro EEA>=2, operador, pico de verano y causalidad conjunta climatización/CPD. Fuentes: S25,S29,S30. |
| G-C | Orden vinculanteDOE/FERC/RTO/ISO aCPD/grandes cargas>50MW o generación asociada, autogeneración/corte≥4h. | **PARCIAL** | Hay órdenes de fiabilidad y propuestas sobre grandes cargas; son categorías jurídicas diferentes. No acreditados conjuntamente destinatario >50 MW/generación asociada y obligación de autogeneración/corte >=4 horas. Fuentes: S25,S27,S29,S30,S31. |
| G-D | Curtailment forzoso efectivoOfgem/EirGrid,CPDIA comerciales operativos>100MW combinados. | **NO VERIFICABLE** | MPID345 permanece como antecedente de la base; no se recupera ejecución nueva compatible. Ofgem/EirGrid, CPD IA comerciales operativos, >100 MW combinados y corte forzoso ejecutado. Fuentes: —. |
| G-E | Moratoria hídricaEspaña/Irlanda bloquea licenciaCPDIA>50MW. | **NO VERIFICABLE** | El permiso urbanístico de otro país no prueba la condición hídrica. Acto hídrico España/Irlanda, bloqueo de licencia, proyecto IA y >50 MW. Fuentes: —. |
| G-F | Sanción/demandaCE desdeEED demuestraWUEsectorialmedioUE>0,5L/kWh. | **NO VERIFICABLE** | No recuperada actuación CE compatible ni media sectorial WUE. Sanción/demanda EED y media UE >0,5 L/kWh con universo y periodo definidos. Fuentes: —. |

### Japón/liquidez — cinco condiciones

| ID | Condición vigente | Evaluación W47 | Evidencia y requisito pendiente |
|---|---|---|---|
| J-A | JGB30Y>UST30Y cubiertoJPY>15d hábiles consecutivos y2meses de ventas/no reinversión institucional exterior. | **PARCIAL** | Flujo semanal vendedor; TIC es otra frecuencia/población. No hay conjunción íntegra. Diferencial JGB30Y/UST30Y cubierto JPY durante >15 días hábiles y dos meses institucionales comparables. Fuentes: S05,S06. |
| J-B | Impuesto15sep→TGA>900BUSD y reservas<3,1TUSD en misma quincena. | **NO VERIFICABLE** | Los niveles actuales no completan retrospectivamente la ventana fiscal de septiembre. Misma quincena del impuesto 15 sep, series compatibles y causalidad impuesto→TGA/reservas. Fuentes: S04. |
| J-C1 | SOFR−IORB>8pb durante3d hábiles consecutivos. | **NO ACTIVADO EN COBERTURA** | El cálculo de cinco sesiones recuperadas no supera el umbral en ninguna. Falta sesión 20 nov; no extrapolar al resto de instrumentos o al futuro. Fuentes: S01,S02,S03. |
| J-C2 | Alternativamente, dispersiónGCp99>25pb. | **NO VERIFICABLE** | SOFR es mediana; no mide la alternativa GCp99. Benchmark y dispersión GCp99 >25 pb con definición compatible. Fuentes: S01. |
| J-D | SRF>20BUSDdiarios>2d consecutivos alrededor25–30sep. | **NO VERIFICABLE** | El agregado repo de H.4.1 no reconstruye la serie SRF diaria de septiembre. SRF >20 BUSD/día durante >2 días consecutivos alrededor 25–30 sep. Fuentes: S04. |

### CoWoS — cuatro condiciones

| ID | Condición vigente | Evaluación W47 | Evidencia y requisito pendiente |
|---|---|---|---|
| C-A | Anuncio oficialAP7Chiayi retrasa equipamiento/conexión y producción más alláH1-2027. | **NO VERIFICABLE** | Los datos comerciales de otros proveedores no fijan el calendario AP7. Anuncio oficial Chiayi/AP7: equipamiento/conexión y producción después de H1-2027. Fuentes: S21. |
| C-B | YieldsCoWoS-L causan entregasBlackwell20%bajo guíaQ4-2026. | **PERIODO INCOMPLETO** | El Q4 calendario sigue abierto; Q3 FY2027 no es ese periodo ni Blackwell aislado. Entregas/guía comparable, déficit del 20% y causalidad yields CoWoS-L. Fuentes: S12,S13,S14. |
| C-C | Recorte agregado>10%de guíaCAPEXhyperscalersQ3/Q4 señala freno físico en aceleradores. | **NO VERIFICABLE** | La comparación por emisor aporta contrapesos; no forma agregado homogéneo ni demuestra freno físico. Universo fijo, guía Q3/Q4 previa y actual, criterio leases/caja y causa física del recorte >10%. Fuentes: S17,S18,S19,S20. |
| C-D | Sobrecapacidad/contracción de pedidos→plazoCoWoS<20semanas generalizado. | **NO VERIFICABLE** | Capacidad futura y acuerdos de memoria no constituyen serie de plazos CoWoS. Plazo <20 semanas generalizado y causa sobrecapacidad/contracción de pedidos. Fuentes: S21,S22. |

### Marítimo — cuatro condiciones

| ID | Condición vigente | Evaluación W47 | Evidencia y requisito pendiente |
|---|---|---|---|
| M-A | Dos brokers independientes/circularLMA prima≥1,5%casco mismo corredor, o retirada/denegación≥48h. | **NO VERIFICABLE** | Incidentes documentados no son cotizaciones de seguros. Dos brokers independientes/circular LMA, nivel >=1,5% casco mismo corredor; o retirada/denegación >=48 h. Fuentes: S33. |
| M-B | Ataque y hundimiento/daño estructural críticoVLCC oLNG enOrmuz/Bab. | **PARCIAL** | Nuevo daño a buque en el registro; no se completa población/gravedad/corredor. VLCC/LNG, Ormuz/Bab y hundimiento o daño estructural crítico tras ataque. Fuentes: S33. |
| M-C | Declaración oficial de saturación de puertos africanos que impide bunkering desviado. | **NO VERIFICABLE** | No recuperada declaración oficial compatible. Saturación de puerto africano que impida bunkering de desvíos, no mera congestión o flete alto. Fuentes: —. |
| M-D | Cierre parcialOrmuz paraliza>5Mb/d del suministro delGolfo durante>48h. | **NO VERIFICABLE** | Registro de incidentes no mide paralización de suministro por cierre. Ormuz parcialmente cerrado, >5 Mb/d del Golfo paralizados y >48 h. Fuentes: S33. |

### Tariff Stack — cinco condiciones

| ID | Condición vigente | Evaluación W47 | Evidencia y requisito pendiente |
|---|---|---|---|
| T-A | Aplicación material50%vehículos/alcohol/lácteosCanadá, sin neutralización. | **PARCIAL** | Texto jurídico recontrastado; las modificaciones de partidas no equivalen a cobro completo. Perímetros vehículos/alcohol/lácteos, aplicación material 50% y ausencia de neutralización. Fuentes: S52. |
| T-B | Contramedidas vinculantesCanadá/Brasil/UE>10.000M$comercioanual. | **ACTIVO HEREDADO; REVALIDACION PARCIAL** | Se conserva procedencia W45/W46. Resumen canadiense aporta cobertura nominal, con límite jurídico/divisa. Actos vinculantes consolidados y comercio anual >10.000 MUSD conciliado. No nueva activación/desactivación por silencio. Fuentes: S51. |
| T-C | Dos fabricantes afectados cuantifican>5%costeunitario/margenbruto/producción o relocalización física atribuible. | **NO VERIFICABLE** | No recuperados dos fabricantes con cuantificación y atribución compatibles. Dos afectados, >5% en métrica requerida o relocalización física atribuible a aranceles. Fuentes: —. |
| T-D | Importaciones de sectores cubiertos−15%YoYdurante2meses consecutivos,Census/BEA. | **NO VERIFICABLE** | Septiembre ya estaba publicado; el calendario no entrega las celdas sectoriales. Partidas de sectores cubiertos, comparación YoY homogénea y dos meses consecutivos -15%. Fuentes: S53. |
| T-E | Fuenteoficial atribuye≥0,3ppdeinflaciónYoYbienesbásicos a nuevos aranceles en2publicaciones. | **NO VERIFICABLE** | La publicación de CPI no acredita atribución causal oficial a nuevos aranceles. >=0,3 pp YoY en bienes básicos en dos publicaciones oficiales con ese nexo. Fuentes: S54. |

### Siete seguimientos cualitativos

No se inventan umbrales retrospectivos. Se conservan sus criterios cualitativos, incluidos alivio y falsación.

| Ficha | Evidencia y lectura | Próxima prueba / límite | Fuentes |
|---|---|---|---|
| EE. UU.–China / ejecución | La bilateral y nueva cumbre sí ocurrieron. La ejecución de compromisos comerciales sigue siendo otro objeto. | Comprobar acto, partida, licencia, contrato y flujo; no elevar clase por una foto ni por declaración conjunta. | S40,S48,S49,S50 |
| Deuda francesa | Nueva curva y adjudicación aportan financiación efectiva en subasta; falta liquidación y transmisión bancaria. | Seguir spread OAT–Bund, cobertura de vencimientos comparables, ejecución fiscal y exposición bancaria. No usar TEC30 para el trigger a diez años. | S07,S08,S10 |
| Gas europeo / invierno | La evidencia alemana combina colchón bajo con suministro considerado estable por el regulador. | Desagregar país, gas day, flujos, clima, precio y restricciones. Ni racionamiento europeo ni normalización de toda Europa quedan demostrados. | S32 |
| Registro tecnológico China48 | La consulta terminó según calendario, pero no se recuperó texto final. Las vigencias de49–51 son instrumentos separados. | Preregistro transitorio no expira automáticamente el15nov; verificar norma final, ámbito/anexo y expediente de transferencia. | S34,S35,S36,S37,S40 |
| NVIDIA / sucesión y continuidad | Kress firma todavía como CEO interina/CFO. Primera prueba de resultados realizada; no resuelve por sí sola sucesión ni continuidad por cliente. | Cuatro familias: mandato; roadmap/entregas; resultados/guía; continuidad corroborada y sucesión resuelta. No atribuir retraso físico al relevo sin nexo. El 10-Q sigue pendiente en documentación recuperada. | S12,S13,S14 |
| España / gobernabilidad fiscal | Campaña en curso y calendario legal recontrastados. No se acredita nuevo gobierno, presupuesto o bloqueo material. | Separar diagnóstico fiscal previo de efecto de elección futura. Documento completo AIReF no recuperado; no consolidar sus cifras indexadas. | S45,X02 |
| Ajuste de valoraciones IA / transmisión financiera | Hay nueva evidencia de precios, capital y exposición contractual, junto a captación efectiva y caja operativa positiva del proveedor. | Cuatro familias: precios; financiación/garantías; inversión/caja; alivio/salida. Falta default o margin call generalizado atribuible; no sumar exposiciones máximas como pérdidas actuales. | S09,S10,S11,S13,S14,S15,S16 |

### 25 condiciones de vectores

Una condición vectorial puede estar jurídicamente activa sin completar población, duración o causalidad de un evento. Canales secundarios no duplican carga.

| ID | Condición vigente | Evaluación y límite | Fuentes |
|---|---|---|---|
| V01-01 | Spread de liquidez interbancaria > 15 bps durante 5 días hábiles consecutivos. | **NO ACTIVADO EN COBERTURA**. El proxy SOFR−IORB recuperado permanece bajo umbral; otros spreads no auditados. | S01,S02 |
| V01-02 | Uso de facilidades de repo de emergencia > $50 B sostenido por más de 5 días hábiles. | **NO VERIFICABLE**. Repo semanal muy bajo no sustituye la serie diaria completa de facilidades de emergencia >5 días. | S04 |
| V01-03 | Ratio de cobertura (bid-to-cover) en subastas de deuda a 10 Y/30 Y < 2.3 en dos emisiones sucesivas. | **NO ACTIVADO EN MUESTRA**. Las dos subastas UST elegibles recuperadas no bajan de 2,3; 3Y no es elegible. No certifica todo soberano/emisión. | S57,S58,S59 |
| V01-04 | Rendimiento del bono soberano de referencia a 10 años > 5% sostenido por más de 10 días de negociación. | **PARCIAL**. UST10Y supera 5% en las cinco sesiones visibles; Francia no. Falta demostrar >10 sesiones consecutivas. | S07,S60 |
| V02-01 | Incremento de las primas de seguro de guerra marítimo > 0.5% del valor del buque por tránsito. | **NO VERIFICABLE**. No hay serie homogénea de incremento de prima por tránsito; distinta de nivel de M-A. | S33 |
| V02-02 | Caída en el tránsito de buques energéticos en chokepoints > 20% en promedio móvil de 14 días. | **NO VERIFICABLE**. Falta tráfico de buques energéticos y promedio móvil 14 días por chokepoint. | S33 |
| V02-03 | Daño estructural físico confirmado en terminales clave de exportación que reduzca la capacidad global en > 1 M bpd. | **NO VERIFICABLE**. Daño a buque no acredita terminal ni pérdida de capacidad global >1 Mb/d. | S33 |
| V02-04 | Desvío de más del 30% del volumen nominal del tráfico naviero regular hacia rutas alternativas de larga distancia. | **NO VERIFICABLE**. Falta denominador nominal y volumen >30% desviado a rutas largas. | — |
| V02-05 | Orden 202(c), EEA 3 o instrucción equivalente que obligue a despachar generación fuera de régimen ordinario, activar respaldo o interrumpir grandes cargas para preservar la fiabilidad del sistema. | **ACTIVO JURIDICO**. Órdenes vigentes de disponibilidad/despacho por fiabilidad. Operación efectivamente realizada se verifica aparte; no completa G-C. | S29,S30,S31 |
| V03-01 | Desviación trimestral > 15% en el guidance de inversión agregada de los hyperscalers de cómputo. | **NO VERIFICABLE**. No agregado trimestral homogéneo; no usar suma de guías anuales, TTM y gastos de caja. | S17,S18,S19,S20 |
| V03-02 | Aumento del lead time de hardware de cómputo avanzado por encima de las 24 semanas de forma generalizada. | **NO VERIFICABLE**. Comentarios de capacidad futura no prueban lead time generalizado >24 semanas. | S21,S22 |
| V03-03 | Publicación formal de restricciones de exportación sobre nuevos nodos litográficos o arquitecturas de hardware avanzado en registros regulatorios clave. | **PARCIAL**. Restricción formal de acceso remoto a cómputo; falta cotejo técnico que acredite nuevo nodo/arquitectura frente a ampliación de acceso/destinos. | S38,S39 |
| V03-04 | Evidencia técnica auditada de procesamiento comercial viable de obleas sub-5 nm en jurisdicciones restringidas sin el uso de equipos de litografía occidentales. | **NO VERIFICABLE**. Producción agregada de circuitos integrados no audita oblea comercial sub-5 nm sin litografía occidental. | S42 |
| V04-01 | Imposición de aranceles extraordinarios > 20% en sectores industriales estratégicos en economías líderes. | **ACTIVO JURIDICO HEREDADO**. Parte dispositiva confirma aranceles extraordinarios; anexos/cobro íntegro no auditados. No completa T-A. | S52 |
| V04-02 | Desviación sostenida > 20% del índice de fletes de contenedores en comparación con su media móvil de 90 días. | **NO VERIFICABLE**. Falta serie de contenedores, media móvil 90 días y persistencia >20%. | — |
| V04-03 | Liquidación de operaciones comerciales sin dólares que superen los $50 B agregados anuales en una red bilateral verificable. | **NO VERIFICABLE**. Infraestructura/grupo de tokenización no acredita comercio bilateral no-USD >50 BUSD/año. | S55,S56 |
| V04-04 | Incremento > 30% interanual en la IED industrial hacia jurisdicciones puente (friend-shoring). | **NO VERIFICABLE**. Falta flujo de IED industrial y comparación YoY >30% en jurisdicción puente; stock no es flujo. | — |
| V05-01 | Desviación anual del déficit neto de previsión social > 2% del PIB en una economía del G 7 o eurozona. | **NO VERIFICABLE**. Nómina mensual no déficit neto anual sobre PIB; ejercicio 2026 no cerrado. | S43 |
| V05-02 | Caída del ratio de soporte demográfico por debajo de 1.4 cotizantes por pensionista sostenido durante un ejercicio fiscal completo. | **NO VERIFICABLE**. Faltan personas cotizantes/pensionistas comparables y ejercicio completo; prestaciones no personas. | S43 |
| V05-03 | Salida neta documentada de inversión corporativa (CAPEX de activos físicos) > $5 B anuales desde una jurisdicción industrial principal. | **NO VERIFICABLE**. IPI no salida neta de CAPEX físico transfronterizo anual >5 BUSD. | S41 |
| V05-04 | Penetración de mercado de plataformas manufacturadas importadas de nueva generación (ej. VE) superando el 25% de la cuota local de forma sostenida por 6 meses. | **NO VERIFICABLE**. Propulsión BEV/PHEV no demuestra origen importado ni cuota mantenida seis meses del universo requerido. | S44 |
| V06-01 | Volumen de liquidaciones comerciales no denominadas en la divisa hegemónica transaccionadas en plataformas alternativas superando los $100 B mensuales sostenidos. | **NO VERIFICABLE**. No volumen comercial no-USD mensual sostenido; tokenización europea no prueba esta condición. | S55,S56 |
| V06-02 | Aumento del presupuesto de defensa en economías de primer nivel > 15% interanual durante dos presupuestos consecutivos. | **NO VERIFICABLE**. Declaración de seguridad no dos presupuestos nacionales comparables >15% YoY. | S49,S50 |
| V06-03 | Adjudicación de concesión o uso militar de una base dual soberana en zonas de estrechos militares estratégicos. | **NO VERIFICABLE**. Cumbre/diplomacia no concesión o uso militar de base dual en estrecho. | S49,S50 |
| V06-04 | Congelación o incautación judicial y ejecutiva formal de activos de bancos centrales extranjeros que superen los $50 B en un solo decreto de sanción. | **NO VERIFICABLE**. Sin decreto individual compatible de congelación/incautación de banco central extranjero >50 BUSD. | S50 |

## Tesis revisadas

Rectificación interpretativa posterior al cierre factual: revisión de las seis tesis aprobada y aplicada el 22 de noviembre, TASK391. Los grados globales se conservan con alcance por afirmación; T06 añade soporte moderado para interdependencias financieras concretas. T03 vuelve al mecanismo residencial/fiscal. No altera los 13 eventos, la carga 171,76 ni el radar. [[REVISION_TESIS_2026_11_22]].



| Tesis | Soporte | Estado | Alcance | Próxima falsación |
|---|---|---|---|---|
| [[TESIS_01_Dominancia_Fiscal]] | moderado | vigente | Restricción fiscal y ejecución; dominancia monetaria no acreditada por la evidencia revisada | Intereses/ingresos, presupuesto/ejecución, refinanciación y reacción monetaria atribuible; comparar continuidad y ajuste sin subordinación. |
| [[TESIS_02_Frictionless_Stabilization]] | moderado_alto | vigente | Coerción selectiva; estabilización material por sector en validación; coordinación no acreditada | Acto/licencia y efecto sobre entrega/coste/plazo por producto y destino; comparar continuidad sin acuerdo e hipótesis sin coordinador. |
| [[TESIS_03_Captura_de_Renta]] | moderado | vigente | Contexto residencial y distributivo; contribución fiscal y causalidad conjunta en validación | Renta disponible real, esfuerzo residencial, ahorro y transferencias netas por cohorte/tenencia/territorio; desplazamiento de inversión con mecanismo. |
| [[TESIS_04_Multipolaridad_Logistica]] | moderado_alto | vigente | Vulnerabilidad y coste de resiliencia; reordenación logística ejecutada en validación | Servicio y coste total por corredor; capacidad alternativa utilizada; contratos y flujos persistentes para reordenación geopolítica. |
| [[TESIS_05_Tokenizacion_del_Colateral]] | moderado | en_validacion | Avance jurídico e infraestructural; uso recurrente y beneficio económico en validación | Mismo activo/riesgo/moneda: uso recurrente, coste/plazo total, fallos, origen de fondos y sustitución de tenedores. |
| [[TESIS_06_IA_como_silicio_y_energia]] | alto | vigente | Alto solo para dependencia física; interdependencia financiera moderado; restricción marginal y retorno por validar | Cuello marginal y entrega; contraparte/contrato/cobro/garantía; utilización, reposición y caja del operador; productividad útil del usuario. |

## Visión de Luis y contraste

Se revisaron16 documentos propios: cuatro transcripciones, seis publicaciones archivadas, dos borradores y cuatro punteros. Atribución documental, sin cotejo de audio ni verificación remota de cada publicación. No se transcriben borradores privados ni se incorporan rutas personales al repositorio público. Las lecturas son hipótesis para elegir pruebas; no otra fuente independiente que confirme el argumento.

| Lectura atribuida a Luis | Mecanismo / pregunta | Límite y prueba |
|---|---|---|
| La financiación del ecosistema puede sostener parte de su propia demanda. | Capital o garantías a cliente/proveedor → inversión y compra → cobro y nueva financiación. | Proporción de compras financiadas y demanda final independiente; no equiparar relación comercial e irregularidad. Conciliar contraparte, inversión, compra, aceptación, cobro y origen de fondos; considerar cliente que paga con caja operativa autónoma. |
| El éxito de captar capital no resuelve la rentabilidad y la reposición de infraestructura. | Obsolescencia/reposición + operación → necesidad de caja → retornos exigidos a aplicaciones. | 600.000/200.000 millones son cifras atribuidas a intervenciones, no agregado aquí validado. No presumir renovación anual de todo activo. Separar expansión/reposición, GPU/edificio/red, vida útil, utilización, margen y caja; fijar perímetro para evitar doble conteo de ventas entre capas. |
| Una revolución tecnológica puede coexistir con una burbuja o malos retornos financieros. | Utilidad y adopción reales no determinan por sí solas precio pagado ni captura del valor. | Ni precio bursátil prueba inutilidad ni mejora tecnológica prueba valoración razonable. Contrastar por separado calidad/coste de tarea, ahorro/ingreso del cliente y retorno/caja del inversor. |
| El relato y el calendario político pueden modular un ajuste; también puede operar la inercia del sistema. | Atención/expectativas y decisiones institucionales → valoración/acceso a financiación → ritmo del ajuste. | Interés en evitar una caída no demuestra coordinación/capacidad. P01 ofrece alternativa sin orquestación; no borrar ese matiz. Cronología comprobable, actos y canales; comparar explicación coordinada con resultados, tipos y dinámica de mercado sin coordinación. |
| La ventaja estratégica depende de cadena física y adopción industrial, más allá del relato o un nodo aislado. | Litografía/fabricación/energía + uso en planta → coste/calidad/productividad → competitividad y renta. | No acreditadas supremacía tecnológica total, oblea comercial sin equipos occidentales o eficacia nula de controles. Comparar por tecnología y tarea: entregas, energía, rendimiento, utilización, productividad y sustituibilidad; comprobar efectos de la regla. |
| Shenzhen puede expresar un desplazamiento del poder hacia el Pacífico y acuerdos entre grandes potencias. | Geografía productiva y coordinación soberana → acuerdos de acceso/seguridad → ejecución y capacidad de negociación. | Yalta2.0 es analogía. Reunión sin Europa no demuestra por sí sola reparto consumado ni desaparición de su poder industrial. Seguir acuerdos vinculantes, concesiones, acceso, rutas/flujo y compromisos europeos que alteren o contradigan el escenario. |
| Productividad, vivienda y política monetaria conectan la capacidad de crear valor con el acceso a renta y financiación. | Capital/productividad y oferta territorial → salario real/movilidad; gobernanza monetaria → coste de financiar transición. | Ratios residenciales y salariales requieren denominadores; respaldo político inferido no nombramiento BCE. Renta/horas/cohorte/territorio comparables y oferta ejecutada; nombramiento/decisión monetaria y transmisión observada. |

La financiación circular es una pregunta sobre contrapartes/caja, no ingreso ficticio demostrado. La captación de capital no resuelve ROI; una revolución tecnológica puede coexistir con sobrevaloración. La explicación de ajuste coordinado conserva la alternativa de inercia/endogeneidad expresada por Luis. Shenzhen no acredita reparto consumado ni desaparición del poder europeo.

## Radar actualizado

**34 hitos abiertos (1 Régimen / 0 Crítico / 28 Elevado / 5 Latente), seis observatorios y 73 resoluciones acumuladas.** Horizonte21-nov-2026–20-ene-2027 inclusive (+60d). Retirados13 vencidos (11 MATERIAL, dos NO VERIFICABLE; coberturas parciales explícitas), admitidos12. Dos ventanas intersectan el horizonte y conservan sus límites íntegros. Cero ventanas enriquecidas.

Detalle en [[Radar_Eventos_2026_11]]; tres rectificaciones de subastas previas conservan IDs, sin añadir tres resoluciones. Revalidación de calendarios al redactar sin traer resultados posteriores al corte. Publicaciones de los mismos textos políticos no son confirmaciones independientes.

## Calibración C23 aprobada y aplicada

Luis respondió «Si» a la propuesta concreta presentada22nov: E0/V04, presión3, peso4,30, tendencia→/factor1 y carga12,90. La autorización completa los parámetros que habían quedado ND en la aplicación anterior; no reabre A ni la selección de inventario.

| Parámetro | Aplicado22nov | Fundamento conservado |
|---|---|---|
| Clase / primario | E0 / V04 | Seguimiento de acceso jurídico-comercial; no shock físico demostrado |
| Presión | 3 | Restricción efectiva y cumplimiento transfronterizo; denegaciones/efectos materiales aún no acreditados. Juicio ordinal |
| Peso estructural | 4,30 | A5/T4/S4/D4: 0,30×5 + 0,30×4 + 0,20×4 + 0,20×4; alcance, transmisión, sustitución y persistencia |
| Tendencia / factor | → / 1 | Sin serie que demuestre aceleración/alivio; neutralidad calibrada aprobada |
| Carga primaria | 12,90 | 3 × 4,30 × 1; única imputaciónV04 |

V04=7,00+16,40+12,90=36,30. Total=158,86+12,90=171,76; puente respectoW46:160,16−1,30 de pesos+12,90 del alta. Los parámetros son juicios ordinales aprobados, no probabilidades o validación empírica. La actualización queda cerrada localmente como precierre W47; publicación autorizada por Luis22nov; la recepción remota se documenta por separado. La propuesta previa y el estadoND quedan trazados en COMM y respaldo fechado, sin reescribir sus recibos históricos.

## Límites y estado de cierre

Precierre, no observación completa del domingo22. Falta20nov en series recuperadas, diferencial cubierto, GCp99/SRF completos, primas comparables y varios expedientes/efectos. APEC21nov sin hora excluido; AIReF y SPP sin contenido primario completo no se consolidan. Fuentes fechadas antes del corte distinguen publicación nueva de periodo pasado y antecedentes recuperados. Las consultas posteriores no renuevan el corte.

Aplicación autorizada, calibración C23 y reconciliación local realizadas; actualización cerrada localmente como precierre W47. Publicación autorizada por Luis22nov; la recepción remota se documenta por separado. InformeW46 conserva archivo original fechado. Sin escribirD:, tocar índice/staging/HEAD o los siete históricos MM. Snapshot/Dashboard solo actualizan sus referencias/bloques231.

## Fuentes y reproducibilidad

Catálogo heredado de la investigación:60 fuentes externas más ocho relecturas complementarias. Consulta inicial21nov; revalidaciones de calendario22nov identificadas en reciboCOMM, sin afirmar inmutabilidad histórica de páginas dinámicas. No se considera auditoría exhaustiva de anexos, emisores o mercados.

| ID | Fuente primaria | Publicación | Periodo | Alcance |
|---|---|---|---|---|
| S01 | [FRED/NY Fed — SOFR](https://fred.stlouisfed.org/series/SOFR) | 2026-11-20 | sesiones 13 y 16–19 nov | Cinco observaciones visibles; falta sesión 20 nov. |
| S02 | [FRED/Fed — IORB](https://fred.stlouisfed.org/series/IORB) | 2026-11-20 | tipo administrado vigente en sesiones contrastadas | Distinguir tipo anunciado de observación futura de mercado. |
| S03 | [Fed — Implementation Note](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a1.htm) | 2026-10-28 | vigencia desde 29 oct | Antecedente de política; no decisión nueva de noviembre. |
| S04 | [Fed — H.4.1](https://www.federalreserve.gov/releases/h41/Current/) | 2026-11-19 | promedio semana terminada 18 nov y posición de miércoles | Tablas fechadas; URL móvil. Repo agregado no serie diaria íntegra de SRF. |
| S05 | [MOF Japón — flujos semanales de valores](https://www.mof.go.jp/english/policy/international_policy/reference/itn_transactions_in_securities/week.pdf) | 2026-11-19 | 8–14 nov; revisión 1–7 nov | PDF y tabla inspeccionada visualmente; unidad 100 millones JPY; URL móvil. |
| S06 | [US Treasury — TIC September](https://home.treasury.gov/news/press-releases/sb0693) | 2026-11-18 | septiembre 2026 | Publicación nueva sobre periodo atrasado; custodia no titular último. |
| S07 | [Banque de France — indices obligataires](https://www.banque-france.fr/fr/statistiques/taux-et-cours/indices-obligataires-2026-11-20) | 2026-11-20 | 16–20 nov; comparación con 13 nov de la base | TEC10 de vencimiento constante; no spread OAT–Bund. |
| S08 | [AFT — adjudicación OAT medio plazo](https://www.aft.gouv.fr/fr/publications/communiques-presse/19-novembre-2026-emission-oat) | 2026-11-19 | subasta 19 nov; liquidación prevista 23 nov | Resultados iniciales; no incorpora necesariamente ONC2 ni acredita liquidación futura. |
| S09 | [FRED/Nasdaq — Nasdaq Composite](https://fred.stlouisfed.org/series/NASDAQCOM) | 2026-11-20 | cierres 13 y 16–19 nov | Cobertura parcial hasta 19 nov; no retorno de semana completa. |
| S10 | [BCE — Financial Stability Review](https://www.ecb.europa.eu/press/financial-stability-publications/fsr/html/ecb.fsr202611~e03b919d36.es.html) | 2026-11-18 | evaluación noviembre; algunos episodios retrospectivos | Lectura dirigida a IA, soberano y no bancos; no auditoría exhaustiva del informe. |
| S11 | [Fed — Michael Barr sobre IA y estabilidad financiera](https://www.federalreserve.gov/newsevents/speech/barr20261116a.htm) | 2026-11-16 | estimaciones vigentes y proyecciones de cierre de año | Discurso de supervisor; distinguir estimación, proyección y pérdida realizada. |
| S12 | [NVIDIA — 8-K Item 2.02](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000088/nvda-20261117.htm) | 2026-11-17 | trimestre terminado 25 oct; firma 17 nov | 8-K registrado; anexos 99.1/99.2/99.3 furnished; no 10-Q auditado. |
| S13 | [NVIDIA — supplemental financial information](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000088/supplementalfinancialinfor.htm) | 2026-11-17 | Q3 FY2027 y nueve meses; balances 25 oct/25 ene | Estados suplementarios no auditados; clientes directos anónimos. |
| S14 | [NVIDIA — CFO commentary](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000088/q3fy27cfocommentary.htm) | 2026-11-17 | Q3 FY2027; compromisos al 25 oct; guía futura | Tablas de compromisos y garantías; información de dirección y contingencias, no pérdida pagada. |
| S15 | [Anthropic — folleto definitivo 424B4](https://www.sec.gov/Archives/edgar/data/2130357/000162828026074944/anthropicpbc-424b4.htm) | 2026-11-19 | oferta base y escenarios con opción | Folleto no equivale a cierre; para cantidades finales prevalece S16. |
| S16 | [Anthropic — cierre OPV y colocación privada](https://www.anthropic.com/news/ipo-close) | 2026-11-20 | cotización desde 19 nov; cierre 20 nov | Cierre confirmado por emisor; importes brutos antes de costes, no efectivo libre auditado. |
| S17 | [Microsoft — llamada Q1 FY2027](https://www.microsoft.com/en-us/investor/events/fy-2027/earnings-fy-2027-q1) | 2026-10-28 | trimestre terminado septiembre; guía calendario 2026/FY2027 | Capex con reconocimiento de leases y caja PPE diferenciados; guía de dirección. |
| S18 | [Amazon — Q3 2026 results](https://ir.aboutamazon.com/news-release/news-release-details/2026/Amazon-com-Announces-Third-Quarter-Results/) | 2026-10-29 | Q3, nueve meses y doce meses móviles al 30 sep | PPE/FCF de caja; guía anual comparable no recuperada en este contraste. |
| S19 | [Alphabet — llamada Q3 2026](https://abc.xyz/investor/events/event-details/2026/2026-Q3-Earnings-Call-2026-Ujou16CTw9/default.aspx) | 2026-10-28 | Q3 calendario y guía anual 2026 | Capex y guía de dirección; antecedente, no publicación W47. |
| S20 | [Meta — Q3 2026 results](https://investor.atmeta.com/investor-news/press-release-details/2026/Meta-Reports-Third-Quarter-2026-Results/default.aspx) | 2026-10-28 | Q3 y guía anual calendario 2026 | Capex incluye principal de finance leases; comparación por emisor. |
| S21 | [ASML — Q3 2026 results](https://www.investor.asml.com/news-releases/news-release-details/asml-reports-eu11.7-billion-total-net-sales-and-eu5.0-billion-net-income-q3-2026) | 2026-10-14 | Q3; expectativas capacidad 2027–2030 | Total de sistemas litográficos no igual a EUV; expectativas no lead time medido. |
| S22 | [SK hynix — Q3 2026 results](https://news.skhynix.com/en/q3-2026-business-results/) | 2026-10-28 | Q3; acuerdos capacidad futura | Anuncio empresarial de HBM/contratos; no auditoría técnica de yields. |
| S23 | [SK hynix — SC26 AI/HPC exhibition](https://news.skhynix.com/en/sc26-ai-hpc-exhibition/) | 2026-11-20 | presentación SC26 | Demostraciones; no medición de volumen productivo, pedidos o plazos. |
| S24 | [Loudoun — pausa de solicitudes CPD/subestaciones](https://sheriff.loudoun.gov/Archive/ViewFile/Item/15495) | 2026-11-18 | decisión 17 nov; aplicación retroactiva 15 sep | Comunicado PDF oficial: proceso urbanístico con excepciones; no moratoria energética. |
| S25 | [PJM — filing ER27-522-000](https://www.pjm.com/-/media/DotCom/documents/ferc/filings/2026/20261116-er27-522-000.pdf) | 2026-11-16 | propuesta; entrada solicitada 16 ene 2027 | Lectura del filing y alcance; propuesta no aprobación FERC. |
| S26 | [FERC OPP — cost transparency/customer protection](https://www.ferc.gov/cost-transparency-customer-protection) | 2026-10-19 | plazos respuestas 16 y 20 nov | Describe procedimiento/calendario; no acredita cada respuesta ni decisión final. |
| S27 | [MISO — large load filings fact sheet](https://cdn.misoenergy.org/Fact%20Sheet%20-%20MISO%20Large%20Load%20Filings796428.pdf) | ND — fact sheet sobre presentaciones 16 nov | presentaciones 16 nov; revisión futura | Síntesis primaria del proponente; no lectura íntegra de todos sus anexos. |
| S28 | [PJM — latest filings/home](https://www.pjm.com/Home/) | ND — índice con entrada de 20 nov | entrada de comentarios NERC 20 nov | Índice primario, sin PDF de comentarios recuperado; acredita presentación, no contenido íntegro. |
| S29 | [DOE — Eddystone order 202-26-52](https://www.energy.gov/documents/202-26-52-eddystone-order) | 2026-11-20 | vigencia 21 nov–18 feb 2027 | PDF: orden y fechas leídas; disponibilidad/dispatch cuando necesario no despacho ejecutado. |
| S30 | [DOE — Wagner order 202-26-25B](https://www.energy.gov/documents/202-26-25b-wagner) | 2026-11-17 | vigencia 18 nov–31 dic 2026 | PDF y cláusula de vigencia inspeccionada; no serie diaria de operación. |
| S31 | [DOE — Campbell order 202-26-51](https://www.energy.gov/ceser/federal-power-act-section-202c-midcontinent-independent-system-operator-miso-order-no-202-2) | 2026-11-13 | vigencia 15 nov–12 feb 2027 | Ficha oficial de orden; emisión antecedente, inicio jurídico W47; despacho no contrastado. |
| S32 | [Bundesnetzagentur — gas supply](https://bundesnetzagentur.de/DE/Gasversorgung/aktuelle_gasversorgung/artikel.html) | 2026-11-20 | almacenamiento al parte; flujos 12–18 nov | Parte alemán actualizado 09:18; evaluación de seguridad no toda Europa. |
| S33 | [IMO — Middle East incidents](https://www.imo.org/en/mediacentre/hottopics/pages/middle-east-highlighted-incidents.aspx) | 2026-11-17 | acumulado al 17 nov e incidentes con fecha individual | Registro móvil; acumulado no ataques semanales; sin primas ni tráfico 14 días. |
| S34 | [MOFCOM — anuncio 48](https://www.mofcom.gov.cn/zcfb/dwmygl/art/2026/art_61446ab4beee4f63973d4d0ab3097648.html) | 2026-10-16 | consulta hasta 15 nov; preregistro transitorio | Cuerpo releído, anexos WPS no auditados; no texto final posterior acreditado. |
| S35 | [MOFCOM — anuncio 49 drones](https://www.mofcom.gov.cn/zcfb/zc/art/2026/art_b2fa4e60bcd24bdf8c658e476b808785.html) | 2026-10-19 | efectivo 18 nov | Cuerpo, licencia y cláusula de vigencia; no expedientes de exportación. |
| S36 | [MOFCOM — anuncio 50 maquinaria de túneles](https://www.mofcom.gov.cn/zcfb/zc/art/2026/art_1628d886f39840489513af242f93517b.html) | 2026-10-19 | efectivo 18 nov | Cuerpo, distinción de destinos y vigencia; no entrega interrumpida acreditada. |
| S37 | [MOFCOM — anuncio 51 dragas](https://www.mofcom.gov.cn/zcfb/zc/art/2026/art_f4ab31f0b7e94c159b357e39f5a12fc9.html) | 2026-10-19 | efectivo 18 nov | Cuerpo/licencias/vigencia; no cuantificación de flujos afectados. |
| S38 | [BIS — anuncio remote access](https://www.bis.gov/press-release/bis-issues-rule-addressing-remote-access-american-super-intelligence-technology) | 2026-11-16 | anuncio 16 nov | Comunicado; texto y fecha jurídica se contrastan con S39. |
| S39 | [Federal Register — remote access IFR 2026-23529](https://www.govinfo.gov/content/pkg/FR-2026-11-19/html/2026-23529.htm) | 2026-11-19 | efectiva 19 nov; comentarios hasta 19 ene 2027 | Lectura dirigida de alcance, fechas y transición; no auditoría exhaustiva ECCN ni licencias ejecutadas. |
| S40 | [MOFCOM — conferencia 19 noviembre](https://www.mofcom.gov.cn/xwfbzt/2026/swbzklxxwfbh2026n11y19r/index.html) | 2026-11-19 | Consejo comercial 13 nov y posiciones actuales | Declaraciones de parte y proceso; no prueba de entrega ni desenlace de consulta48. |
| S41 | [Eurostat — industrial production September](https://ec.europa.eu/eurostat/en/web/products-euro-indicators/w/4-16112026-ap) | 2026-11-16 | septiembre 2026 y revisión agosto | Índices ajustados de producción; no causalidad IA/aranceles ni flujo de inversión. |
| S42 | [NBS — industrial production October](https://www.stats.gov.cn/english/PressRelease/202611/t20261117_1965883.html) | 2026-11-17 | octubre y enero–octubre 2026 | Valor añadido real y producción física por producto; producción no adopción/productividad. |
| S43 | [Seguridad Social — pensiones octubre](https://www.inclusion.gob.es/w/la-pension-media-del-sistema-de-la-seguridad-social-alcanza-los-1.376-1-euros-en-octubre-un-4-6-mas-alta-que-hace-un-ano) | 2026-10-27 | nómina octubre 2026 | Prestaciones, personas y nómina; no liquidación anual neta ni ejercicio fiscal cerrado. |
| S44 | [ANFAC — matriculaciones octubre](https://anfac.com/wp-content/uploads/2026/11/Informe-Matriculaciones-CCAA-FFEE-Octubre-2026.pdf) | 2026-11-02 | octubre y acumulado 2026 | Informe por propulsión/CCAA; no serie de seis meses de origen importado del universo requerido. |
| S45 | [BOE — Real Decreto 806/2026](https://www.boe.es/diario_boe/txt.php?id=BOE-A-2026-20742) | 2026-10-06 | campaña 13–27 nov, elección 29 nov, cámaras 23 dic | Texto legal de convocatoria; no resultados ni bloqueo presupuestario realizado. |
| S46 | [Eurogrupo — candidaturas presidencia BCE](https://www.consilium.europa.eu/es/press/press-releases/2026/11/06/statement-by-the-eurogroup-president-on-the-nominations-for-the-post-of-ecb-president/) | 2026-11-06 | nominaciones y procedimiento | Nominación no nombramiento; no preferencias nacionales inferidas. |
| S47 | [BCE — salida de presidenta](https://www.ecb.europa.eu/press/pr/date/2026/html/ecb.pr261029~abbb6dc64b.pt.html) | 2026-10-29 | fecha futura 7 feb 2027 | Antecedente; fecha fuera del horizonte 20 ene. |
| S48 | [MFA China — Xi/Trump bilateral](https://www.fmprc.gov.cn/eng/xw/zyxw/202611/t20261119_12063139.html) | 2026-11-19 | reunión 19 nov; publicación 18:00 hora de página | Relato primario chino; acuerdos políticos, no ejecución aduanera por partidas. |
| S49 | [MFA China — cumbre trilateral](https://www.mfa.gov.cn/eng/gjhdq_665435/3376_665447/3432_664920/3435_664926/202611/t20261119_12063266.html) | 2026-11-19 | reunión 19 nov; publicación 22:15 hora de página | Existencia de reunión; texto conjunto contrastado también en S50. |
| S50 | [White House — declaración trilateral toward Peace](https://www.whitehouse.gov/briefings-statements/2026/11/u-s-russia-china-heads-of-state-declaration-toward-peace/) | 2026-11-19 | cumbre y declaración 19 nov | Cuatro compromisos políticos; sin volumen de suministro, cronograma o tratado militar. |
| S51 | [Canada Finance — lista consolidada de contramedidas](https://www.canada.ca/en/department-finance/programs/international-trade-finance-policy/canadas-response-us-tariffs/complete-list-us-products-subject-to-counter-tariffs.html) | ND — resumen de vigencia 8 sep | medidas efectivas 8 sep, página consultada W47 | Resumen informativo sin sanción oficial; CAD, no USD; Gazette/expedientes sin conciliar. |
| S52 | [White House — scope Canada duties](https://www.whitehouse.gov/presidential-actions/2026/10/further-modifying-the-scope-of-products-of-canada-subject-to-the-additional-duties-imposed-to-offset-canadian-discrimination-against-the-commerce-of-the-united-states-with-respect-to-motor-vehicles/) | 2026-10-23 | vigencia modificación 30 oct | Parte dispositiva recontrastada; anexos/partidas y cobro no auditados integralmente. |
| S53 | [US Census — foreign trade release schedule](https://www.census.gov/foreign-trade/schedule.html) | ND — calendario consultado 21 nov | calendario 2026–2027 visible a consulta | Solo calendario primario indexado; no admite resultados por sectores ni precisa publicación del calendario. |
| S54 | [BLS — CPI October release](https://www.bls.gov/news.release/archives/cpi_11102026.htm) | 2026-11-10 | octubre 2026 | Documento localizado/abierto; no se extrae atribución causal de aranceles de su ausencia en el texto recuperado. |
| S55 | [BCE — lanzamiento Pontes](https://www.ecb.europa.eu/press/pr/date/2026/html/ecb.pr260921~e754847a7b.en.html) | 2026-09-21 | lanzamiento y participación inicial | Operación institucional inicial; no serie de volumen/demanda neta de colateral. |
| S56 | [Comisión Europea — convocatoria ETSG](https://finance.ec.europa.eu/news/eu-seeks-nominations-stakeholder-group-tokenisation-standards-finance-2026-11-09_en) | 2026-11-09 | solicitudes hasta 27 nov | Convocatoria y finalidad; no estándar final ni eficiencia realizada. |
| S57 | [US Treasury — resultado 10Y CUSIP 91282CRX1](https://www.treasurydirect.gov/instit/annceresult/press/preanre/2026/R_20261110_1.pdf) | 2026-11-10 | subasta 10 nov; emisión 16 nov | Resultado PDF primario; fecha de emisión no otra subasta. |
| S58 | [US Treasury — resultado 30Y CUSIP 912810UY2](https://www.treasurydirect.gov/instit/annceresult/press/preanre/2026/R_20261112_4.pdf) | 2026-11-12 | subasta 12 nov; emisión 16 nov | Resultado PDF primario; no duración de tipos secundarios. |
| S59 | [US Treasury — resultado 3Y CUSIP 91282CRW3](https://www.treasurydirect.gov/instit/annceresult/press/preanre/2026/R_20261109_3.pdf) | 2026-11-09 | subasta 9 nov; emisión 16 nov | Antecedente recuperado; vencimiento no elegible para V01-03. |
| S60 | [FRED/Fed — DGS10](https://fred.stlouisfed.org/series/DGS10) | 2026-11-20 | sesiones 13 y 16–19 nov | Cinco observaciones visibles; no continuidad de más de diez sesiones ni cierre 20 nov. |
| R01 | [TSMC / transcripción de resultados Q3](https://investor.tsmc.com/english/encrypt/files/encrypt_file/reports/2026-10/eba4fac72873bf546b669bd2b5d973df5c93215d/TSMC%203Q26%20Transcript.pdf) | 2026-10-15 | Antecedente recontrastado | Antecedente recién contrastado; apartados de packaging/capacidad y respuesta sobre alternativas. No dato nuevo W47 ni auditoría independiente de yields. |
| R02 | [NVIDIA / CFO commentary Q3FY27](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000088/q3fy27cfocommentary.htm) | 2026-11-17 | Antecedente recontrastado | Relectura de compromiso/garantías y aviso 10-Q; periodos al25oct y proyecciones posteriores. |
| R03 | [MFA China / bilateral Xi–Trump](https://www.fmprc.gov.cn/eng/xw/zyxw/202611/t20261119_12063139.html) | 2026-11-19 | Antecedente recontrastado | Comunicado primario de parte; acuerdo de formular plan, no implementación acreditada. |
| R04 | [BCE / Financial Stability Review](https://www.ecb.europa.eu/press/financial-stability-publications/fsr/html/ecb.fsr202611~e03b919d36.es.html) | 2026-11-18 | Antecedente recontrastado | Lectura dirigida §1.2/§2.2 y overview: inversores/absorción/riesgo soberano. Periodos heterogéneos, en gráficos hasta10nov o trimestres anteriores; no serie de la última semana ni crisis ejecutada. |
| R05 | [NVIDIA /8-K resultados](https://www.sec.gov/Archives/edgar/data/1045810/000104581026000088/nvda-20261117.htm) | 2026-11-17 | Antecedente recontrastado | Q terminado25oct; cargos y firma de Kress17nov. No trimestre operativo posterior al relevo11nov; anexos furnished. |
| R06 | [Bundesnetzagentur / gas alemán](https://bundesnetzagentur.de/DE/Gasversorgung/aktuelle_gasversorgung/artikel.html) | 2026-11-20 | Antecedente recontrastado | Parte fechado20nov; alternativas de importación, flujos12–18nov y almacenamiento. Alemania no toda UE. |
| R07 | [BOE /convocatoria elecciones](https://www.boe.es/diario_boe/txt.php?id=BOE-A-2026-20742) | 2026-10-06 | Antecedente recontrastado | Antecedente recontrastado: fecha29nov/campaña/cámaras; no resultado ni efecto presupuestario consumado. |
| R08 | [Anthropic /cierre OPV y privada](https://www.anthropic.com/news/ipo-close) | 2026-11-20 | Antecedente recontrastado | Captación cerrada por emisor; no retorno ni independencia de toda la demanda demostrados. |

[[ACTUALIZACION_SEMANAL_231_2026_11_22]] · [[VECTOR_00_Indice]] · [[TESIS_00_Indice]] · [[Radar_Eventos_2026_11]] · [[PROPUESTA_DECISION_EVENTOS_2026_11_22]]

<details>
<summary>Filas interpretativas anteriores, sustituidas el 22 de noviembre por decisión TASK391; no son soporte vigente</summary>

| Tesis | Soporte | Estado | Alcance previo | Falsación previa |
|---|---|---|---|---|
| [[TESIS_01_Dominancia_Fiscal]] | moderado | vigente | Restricción fiscal y ejecución; dominancia monetaria condicional | Medidas/ejecución fiscal y monetaria, persistencia y nexo a financiación. |
| [[TESIS_02_Frictionless_Stabilization]] | moderado_alto | vigente | Coerción modular; estabilización con validación propia | Acto/licencia y excepción aplicados, estabilización material; comparar hipótesis sin coordinador. |
| [[TESIS_03_Captura_de_Renta]] | moderado | vigente | Formulación causal conjunta; evidencia diferenciada por mecanismo | Rentas/horas/cohortes/territorios y propiedad comparables; margen y coste/beneficio por capa. |
| [[TESIS_04_Multipolaridad_Logistica]] | moderado_alto | vigente | Vulnerabilidad logística y coste de resiliencia | Ruta/volumen/coste/capacidad, plazo y persistencia; acto/entrega que ejecute concesión. |
| [[TESIS_05_Tokenizacion_del_Colateral]] | moderado | en_validacion | Admisibilidad jurídica acotada; uso/eficiencia/demanda neta en validación | Activo, elegibilidad, origen de fondos, volumen liquidado recurrente y coste total frente a alternativa. |
| [[TESIS_06_IA_como_silicio_y_energia]] | alto | vigente | Dependencia física; financiación y productividad con pruebas independientes | Entregas/yield/plazo y energía; después utilización/tarea/coste/caja/retorno. Reposición distinta de expansión y vidas útiles por activo. |


</details>
