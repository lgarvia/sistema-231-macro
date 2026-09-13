# Prompt: Reforma estructural del Sistema de Eventos (2026-04-26)

## Contexto del Sistema

Este prompt NO actualiza eventos individuales (para eso → `Prompt_Actualizacion_Eventos.md`).
Este prompt opera sobre la **infraestructura** del sistema 231 Eventos: arregla incoherencias estructurales detectadas durante la auditoría del 2026-04-26.

Capas afectadas:
1. **VECTORES**: NO se tocan (gobernanza Front Office).
2. **RADAR (`Radar_Eventos_2026_04.md`)**: solo se cita como referencia de cobertura. NO se reescribe.
3. **EVENTOS (`Evento_E0_*` y `Evento_E1_*`)**: aquí ocurre toda la intervención.
4. **AUTOMATISMO (`update_estados_log.txt`)**: se diagnostica, NO se reescribe (lo decide Luis).

---

## Diagnóstico previo (causa raíz de la reforma)

Auditoría 2026-04-26 detectó:
- **Estado triple**: el script `update_estados_log.txt` modifica `Estado:` en frontmatter pero deja secciones del cuerpo con estados antiguos. Resultado: una misma ficha declara dos estados distintos (NFP, CPI, QRA confirmados).
- **Eventos pasados sin cierre formal** (Repo 04-01, Comercio 04-15, Hyperscalers 04-23, BoJ 04-24): siguen activos en directorio + Dashboard cuando ya pasaron.
- **Desincronización fecha QRA**: nombre de archivo `Evento_E0_2026_05_01_US_Treasury_Quarterly_Refunding.md` vs RADAR que sitúa QRA en `2026-04-29`.
- **10 eventos del RADAR sin ficha asociada**: gap entre sensor (RADAR) y backend documental (fichas).
- **Medio Oriente Escalada (E1)**: clasificado V02 cuando opera transversalmente con V01/V05/V06.
- **Dominancia V01 (52%)**: ya reconocida por la auditoría interna del RADAR. NO requiere acción aquí.

---

## Proceso de Ejecución (6 bloques)

Ejecutar en orden estricto. Entre bloques, no consolidar; reportar al final.

### BLOQUE 1 — Resolver Estado Triple

**Regla canónica:** el `Estado:` del frontmatter YAML es la fuente única de verdad. Cualquier referencia al estado dentro del cuerpo debe coincidir, o eliminarse.

Para cada ficha en `20 Académico/23 MOC/231 Eventos/Evento_E*.md`:

1. Leer `Estado:` del frontmatter.
2. Buscar en el cuerpo cualquier mención literal de estado (🟡 LATENTE, 🟠 ELEVADO, 🔴 CRÍTICO, ⚫ AGOTADO, ⚪ MONITORIZACIÓN).
3. Si discrepancia: actualizar el cuerpo al valor del frontmatter. **NO al revés.**
4. Si la sección de cuerpo es redundante (solo repite el frontmatter sin añadir contexto), eliminarla.

Casos confirmados que requieren intervención:
- `Evento_E0_2026_05_08_US_Mercado_Laboral_NFP.md`: frontmatter ⚪, cuerpo 🟡.
- `Evento_E0_2026_05_13_US_Inflacion_CPI_PCE.md`: misma divergencia.
- `Evento_E0_2026_05_01_US_Treasury_Quarterly_Refunding.md`: estado triple confirmado.

### BLOQUE 2 — Cerrar y archivar eventos pasados

Cuatro eventos han concluido factualmente y deben pasar a archivo:

| Ficha | Razón cierre |
|:---|:---|
| `Evento_E0_2026_04_01_Sistema_Financiero_Repo_Market.md` | Trigger continuo sin escalada en mes; sustituir por monitorización en RADAR siguiente. |
| `Evento_E0_2026_04_15_Comercio_Global_Riesgo_Maritimo.md` | Trigger continuo sin escalada en mes; sustituir por monitorización en RADAR siguiente. |
| `Evento_E0_2026_04_23_Hyperscalers_CAPEX_AI.md` | Earnings semanal completada (Alphabet/MSFT/Meta/Amazon/Apple) entre 28-abr y 1-may. |
| `Evento_E0_2026_04_24_BoJ_Normalizacion_Yen.md` | Decisión 24-abr ejecutada. |

Para cada uno:
1. Cambiar frontmatter a `Estado: ⚫ AGOTADO` y añadir `Fecha_cierre: 2026-04-26`.
2. Añadir bloque `## Cierre del evento` al final con: fecha de cierre, tipo de cierre (Vencimiento de fecha / Trigger ejecutado / Pérdida de relevancia), y línea factual del desenlace.
3. Mover físicamente a `50 Archivo/231 Eventos cerrados/` (crear carpeta si no existe).
4. Registrar la operación en `EVENTOS_CERRADOS_LOG.md` (ver Bloque 6 / o archivo ya existente si Luis lo creó previamente).

### BLOQUE 3 — Reconciliar fecha QRA

Inconsistencia confirmada:
- Nombre de archivo: `Evento_E0_2026_05_01_US_Treasury_Quarterly_Refunding.md`
- RADAR (línea 12): `E_2026_04_29_US_QRA` con fecha `2026-04-29`
- Frontmatter del archivo: revisar — fuente esperada de verdad.

