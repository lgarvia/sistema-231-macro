---
tipo: tesis_estructural
id: TESIS_05
estado: en_validacion
soporte: moderado
ultima_actualizacion: 2026-09-12
corte_factual_previo: "2026-09-12 21:21 Europe/Madrid"
alcance_actualizacion: "Precierre W37 TASK_099; revisión de tesis sobre evidencia admitida en fases 1-4"
vector_dominante: "[[VECTOR_01_Arquitectura_monetaria_global]]"
---

# 💡 TESIS_05: Tokenización del Colateral

## 1. Definición

Las stablecoins, los depósitos tokenizados y los bonos públicos tokenizados amplían la distribución digital del dinero y crean nuevos canales de demanda, liquidación y movilización de colateral. Dado que la mayoría de stablecoins están denominadas en dólares y respaldadas parcialmente por activos líquidos, pueden extender la dolarización y la demanda de instrumentos soberanos cortos fuera del depósito bancario tradicional.

La tesis no presupone que las stablecoins sean compradores indispensables de Treasuries ni que sustituyan automáticamente a SWIFT, a la banca o al dinero de banco central.

## 2. Restricción estructural asociada

- **Confianza:** el dinero tokenizado depende de la calidad, custodia y liquidez del activo de reserva.
- **Regulación:** admisibilidad de reservas, reembolso, segregación patrimonial y acceso a sistemas de pago.
- **Financiación bancaria:** migraciones desde depósitos pueden reducir crédito y alterar la demanda bancaria de deuda.
- **Soberanía monetaria:** la adopción de stablecoins en economías débiles puede intensificar dolarización y volatilidad de capitales.

## 3. Manifestaciones observables

- **Escala:** el BIS sitúa la capitalización de stablecoins cerca de 300 B$ a 29/05/2026, con predominio abrumador de denominaciones en dólares.
- **Demanda de activos cortos:** las reservas de emisores incluyen letras del Tesoro y fondos monetarios, creando un canal adicional hacia instrumentos públicos líquidos.
- **Arquitectura institucional:** bancos centrales y BIS exploran un modelo con reservas de banco central, depósitos bancarios y bonos públicos tokenizados.
- **Pagos:** las stablecoins permiten transferencias programables y transfronterizas, pero siguen presentando deficiencias de singularidad, elasticidad e integridad monetaria.
- **Integración financiera:** una nota de la Reserva Federal del 16/07 describe stablecoins y activos tokenizados como canales crecientemente conectados con pagos en dólares y mercados tradicionales; la SEC ya distingue modelos de valores tokenizados sin eximirlos de la regulación de valores.

## 4. Tensiones internas

- **Desintermediación:** crecimiento a costa de depósitos bancarios puede reducir financiación y crédito.
- **Composición de flujos:** si el dinero procede de fondos monetarios, el aumento de demanda neta de T-bills puede ser pequeño.
- **Riesgo del subyacente:** una pérdida de liquidez o confianza en reservas puede romper la paridad.
- **Centralización persistente:** gran parte de la tokenización institucional refuerza, en lugar de elimina, el dinero de banco central y la intermediación regulada.

## 5. Relación con VECTORES y EVENTOS

- **Vector dominante:** [[VECTOR_01_Arquitectura_monetaria_global]].
- **Vectores secundarios:** [[VECTOR_04_Reconfiguracion_del_comercio_global]] y [[VECTOR_06_Orden_geopolitico_y_esferas_de_influencia]].
- **Memoria de contraste:** [[20 Académico/23 MOC/231 Eventos/231_Eventos_Cerrados/Evento_E0_2026_06_20_Stress_Colateral_SOFR]].
- **Sensores transversales:** QRA, FOMC y evolución de letras/ON RRP en [[Radar_Eventos_2026_09]] y V01.

### Paquete dedicado de sensores

| Sensor | Evidencia primaria | Qué debe distinguir | Frecuencia |
|:---|:---|:---|:---:|
| Reservas de stablecoins | Informes mensuales de composición y attestations de emisores regulados | Efectivo, T-bills, repos y fondos monetarios; concentración y duración | Mensual |
| Demanda neta de T-bills | Datos del Tesoro/TBAC y variación de reservas declaradas | Compra adicional frente a sustitución de fondos monetarios, depósitos u otros tenedores | Mensual / QRA |
| Liquidación tokenizada | Reguladores, infraestructuras y plataformas supervisadas | Emisión nominal frente a volumen realmente liquidado, DvP y uso de colateral | Mensual / trimestral |
| Migración de depósitos | Fed, FDIC y encuestas bancarias | Traslado atribuible a stablecoins frente a variación estacional o de tipos | Trimestral |
| Calendario regulatorio | Congreso, Tesoro, Fed, SEC y reguladores bancarios | Norma aprobada, fecha efectiva y requisitos de reserva, reembolso y custodia | Por hito |

