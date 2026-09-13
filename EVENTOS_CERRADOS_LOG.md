---
tipo: log_cierres_eventos
creado: 2026-04-26
actualizador: Sistema 231 / Front Office
ultima_actualizacion: 2026-08-17
---

# REGISTRO DE CIERRES DE EVENTOS

> Trazabilidad de cierre y archivado de fichas E0/E1.
> Cada vez que un evento se mueve al directorio canónico `20 Académico/23 MOC/231 Eventos/231_Eventos_Cerrados/`, se añade una línea aquí.
> Formato: `## [YYYY-MM-DD] Cierre: [Nombre del evento]` + Tipo de cierre + Razón factual.

---

## Tipos de cierre

- **Vencimiento de fecha:** trigger atado a fecha concreta ya ocurrida.
- **Trigger ejecutado:** decisión institucional o evento binario consumado.
- **Pérdida de relevancia:** evento continuo sin escalada en el ciclo, queda en monitorización por RADAR.
- **Fusión:** integrado en otro evento de gatillo idéntico.
- **Falsa alarma:** trigger no se materializó.

---

## Convención de archivado

Destino canónico vigente: `20 Académico/23 MOC/231 Eventos/231_Eventos_Cerrados/`
Renombrado: mantener el nombre original y declarar fecha y razón de cierre en el snapshot de la ficha.

---

## Registro

## [2026-08-17] Cierre: Evento_E0_2026_05_20_Taiwan_Riesgo_Estrecho
- **Tipo de cierre:** Vencimiento de ventana / transferencia a vector.
- **Razón factual:** la ventana oficial de Han Kuang 42 terminó el 14/08 y no se verificó un NOTAM o zona de exclusión del EPL que cumpliera el trigger. La presión de zona gris continúa como observatorio en V06.
- **Memoria:** [[231_Eventos_Cerrados/Evento_E0_2026_05_20_Taiwan_Riesgo_Estrecho]].

## [2026-08-17] Cierre: Evento_E0_2026_06_07_GNSS_Spoofing_Maritimo
- **Tipo de cierre:** Pérdida de naturaleza episódica / transferencia a vector.
- **Razón factual:** la interferencia GNSS se había convertido en una condición persistente sin accidente, orden mandatoria ni desvío que ejecutara sus triggers. El sensor continúa en V02.
- **Memoria:** [[231_Eventos_Cerrados/Evento_E0_2026_06_07_GNSS_Spoofing_Maritimo]].

## [2026-08-17] Cierre: Evento_E0_2026_06_15_Spain_Pensiones_Renta
- **Tipo de cierre:** Fusión con vector y tesis.
- **Razón factual:** la sostenibilidad de pensiones es una restricción estructural y la ficha carecía de ventana acotada; el seguimiento pasa a V05 y TESIS_03 hasta una liquidación que cruce un umbral explícito.
- **Memoria:** [[231_Eventos_Cerrados/Evento_E0_2026_06_15_Spain_Pensiones_Renta]].

## [2026-07-18] Cierre: Evento_E0_2026_07_02_US_NFP
- **Tipo de cierre:** Trigger ejecutado / Vencimiento de fecha
- **Razón factual:** El informe de junio registró +57.000 nóminas y ejecutó el Trigger A. La siguiente publicación del 07/08 permanece como hito independiente del RADAR.

## [2026-07-18] Cierre: Evento_E0_2026_06_20_Stress_Colateral_SOFR
- **Tipo de cierre:** Falsa alarma / Pérdida de relevancia
- **Razón factual:** SOFR 3,62%, EFFR 3,63% y ON RRP 0,278 B$ no activaron ningún trigger; tampoco hubo uso persistente de SRF, subasta fallida ni pausa de emergencia del QT. El riesgo vuelve a monitorización basal en V01 y RADAR.

## [2026-06-21] Cierre: Evento_E0_2026_06_16_BoJ_MPM
- **Tipo de cierre:** Trigger ejecutado
- **Razón factual:** Subida histórica de tipos del Banco de Japón en 25 pb (hasta el 1.0%) en votación 7-1, forzada por la inflación importada de energía de oferta, asimilada en Vector 1 (Monetario).

## [2026-06-21] Cierre: Evento_E0_2026_06_15_G7_Evian_Summit
- **Tipo de cierre:** Trigger ejecutado
- **Razón factual:** Clausura de la cumbre del G7 en Évian (15 de junio) enfocada en el rearme híbrido, controles de exportación y aranceles sectoriales coordinados de doble uso frente a BRICS+, asimilada en Vector 6 (Geopolítico).

## [2026-06-21] Cierre: Evento_E0_2026_06_15_Memorandum_Islamabad
- **Tipo de cierre:** Trigger ejecutado / Invalidación
- **Razón factual:** Firma de la tregua provisional de 60 días para reabrir Ormuz el 14-15 de junio, invalidada de facto el 20 de junio por la escalada militar proxy en el Líbano y amenazas de re-cierre, asimilada en Vector 2 (Energía) y Vector 6 (Geopolítico).

