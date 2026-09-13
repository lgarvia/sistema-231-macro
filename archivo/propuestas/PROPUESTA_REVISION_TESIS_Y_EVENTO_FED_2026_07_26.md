# Propuesta de revisión de tesis y regla de alta FED — 26/07/2026

> **Estado Front Office:** ✅ Aprobada y ejecutada el 26/07/2026 mediante TASK_044.  
> **Excepción vigente:** la ficha FED no se crea antes del comunicado; continúa sometida a la regla condicional de la sección 2.

## Alcance y decisión ejecutiva

Esta nota revisó la arquitectura de eventos y las seis tesis después del alta de [[Evento_E0_2026_07_24_US_Tariff_Stack]]. Front Office aprobó la propuesta y autorizó su aplicación a `TESIS_*`, al índice y a la sección `Tesis (Luis)` del nuevo evento.

La conclusión operativa sobre la reunión de la Reserva Federal del 28–29 de julio es:

- **No crear un evento FOMC genérico antes de la decisión.**
- **Mantener la reunión como disparador obligatorio del [[Radar_Eventos_2026_07]].**
- **Crear `E0_2026_07_29_Fed_Tightening_Bias` después del comunicado únicamente si se ejecuta al menos una de las condiciones objetivas de la sección 2.**

La reunión puede convertirse en evento, pero el hecho durable sería el cambio de régimen o de función de reacción, no la mera celebración del FOMC.

## 1. Punto de partida factual de la FED

- El FOMC se reúne el **28–29/07/2026**. No es una reunión asociada a un Summary of Economic Projections; el próximo SEP está previsto para septiembre.
- El 17/06 mantuvo el rango objetivo en **3,50%–3,75%**, por voto **12–0**, y reafirmó un régimen de reservas amplias.
- Las actas de junio describen las reservas como amplias, mantienen los riesgos de inflación sesgados al alza y atribuyen parte de la inflación de bienes a aranceles, energía y demanda ligada a IA.
- El Monetary Policy Report de julio registra PCE interanual del **4,1%** y PCE subyacente del **3,4%** en mayo. También advierte que los efectos arancelarios no se observan directamente en los índices y dependen de la respuesta de empresas, consumidores, importadores y exportadores.
- El SEP de junio situó la mediana de PCE 2026 en **3,6%**, PCE subyacente en **3,3%** y fed funds a cierre de 2026 en **3,8%**. La distribución estaba muy dividida: 8 participantes en 3,625%, 3 en 3,875%, 5 en 4,125%, 1 en 4,375% y 1 en 3,375%.
- Christopher Waller señaló el 13/07 que el FOMC debía estar dispuesto a endurecer si la inflación subyacente volvía a sorprender al alza, aunque también advirtió contra reaccionar demasiado pronto.

**Lectura operativa:** existe riesgo hawkish real, pero no hay todavía cambio factual de régimen. La nueva pila arancelaria entró en vigor después de los datos de mayo y apenas antes del FOMC, por lo que la reunión puede reconocer el canal, pero todavía no puede medir dos publicaciones de transmisión.

## 2. Regla propuesta para el evento FED

### Nombre reservado

`E0_2026_07_29_Fed_Tightening_Bias`

### Alta inmediata si se cumple al menos una condición

1. **Movimiento de tipos:** subida de al menos 25 puntos básicos.
2. **Cambio explícito de sesgo:** el comunicado o la rueda de prensa introduce una preferencia verificable por endurecer de nuevo, o señala una subida próxima por persistencia de aranceles, energía o inflación subyacente.
3. **Ruptura del consenso:** al menos dos votos por subir tipos, o una división material equivalente que revele un bloque hawkish organizado.
4. **Tensión de implementación:** cambio no rutinario en IORB, SRF, compras de reservas u otra herramienta motivado por estrés en repo o mercados monetarios, no por mero alineamiento técnico.
5. **Acoplamiento aranceles–reacción monetaria:** la FED vincula expresamente la nueva pila arancelaria con una inflación subyacente persistente y con una senda de política más restrictiva.

### No alta

Si el FOMC mantiene 3,50%–3,75%, el voto sigue siendo unánime o casi unánime, conserva el régimen de reservas amplias y usa lenguaje dependiente de datos sin sesgo nuevo, se registrará la ejecución en el radar y **no se creará evento**.

### Arquitectura si se activa

