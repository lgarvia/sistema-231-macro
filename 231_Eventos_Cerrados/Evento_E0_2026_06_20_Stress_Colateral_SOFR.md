---
titulo: "Stress Colateral y Liquidez SOFR"
fecha: 2026-06-20
source: Fed de Nueva York / Treasury / FRED
url: https://www.newyorkfed.org/
vector: "[[VECTOR_01_Arquitectura_monetaria_global]]"
moc: "[[MOC_Politica_Monetaria]]"
tags: [monetario, sofr, repo, liquidez]
tipo: evento
Fecha_cierre: 2026-07-18
Estado: "⚫ AGOTADO"
---

# EVENTO: E0_2026_06_20_Stress_Colateral_SOFR

## 1. SNAPSHOT ACTUAL
- **Estado:** ⚫ Agotado — FALSA ALARMA; ARCHIVADO
- **Nivel de presión:** MODERADA (P3)
- **Dirección de tendencia:** ↓ Descomprimiendo
- **Peso estructural:** 4
- **Última actualización:** 2026-07-18
- **Vector primario:** [[VECTOR_01_Arquitectura_monetaria_global]]
- **Vectores secundarios:** N/A (Fricción pura de nivel 1)
- **KPIs Actuales:**
  - SOFR: 3,62% el 16/07/2026.
  - EFFR: 3,63% el 16/07/2026; IORB vigente: 3,65%.
  - Spread SOFR–IORB: -3 pb, sin spike superior a +50 pb.
  - Saldo ON RRP: 0,278 B$ el 14/07/2026.
  - SRF y subastas: no consta activación del umbral de 50 B$ durante tres sesiones ni subasta 10Y/30Y con bid-to-cover inferior a 2,0x.
  - Régimen de reservas: la Fed mantiene reservas amplias y compras de gestión de reservas.

## 2. CONDICIONES DE ACTIVACIÓN
- **Trigger A:** Spike intradía del SOFR superior a 50 bps por encima del límite superior del rango de los Fed Funds, sin absorción automática del mercado.
- **Trigger B:** Uso agregado de la Standing Repo Facility (SRF) por encima de $50 Billones diarios durante tres jornadas consecutivas.
- **Trigger C:** Subasta oficial del US Treasury (10Y o 30Y) calificada como "fallida" con un ratio bid-to-cover inferior a 2.0x.
- **Trigger D:** Comunicado de emergencia de la Reserva Federal (bajo la administración Warsh) anunciando una pausa temporal del QT (Quantitative Tightening) para preservar la liquidez bancaria.

## 3. CONTEXTO Y SEÑAL DOMINANTE
La tasa SOFR presionando por encima del IORB y el uso de la Standing Repo Facility indican que la liquidez del sistema ya no es abundante, obligando al mercado a buscar oxígeno diario en los mecanismos de emergencia. El sistema de cañerías del dólar ha agotado el colchón del ON RRP. Con el Departamento del Tesoro (US Treasury) emitiendo volúmenes récord para financiar $39T de deuda bajo régimen de Dominancia Fiscal, la oferta de colateral supera la capacidad del balance de los Primary Dealers. El mercado interbancario opera con el oxígeno justo, y la liquidez ha pasado de "abundante" a "ajustada". En este entorno, los compradores no tradicionales, como las stablecoins (dólar sintético), están actuando como el último comprador marginal fiable de letras a corto plazo (T-Bills).

## 4. TESIS (Luis)
El mercado repo ya no es un termómetro, es la válvula de escape. Cuando el SOFR cruje, el problema no es que falte liquidez en los bancos, es que falta colateral para asimilar la deuda de un Estado en dominancia fiscal. Las stablecoins están absorbiendo la oferta corta porque el mercado institucional ya no puede digerir la curva larga sin quebrar. La Fed de Warsh no vigilará el IPC; vigilará que las subastas de deuda no queden desiertas.