## [2026-06-21] Cierre: Evento_E0_2026_06_17_Fed_FOMC
- **Tipo de cierre:** Trigger ejecutado
- **Razón factual:** Reunión del FOMC del 17 de junio de 2026 donde se mantuvieron tipos planos (3.50%-3.75%) pero con dot plot hawkish al 3.8% y retirada de la forward guidance de recortes bajo Kevin Warsh, asimilado en Vector 1 (Monetario).

## [2026-06-21] Cierre: Evento_E0_2026_06_11_BCE_Consejo
- **Tipo de cierre:** Trigger ejecutado
- **Razón factual:** El Consejo de Gobierno del BCE elevó el 11 de junio de 2026 los tipos clave en 25 pb (facilidad de depósito en 2.25%), asimilado en Vector 1 (Monetario).

## [2026-06-21] Cierre: Evento_E0_2026_06_10_TSMC_Guidance
- **Tipo de cierre:** Trigger ejecutado / Vencimiento de fecha
- **Razón factual:** Publicación del reporte de ingresos consolidados de mayo (+30.1% YoY) el 10 de junio de 2026. Los datos fueron completamente asimilados en el Vector 3 (Semiconductores).

## [2026-06-07] Cierre: Evento_E0_2026_06_07_OPEP_Meeting
- **Tipo de cierre:** Trigger ejecutado
- **Razón factual:** Conferencia Ministerial celebrada el 7 de junio de 2026. Un grupo de 7 miembros acuerda elevar voluntariamente cuotas en 188k bpd desde julio, mientras las políticas agregadas de recortes de la OPEP+ se mantienen y las compensaciones se extienden hasta diciembre de 2026. *Nota: El cierre de esta ficha no implica la resolución del riesgo energético estructural, que permanece monitorizado en V02 y en Evento_E0_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb.*

## [2026-05-31] Cierre: E1_2026_02_28_Medio_Oriente_Escalada
- **Tipo de cierre:** Fusión
- **Razón factual:** Fusión topológica y consolidación analítica completa en el sensor de seguros y logística `E0_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb`. Este último monitoriza exactamente las mismas variables físicas (War Risk premiums, fletes VLCC, SCFI, Suez transits y Brent) pero bajo triggers cuantitativos depurados de ruido diplomático.

## [2026-05-31] Cierre: E0_2026_05_28_US_PCE
- **Tipo de cierre:** Trigger ejecutado / Vencimiento de fecha
- **Razón factual:** Publicación del deflactor PCE de abril por la BEA el 28 de mayo de 2026. Los datos reales (Headline PCE 3.8% YoY / Core PCE 3.3% YoY / Ahorro de los hogares 2.6%) han sido completamente auditados y consolidados de forma conservadora en el estado estructural del vector V01 (Dominancia Fiscal), agotando el sensor de este ciclo.

## [2026-05-17] Cierre: E0_2026_06_06_EU_Elections
- **Tipo de cierre:** Pérdida de relevancia / Falsa alarma
- **Razón factual:** Error de fecha histórico detectado en la auditoría (no existen elecciones parlamentarias europeas en 2026). Agrupar las elecciones regionales menores dispersas resta precisión analítica. El riesgo de gobernanza se asimila a nivel periférico y en los diferenciales de deuda.

## [2026-05-17] Cierre: E1_2026_01_30_Fed_Transicion_Warsh
- **Tipo de cierre:** Trigger ejecutado / Fusión
- **Razón factual:** Confirmación y asunción del cargo completadas formalmente en el Senado y la Fed el 13-15 de mayo de 2026. Sus implicaciones operativas y de liquidez repo/subastas UST se fusionan con el evento recurrente FOMC (`E0_2026_06_11_Fed_FOMC`) y la `TESIS_01` (Dominancia Fiscal).

## [2026-05-01] Cierre: Repo Market / Sistema Financiero
- **Tipo de cierre:** Pérdida de relevancia
- **Razón factual:** Trigger continuo sin escalada manifiesta en el ciclo de abril. El riesgo se integra en la monitorización basal del RADAR.

## [2026-05-01] Cierre: Comercio Global / Riesgo Marítimo
- **Tipo de cierre:** Pérdida de relevancia
- **Razón factual:** Trigger continuo sin escalada manifiesta en el ciclo de abril. Riesgos logísticos asimilados en el escenario base.

## [2026-05-01] Cierre: Hyperscalers Q1 CAPEX AI
- **Tipo de cierre:** Trigger ejecutado
- **Razón factual:** Temporada de resultados Q1 completada para los 5 grandes (Alphabet, Microsoft, Meta, Amazon, Apple) entre el 28 de abril y el 1 de mayo de 2026. CAPEX estructural confirmado.

## [2026-05-01] Cierre: BoJ Normalización / Yen
- **Tipo de cierre:** Trigger ejecutado
- **Razón factual:** Reunión de política monetaria del 24 de abril de 2026 ejecutada. El mercado asimila la 