## 6. Criterios de validación o refutación

**Refuerzan la tesis:**
- Crecimiento verificable de reservas en deuda soberana que añada demanda neta, no mera sustitución de fondos monetarios o depósitos.
- Uso material de dinero y bonos tokenizados en liquidación institucional y comercio transfronterizo.
- Integración regulada de activos tokenizados con bancos centrales y mercados de colateral.

**Condiciones previas a abrir un EVENTO:**
- Una norma final o fecha efectiva cambia materialmente qué reservas, reembolsos o custodios son admisibles.
- Tres observaciones mensuales comparables muestran aumento de reservas en T-bills que no queda explicado por sustitución completa de fondos monetarios o depósitos.
- Una infraestructura supervisada acredita uso sostenido de bonos públicos tokenizados en liquidación DvP o como colateral, no solo emisión nominal.
- Datos oficiales o bancarios atribuyen una migración persistente de depósitos o un cambio de crédito al uso de stablecoins.

Hasta construir una serie base comparable, estos puntos son **puertas de evidencia**, no triggers numéricos automáticos ni una autorización de alta.

**La debilitan o refutan:**
- Estancamiento de adopción o prohibición efectiva de stablecoins y activos tokenizados.
- Evidencia de que la demanda de T-bills es neutral por sustitución completa de otros compradores.
- Crisis repetidas de paridad o custodia que impidan su uso como dinero o colateral fiable.

## 7. Calibración actual — 29/08/2026

- **Estado:** en validación.
- **Grado de soporte:** moderado.
- **Evidencia favorable:** escala cercana a 300 B$, predominio del dólar, reservas invertidas en activos cortos y mayor integración analítica y regulatoria con las finanzas tradicionales.
- **Evidencia contradictoria:** el BIS identifica fallos estructurales; no hay evidencia de indispensabilidad para SOFR o subastas ni una serie homogénea de demanda neta, liquidación o migración de depósitos.
- **Actualización de ventana:** No se localizó un documento primario nuevo sobre reservas, liquidación DvP o migración de depósitos. El cruce de $40T, las recompras de liquidez, el PCE de julio y la doctrina Warsh no acreditan demanda tokenizada ni activan una puerta de evidencia.
- **Cambio de esta revisión:** se mantiene el paquete dedicado de cinco sensores y se impide abrir un evento antes de construir una línea base comparable.

## 8. Fuentes de seguimiento

- [BIS — Annual Economic Report 2026](https://www.bis.org/publ/arpdf/ar2026e.pdf)
- [BIS — sistema monetario de próxima generación, junio de 2026](https://www.bis.org/press/p260623.htm)
- [U.S. Treasury Borrowing Advisory Committee — stablecoins y mercado de Treasuries](https://home.treasury.gov/news/press-releases/sb0121)
- [New York Fed — condiciones de reservas y mercado monetario](https://tellerwindow.newyorkfed.org/2026/03/31/the-implementation-of-reserve-management-purchases-to-maintain-ample-reserves/)
- [Reserva Federal — stablecoins, pagos digitales y papel internacional del dólar, 16-jul-2026](https://www.federalreserve.gov/econres/notes/feds-notes/fifth-conference-on-the-international-roles-of-the-u-s-dollar-stablecoins-digital-payments-and-the-ir-of-the-usd-20260716.html)
- [SEC — Statement on Tokenized Securities, 28-ene-2026](https://www.sec.gov/newsroom/speeches-statements/corp-fin-statement-tokenized-securities-012826-statement-tokenized-securities)
- [BIS — remuneración de stablecoins y sustitución de depósitos/fondos, 19-jun-2026](https://www.bis.org/publ/bisbull125.htm)

## Rectificación y reconciliación — 06/09/2026 (TASK_090)

Se conserva **en validación · soporte moderado**, según su frontmatter y criterio causal; la etiqueta «vigente · latente» de la síntesis W36 se retira. Recompras, FOMC o liquidez ordinaria no aportan por sí solos evidencia de tokenización. Los antecedentes estructurales conservan sus periodos; ninguna fecha de modificación sustituye la consulta de su fuente.

## Revisión W37 — 12/09/2026 (TASK_099, fase 5)

- **Estado / soporte:** en validación · moderado; sin cambio de grado.
- **Evidencia W37:** no se admite evidencia primaria nueva sobre reservas de stablecoins, demanda neta adicional de T-bills, liquidación DvP, uso de bonos tokenizados como colateral o migración de depósitos.
- **Límite de imputación:** BCE, JGB, TGA, H.4.1 y recompras del Tesoro pertenecen a la arquitectura monetaria general. Sin un nexo tokenizado verificable no refuerzan TESIS_05 ni autorizan una ficha de evento.
- **Juicio:** se conserva la hipótesis y su paquete dedicado de cinco sensores. La ausencia de nueva evidencia no la refuta, pero impide elevar soporte o pasarla a vigente.
