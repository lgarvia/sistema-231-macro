# Radar de Eventos - 2026-04

Horizonte temporal: 45–60 días (19 de abril - mediados de junio)

## Salida en dos capas

### CAPA 1: TABLA DE DETECCIÓN

La columna "ID" debe tener formato `E_YYYY_MM_DD_Nombre_corto` (ej: `E_2026_04_24_BoJ_Yen`). El ID debe ser único dentro del radar y coincidir con el nombre que tendría el EVENTO de llegar a crearse.

| ID | Fecha | Actor / Institución | Tipo | Vector (principal) | Trigger | Descripción factual brief |
|:--- |:--- |:--- |:--- |:--- |:--- |:--- |
| E_2026_04_21_Tesla_Earnings | 2026-04-21 | Tesla | Resultados | V05 | | Resultados Q1 con presión de márgenes por guerra de precios eléctrica y subsidios.<br>Vectores secundarios: V04. |
| E_2026_04_23_Hyperscalers | 2026-04-23 | Microsoft, Alphabet, Meta | Resultados | V03 | | Confirmación de OPEX irreversible en compute e IA frente a escasez de energía. |
| E_2026_04_24_BoJ_Decision | 2026-04-24 | Bank of Japan | Política Monetaria | V01 | ✅ | Decisión de subir tipos ante inflación, riesgo inminente de drenaje de Treasuries.<br>Chokepoint potencial afectado: Mercado de Treasuries. |
| E_2026_04_25_Auto_China | 2026-04-25 | Industria Automotriz | Sectorial | V05 | | Salón del Automóvil en China evidenciando el relevo generacional de la movilidad tradicional.<br>Vectores secundarios: V04. |
| E_2026_04_30_BCE_Consejo | 2026-04-30 | BCE | Política Monetaria | V01 | ✅ | Decisión de tipos bajo asfixia industrial europea e inflación aguda por shock físico.<br>Vectores secundarios: V02, V05. |
| E_2026_04_30_BRICS_Finanzas | 2026-04-30 | BRICS+ | Foro multilateral | V06 | | Reunión para avanzar sistema multidivisa y crear liquidez sin paso por dólares.<br>Vectores secundarios: V01. |
| E_2026_05_01_US_Refunding | 2026-05-01 | US Treasury | Emisión Deuda | V01 | ✅ | Emisión trimestral absorbiendo liquidez crítica en un mercado repo ya tenso.<br>Chokepoint potencial afectado: Repo market. |
| E_2026_05_05_Cumbre_US_China | 2026-05-05 | EE.UU. y China | Cumbre bilateral | V04 | | Expectativas reducidas a pactos comerciales cerrados ante inoperancia de OMC.<br>Vectores secundarios: V06. |
| E_2026_05_06_Fed_FOMC | 2026-05-06 | Fed | Política Monetaria | V01 | ✅ | Límite funcional ante dominancia fiscal total e inflación estructural importada. |
| E_2026_05_09_Russia_Victory | 2026-05-09 | Rusia | Acto geopolítico | V06 | | Posible alteración en teatro europeo aprovechando la distracción bélica occidental. |
| E_2026_05_15_Powell_Term | 2026-05-15 | Fed / Powell | Institucional | V01 | | Expiración mandato Pro tem, aumentando vacío operativo en arquitectura monetaria. |
| E_2026_05_20_Taiwan_Inaug | 2026-05-20 | China / Taiwán | Seguridad | V06 | | Fecha clave de asunción de mandato, máxima probabilidad de fricción naval disuasoria.<br>Vectores secundarios: V03.<br>Chokepoint potencial afectado: Estrecho de Taiwán. |
| E_2026_06_01_OPEP_Meeting | 2026-06-01 | OPEP+ | Política Energética | V02 | ✅ | Decisión global de cuotas superponiéndose al shock estructural persistente en Irán.<br>Chokepoint potencial afectado: Estrecho de Ormuz. |

---

### CAPA 2: CLASIFICACIÓN EN RADAR OPERATIVO

## Clasificación por fricción

### 🔴 CRÍTICO
* E_2026_04_30_BCE_Consejo → V01 | Trigger: Sí
* E_2026_05_01_US_Refunding → V01 | Trigger: Sí
* E_2026_05_06_Fed_FOMC → V01 | Trigger: Sí
* E_2026_06_01_OPEP_Meeting → V02 | Trigger: Sí

### 🟠 ELEVADO
* E_2026_04_24_BoJ_Decision → V01 | Trigger: Sí
* E_2026_05_20_Taiwan_Inaug → V06 | Trigger: No
* E_2026_05_05_Cumbre_US_China → V04 | Trigger: No
* E_2026_04_23_Hyperscalers → V03 | Trigger: No

### 🟡 LATENTE
* E_2026_05_09_Russia_Victory → V06 | Trigger: No
* E_2026_04_30_BRICS_Finanzas → V06 | Trigger: No
* E_2026_05_15_Powell_Term → V01 | Trigger: No

### ⚪ MONITORIZACIÓN
* E_2026_04_21_Tesla_Earnings → V05 | Trigger: No
* E_2026_04_25_Auto_China → V05 | Trigger: No

---

## Reglas de Clasificación Operativa

La clasificación en bloques no depende de la fecha, sino de:
* Activación de trigger
* Proximidad temporal + tensión en vector dominante
* Existencia de fricción observable en métricas

El vector asignado en el RADAR debe coincidir con el vector dominante que tendría el EVENTO si se abriera. 
Si un evento parece pertenecer a múltiples vectores, seleccionar exclusivamente aquel que represente la restricción material dominante (no el contexto narrativo).

**REGLA CLAVE:**
El RADAR sigue siendo un sensor. La clasificación por fricción es preliminar y no sustituye la validación mediante EVENTOS.

---

## Cobertura por vector (Resumen)

| Vector | Eventos detectados |
|:--- |:--- |
| V01 Arquitectura monetaria | 6 |
| V02 Energía | 1 |
| V03 Semiconductores | 1 |
| V04 Comercio | 1 |
| V05 Industria / movilidad | 2 |
| V06 Orden geopolítico | 3 |

---

## Auditoría interna del RADAR

1. **¿Hay algún vector con 0 eventos detectados?**
   No.
2. **¿Hay algún vector sobrerrepresentado (>40% del total)?**
   Sí. El vector V01 concentra el 46% de los eventos (6 de 13).
3. **¿Hay eventos difíciles de clasificar en un único vector?**
   Sí. `E_2026_04_30_BCE_Consejo` requiere forzar la distinción entre un problema puramente monetario (V01 dominante elegido) y el shock de oferta físico que lo motiva (V02). `E_2026_04_30_BRICS_Finanzas` camina en el límite estricto entre orden posicional (V06 dominante elegido) y arquitectura de liquidez paralela (V01).
4. **¿Hay concentración anómala en algún bloque de fricción?**
   Sí. Concentración crítica entre el 30 de abril y el 6 de mayo puramente anclada al V01 y V02 (BCE + US Refunding + FOMC).
5. **¿Algún evento parece ruido pese a haber pasado filtros?**
   Sí. `E_2026_04_21_Tesla_Earnings` bordea el ruido sectorial-corporativo y posiblemente no actúe jamás como limitante a nivel sistémico, pasando un filtro demasiado laxo para V05.