## 5. IMPLICACIONES Y TRANSMISIÓN
- **Transmisión:** V01 → V04 (Valor del Dólar) → V06 (Deuda Global).
- **Implicaciones:** Un fallo en la cámara de compensación (FICC) por estrés de repo destruiría temporalmente la credibilidad de liquidación del dólar. En caso de ruptura, forzará a una intervención directa de la Fed comprando bonos (inyección de reservas encubierta) en pleno entorno inflacionario, rompiendo su mandato estatutario. Si no se activa, el Tesoro se verá forzado a concentrar todas las emisiones en letras cortas (T-Bills), acortando peligrosamente la duración de la deuda nacional.

## 6. HISTORIAL FACTUAL
- **01/05/2026**: El saldo de la facilidad ON RRP mantiene una tendencia de vaciado persistente en comparación con los máximos históricos.
- **13/05/2026**: Aprobación de K. Warsh como nuevo Chair de la Fed. El mercado descuenta un enfoque de infraestructura de mercado por encima de tipos.
- **15/05/2026**: El spread del repo garantizado SOFR frente al tipo objetivo registra un tensionamiento temporal, incrementando solicitudes a la Fed.
- **28/06/2026**: Los saldos diarios de la facilidad Overnight Reverse Repo (ON RRP) de la Fed de Nueva York se consolidan en mínimos históricos en el rango de los $570M–$640M. A pesar del vaciado de liquidez en esta facilidad, el Secured Overnight Financing Rate (SOFR) cotiza estable cerca del 3.60%–3.64%, manteniéndose sin picos de estrés frente al EFFR tras la decisión del FOMC del 17 de junio de mantener los tipos en el rango 3.50%–3.75.
- **20/06/2026**: Monitoreo de liquidez interbancaria al cierre de la semana muestra estabilidad en el spread SOFR vs Fed Funds (en torno a los -2.0 bps). La publicación de Luis el 15 de junio sobre Tether analiza cómo las stablecoins actúan de facto como compradores marginales de las letras a corto plazo (T-Bills) emitidas masivamente bajo dominancia fiscal, amortiguando la sequía de colaterales institucionales.
- **15/05/2026**: El descenso de los saldos de la facilidad ON RRP de la Reserva Federal de Nueva York incrementa la sensibilidad de las condiciones de liquidez interbancaria durante los ciclos de subastas del Tesoro estadounidense. Fuente: Federal Reserve Bank of New York / FRED.

## 7. ACTUALIZACIÓN FACTUAL RECIENTE
- **18/07/2026**: Los datos oficiales muestran **SOFR 3,62%** y **EFFR 3,63%** el 16/07, sin el diferencial de +50 pb exigido por el Trigger A; el saldo ON RRP fue de **0,278 B$** el 14/07. Tampoco se verifica uso de SRF superior a 50 B$ durante tres sesiones, subasta 10Y/30Y fallida ni pausa de emergencia del QT. La Fed mantiene el diagnóstico de reservas amplias y el NY Fed continúa compras de gestión de reservas. **Acción: archivar como falsa alarma, autorizada por Front Office el 18/07/2026.** Fuentes: [FRED SOFR](https://fred.stlouisfed.org/series/SOFR), [FRED EFFR](https://fred.stlouisfed.org/series/EFFR), [FRED ON RRP](https://fred.stlouisfed.org/series/RRPONTSYD), [NY Fed](https://tellerwindow.newyorkfed.org/2026/03/31/the-implementation-of-reserve-management-purchases-to-maintain-ample-reserves/).

## 8. CIERRE DEL EVENTO
- **Fecha de cierre:** 2026-07-18
- **Tipo de cierre:** Falsa alarma / Pérdida de relevancia
- **Desenlace factual:** Ninguno de los cuatro triggers se activó; SOFR, EFFR, SRF y las subastas observadas no acreditan estrés operativo. El riesgo de liquidez permanece monitorizado en V01 y en los hitos FOMC/QRA del RADAR.