Resolución:
1. Leer el frontmatter `Fecha_Trigger:` o equivalente.
2. **El RADAR es la fuente correcta**: QRA es 29-abr.
3. Renombrar el archivo a `Evento_E0_2026_04_29_US_Treasury_Quarterly_Refunding.md`.
4. Actualizar todas las wikilinks `[[...05_01_US_Treasury...]]` a `[[...04_29_US_Treasury...]]` en `00 Dashboard.md`, `00_AGENT_SNAPSHOT.md` y cualquier post LinkedIn que lo cite.

### BLOQUE 4 — Crear stubs para eventos del RADAR sin ficha

10 eventos del RADAR no tienen ficha. Generar stub mínimo en orden de prioridad (críticos primero):

**Prioridad 1 — Triggers activos del próximo ciclo:**
1. `Evento_E0_2026_04_28_ASML_Earnings.md` (V03)
2. `Evento_E0_2026_05_07_BoE_Decision.md` (V01)
3. `Evento_E0_2026_06_01_OPEP_Meeting.md` (V02, 🔴 CRÍTICO)
4. `Evento_E0_2026_06_04_BCE_Consejo_2.md` (V01, 🟡 LATENTE)
5. `Evento_E0_2026_06_11_Fed_FOMC_2.md` (V01, 🟠 ELEVADO)

**Prioridad 2 — Eventos de régimen / binarios:**
6. `Evento_E0_2026_05_18_Xi_Putin_Meet.md` (V06)
7. `Evento_E0_2026_05_25_Tech_AI_Summit.md` (V05, ⚫ régimen)
8. `Evento_E0_2026_06_06_EU_Elections.md` (V06, ⚫ régimen)

**Prioridad 3 — Sensores macro (puede agruparse en un solo "Observatorio macro" si se prefiere):**
9. `Evento_E0_2026_04_30_China_PMI.md` (V05)
10. `Evento_E0_2026_05_01_US_ISM_Manuf.md` (V05)

**Plantilla del stub** (estricta, no añadir secciones):

```markdown
---
Tipo: Evento E0
Estado: 🟡 LATENTE
Vector_Principal: V0X
Vectores_Secundarios: []
Fecha_Trigger: AAAA-MM-DD
Origen_RADAR: Radar_Eventos_2026_04
---

# [Nombre del Evento]

## Trigger
[Trigger del RADAR, copiado literal.]

## Tesis (Luis)
[PENDIENTE — reservada al director del sistema.]

## Cronología factual
- *(vacío hasta primera entrada verificable)*

## Señales a vigilar
- [Inferidas de los chokepoints del Vector dominante.]

## Implicaciones
- *(PENDIENTE)*
```

**Prohibición:** NO escribir la `Tesis (Luis)`. Dejar el placeholder. Es competencia exclusiva del Front Office.

### BLOQUE 5 — Reclasificar Medio Oriente Escalada como transversal

Ficha: `Evento_E1_2026_02_28_Medio_Oriente_Escalada.md`

Frontmatter actual probable: `Vector_Principal: V02`.

Operación:
1. Mantener `Vector_Principal: V02` (energía sigue siendo el chokepoint material).
2. Añadir `Vectores_Secundarios: [V01, V05, V06]` con justificación de una línea cada uno:
   - V01: el Brent metiendo inflación importada bloquea pivote BCE/Fed.
   - V05: industria europea (auto, química) golpeada por coste energético.
   - V06: realineamiento BRICS+/Golfo en torno al chokepoint de Ormuz.
3. NO reescribir Tesis ni Cronología.

### BLOQUE 6 — Diagnóstico del automatismo `update_estados_log.txt` (NO ejecutar reescritura)

Localizar `update_estados_log.txt` o equivalente en `231 Eventos/`. Diagnosticar:
1. ¿Qué campos del frontmatter modifica?
2. ¿Toca el cuerpo del documento?
3. ¿Documenta sus operaciones en `_COMM_LOG.md` o equivalente?

Devolver el diagnóstico al Log de finalización. **NO modificar el script.** Decisión sobre arquitectura del automatismo: Luis (Front Office).

---

## Prohibiciones absolutas

❌ Reescribir la `Tesis (Luis)` de cualquier ficha (existente o nueva).
❌ Modificar fichas VECTOR (`VECTOR_*.md`).
❌ Reescribir el `Radar_Eventos_2026_04.md` (es snapshot histórico).
❌ Modificar el script `update_estados_log.txt`.
❌ Borrar contenido factual histórico de cronologías (acumulación forense).
❌ Generar narrativa o adjetivos en stubs.

---

## Formato de Output de Retorno (Log de Finalización)

### 1. Bloque 1 — Estados conciliados
Lista de fichas modificadas: `[Nombre]` → Estado canónico (frontmatter): `[X]` | Cuerpo modificado: `[sí/no]` | Sección redundante eliminada: `[sí/no]`.

### 2. Bloque 2 — Eventos archivados
Lista de las 4 fichas movidas a archivo, con timestamp.

### 3. Bloque 3 — QRA reconciliada
Confirmación de renombrado + wikilinks actualizados (lista de archivos tocados).

### 4. Bloque 4 — Stubs creados
Listado de las 10 fichas nuevas con su path y prioridad asignada.

### 5. Bloque 5 — Medio Oriente
Confirmación de reclasificación con vectores secundarios añadidos.

### 6. Bloque 6 — Diagnóstico del automatismo
Reporte estructurado del comportamiento de `update_estados_log.txt` (no modificación).

### 7. Conflictos detectados
Cualquier ambigüedad o contradicción que requiera decisión Luis (Front Office).