- **Clase inicial:** E0 intensificado.
- **Presión / tendencia / peso:** P4 / ↑ / 4.
- **Vector primario:** V01 — Arquitectura monetaria global.
- **Vectores secundarios:** V04 — Comercio global; V02 — Energía y nodos; V03 — Semiconductores.
- **Transmisión:** V04 + V02 + V03 → inflación de oferta → V01 → crédito, dólar y refinanciación.
- **Escalada a E1:** dos reuniones consecutivas con endurecimiento efectivo, estrés monetario verificable o transmisión financiera que cruce los triggers de V01.

## 3. Auditoría: qué faltaba

### Cubierto con el nuevo evento

- **V04 ya no carece de evento primario.** [[Evento_E0_2026_07_24_US_Tariff_Stack]] conserva la sustitución de Section 122 por instrumentos Section 301 / 338 y separa el hecho jurídico de su transmisión posterior.
- La cadena `V04 → V05 → V01` ya está incorporada a [[MAPA_TRANSMISIONES]].

### Huecos todavía abiertos

1. **V01 sin evento primario activo.** No conviene rellenarlo artificialmente: la regla FED anterior permite abrirlo solo si aparece una señal durable.
2. **TESIS_05 sin paquete de sensores propio.** La tokenización del colateral depende hoy de referencias demasiado genéricas a QRA/FOMC. Debe vigilar por separado reservas de stablecoins, compras netas de T-bills, volumen liquidado de Treasuries tokenizados, migración de depósitos y fechas regulatorias efectivas.
3. **Confusión posible entre inflación de oferta y dominancia fiscal.** Aranceles, energía o crédito más caro pueden restringir a un banco central sin demostrar que la política monetaria esté subordinada a la financiación soberana. TESIS_01 necesita una puerta de evidencia más exigente.
4. **TESIS_04 conserva lenguaje de “descompresión” ya superado.** Los incidentes marítimos y los ataques renovados obligan a revisar el estado, aunque todavía no haya prima, desvío o cierre que complete un trigger.
5. **TESIS_06 mezcla escasez y expansión.** ASML, TSMC y el CAPEX de hyperscalers confirman inversión acelerada; la tesis debe localizar el cuello de botella móvil —litografía, packaging, energía, red o permisos— en lugar de presuponer una única escasez permanente.
6. **Sensores corporativos caducados o no verificados.** Alphabet e Intel figuraban como próximas referencias en TESIS_06, pero no superaron la validación de calendario del radar. Deben sustituirse por fechas oficiales verificadas.
7. **El índice de tesis quedó anclado al 18/07.** Tras el BCE, la reescalada marítima, la pila arancelaria y los datos industriales, la matriz de soporte ya no refleja todo el estado factual.

### Lo que no falta

No se recomienda crear una séptima tesis. La novedad principal —choques físicos y regulatorios que endurecen el crédito y la reacción monetaria— es una **cadena de transmisión entre V04/V02/V03 y V01**, no una hipótesis estructural independiente.

## 4. Revisión aprobada y aplicada a las seis tesis

| Tesis | Revisión propuesta | Soporte propuesto | Prioridad |
|:---|:---|:---:|:---:|
| **TESIS_01 — Dominancia Fiscal** | Mantener vigente. Añadir una condición de no-validación: deuda alta, inflación de oferta o endurecimiento crediticio por sí solos no prueban dominancia. Exigir evidencia de subordinación monetaria a subastas, coste fiscal, balance o estabilidad financiera. Recalibrar después del FOMC y del QRA. | Moderado | Alta, después de FED/QRA |
| **TESIS_02 — Frictionless Stabilization** | Incorporar [[Evento_E0_2026_07_24_US_Tariff_Stack]] como sensor central. Reformular la idea como “coerción modular sin ruptura total”: expira un instrumento, lo sustituyen otros, mientras el flujo comercial se reconfigura en lugar de desaparecer. Mantener el nombre, pero añadir subtítulo español claro. | Alto | Muy alta |
| **TESIS_03 — Captura de Renta** | Separar tres capas: vivienda/demografía, flujo contributivo y mecanismo fiscal de captura. La afiliación de julio es contrapeso factual y no permite inferir por sí sola el saldo contributivo. Bajar el soporte agregado hasta disponer de liquidación comparable de cotizaciones, pensiones y distribución por edad/renta. | Moderado-alto | Media |
| **TESIS_04 — Multipolaridad Logística** | Eliminar “en descompresión”. Integrar la reescalada de [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb]] y mantener separados tres niveles: incidente, encarecimiento asegurador y desvío físico. | Moderado-alto | Muy alta |
| **TESIS_05 — Tokenización del Colateral** | Mantener en validación. No elevar soporte sin sensores directos. Crear un cuadro específico de stablecoins/T-bills/liquidación tokenizada/depósitos/regulación y definir umbrales antes de proponer un evento. | Moderado | Media-alta |
| **TESIS_06 — IA como silicio y energía** | Mantener vigente y alta, pero sustituir “escasez fija” por “restricción de cadena de conversión”: el límite se desplaza entre silicio, packaging, electricidad, red y permisos. Limpiar fechas corporativas no verificadas y añadir una condición de falsación basada en mejoras sostenidas de coste unitario y eficiencia energética. | Alto | Alta |

## 5. Secuencia de control posterior

1. **Ejecutado 26/07:** TESIS_01–06, [[TESIS_00_Indice]] y la asignación del evento arancelario a TESIS_02.
2. **29/07, después del FOMC:** aplicar la regla de alta FED. TESIS_01 solo cambia de soporte si aparece evidencia adicional a la ya incorporada.
3. **03–05/08, financiación/TBAC/QRA:** contrastar absorción, composición y microestructura antes de cualquier nueva lectura de dominancia.
4. **Siguiente ciclo mensual:** comenzar la línea base de los cinco sensores de TESIS_05 sin abrir evento preventivo.
5. **Cuando exista liquidación contributiva comparable:** revisar el soporte de TESIS_03 con cotizaciones, prestaciones y distribución por edad/renta.

## 6. Fuentes primarias

- [Federal Reserve — calendario FOMC 2026](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm)
- [Federal Reserve — comunicado del 17-jun-2026](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260617a.htm)
- [Federal Reserve — actas del FOMC de junio](https://www.federalreserve.gov/monetarypolicy/fomcminutes20260617.htm)
- [Federal Reserve — Monetary Policy Report de julio](https://www.federalreserve.gov/monetarypolicy/2026-07-mpr-part1.htm)
- [Federal Reserve — SEP del 17-jun-2026](https://www.federalreserve.gov/monetarypolicy/fomcprojtabl20260617.htm)
- [Federal Reserve — discurso de Christopher Waller, 13-jul-2026](https://www.federalreserve.gov/newsevents/speech/waller20260713a.htm)
- [USTR — Section 301 sobre sesenta economías](https://ustr.gov/about/policy-offices/press-office/press-releases/2026/july/ustr-takes-action-forced-labor-section-301-investigations)
- [USTR — Section 338 sobre Canadá](https://ustr.gov/about/policy-offices/press-office/press-releases/2026/july/ambassador-greer-issues-statement-president-trump-imposing-section-338-tariffs-canada)

## 7. Control integral posterior — TASK_043

La revisión técnica completa confirma:

- siete eventos activos: seis E0 y un E1;
- 33 hitos únicos en el radar, sin IDs duplicados, con cobertura V01=13, V02=5, V03=3, V04=5, V05=4 y V06=3;
- fechas críticas de FED, BoE, BoJ, BEA, BLS, Tesoro/QRA, OPEP+, EIA, FERC, OFAC, DOE y USTR contrastadas de nuevo con fuentes primarias;
- correspondencia correcta entre vectores primarios/secundarios y la carga publicada en [[SALUD_DEL_SISTEMA]];
- reparación de los enlaces abreviados de TESIS en el snapshot y sustitución en V03 de un evento histórico inexistente por [[Evento_E0_2026_CoWoS_Capacity]].
- depuración de los contextos de seis eventos heredados para eliminar afirmaciones no ejecutadas por sus KPIs, sin alterar ninguna sección `Tesis (Luis)`;
- corrección del mapa de transmisiones para impedir que inflación de oferta, logística o demografía validen automáticamente dominancia fiscal;
- ampliación del QRA en el radar al proceso completo del 3–5 de agosto: financiación estimada/TBAC y anuncio final.

Los cambios fueron **validados por Front Office y ejecutados en TASK_044**:

1. TESIS_02 incorpora la pila arancelaria como sensor central y sube a soporte alto.
2. TESIS_04 elimina “en descompresión”, integra la reescalada marítima y sube a moderado-alto.
3. TESIS_06 convierte DOE 202-26-35 en hecho ya expirado, retira Alphabet/Intel y adopta el cuello de botella móvil.
4. TESIS_01 añade una puerta estricta de no-validación; TESIS_03 baja a moderado-alto; TESIS_05 incorpora cinco sensores dedicados.
5. [[TESIS_00_Indice]], [[SALUD_DEL_SISTEMA]], [[00_AGENT_SNAPSHOT]] y [[Evento_E0_2026_07_24_US_Tariff_Stack]] quedan sincronizados.
