# PROMPT CANÓNICO — RADAR DE EVENTOS 231

> **Versión:** 2.2 — 2026-09-19 (TASK_116)
> **Salida única:** Radar_Eventos_YYYY_MM.md  
> **Rango temporal:** 30–60 días (horizonte rodante canónico: corte actual a +60d)

---

## 1. Modelo del sistema

El Sistema 231 distingue cuatro tipos de contenido, definidos en [[Prompt_Actualizacion_Eventos]]: **VECTOR** (fuerza), **TESIS** (hipótesis), **EVENTO** (evidencia y memoria) y **VENTANA/CATALIZADOR** (horizonte futuro). El **RADAR** es la superficie que almacena las ventanas; no constituye una quinta capa ni una segunda fuente de estados.

El Radar detecta, fecha y preclasifica; **NO** abre eventos, **NO** altera estados de vectores y **NO** valida tesis por sí mismo.

---

## 2. Principio fundamental y regla de oro

> **RADAR SEÑALA DÓNDE PUEDE APARECER EVIDENCIA. RADAR NO ES EVIDENCIA.**

Regla absoluta de integridad:
> **`HORIZONTE FUTURO ≠ EVIDENCIA`**

Ningún hito calendarizado o ventana en el Radar puede:
- Modificar el semáforo o nivel de presión de un vector.
- Modificar la dirección de tendencia (↑, →, ↓) de un vector o evento.
- Activar o desactivar dominancia en vectores.
- Sumar o restar carga provisional o canónica al sistema.
- Validar o refutar una tesis ex ante.
- Abrir automáticamente una ficha de EVENTO.

Cualquier cambio en el sistema exige la **resolución efectiva del hito** y la **verificación forense del dato primario**.

Reglas de blindaje forense:
- **Respeto estricto del corte temporal:** Un hito fechado en el mismo día del corte que a las 00:00 no cuente con resolución oficial publicada debe permanecer como hito pendiente de resolución; queda prohibido incorporarlo a ejecutados mediante datos intradía posteriores al corte.
- **Periodo y publicación:** consignar año/mes observado, fecha del documento, enlace específico y consulta para cada dato decisivo; comprobar el año dentro de la fuente antes de consumir el hito. Los hubs son puntos de acceso, no evidencia suficiente de una cifra o acto.
- **Rigor métrico en subastas soberanas:** Diferenciar inequívocamente entre *Average Yield* (rendimiento medio ponderado) y *Yield at Lowest Accepted Price* (rendimiento al precio de corte / cutoff yield).
- **Prohibición de falsos triggers:** Queda prohibido asociar operaciones ordinarias de liquidez o subastas a triggers específicos de eventos activos (p. ej., buybacks a Trigger D o subastas a Trigger A) si no satisfacen textualmente la definición del trigger en la ficha activa.
- **Capacidad real de la fuente y derivación matemática:** Un observable debe estar contenido directamente en la fuente citada o derivarse mediante una operación matemática explícita. No puede exigir un desglose que la fuente no publica (p. ej., inferir producción de nodos o CoWoS desde facturación agregada).

---

## 3. Criterios de admisión y eliminación del calendario macro automático

### 3.1. Test de Admisión Operativa
Para que un hito ingrese a la tabla futura, debe ser posible completar rigurosamente esta formulación causal:

> *“Este hito observa `[mecanismo/variable]` del Evento/Vector/Tesis `[identificador]` y el dato decisivo será `[observable cuantitativo/cualitativo]`.”*

Si no se puede rellenar con precisión, el hito **QUEDA EXCLUIDO**.

### 3.2. Prohibición de Inclusión Automática
Queda prohibida la incorporación mecánica de:
- Ruedas de prensa o decisiones de bancos centrales sin canal de fricción identificado.
- Lecturas de inflación (CPI, PCE, PPI) o empleo (NFP) rutinarias que no alimenten un trigger activo.
- Cumbres multilaterales, conferencias tecnológicas o discursos diplomáticos sin capacidad resolutiva.
- Reuniones de la OPEP+ o subastas del Tesoro sin tensión material o sin hipótesis ex ante.

### 3.3. Criterios Generales
- Fecha o ventana temporal oficial conocida.
- Actor institucional o corporativo identificable.
- Enlace a fuente primaria específica (calendario oficial, publicación legal, registro regulatorio, filing).
- Mecanismo de transmisión material plausible hacia las restricciones del Sistema 231.
- Sin cuotas artificiales por vector: si un vector no presenta hitos en 30–60 días, se declara `HUECO REAL DE COBERTURA` sin inventar eventos.
- Exclusión total de rumores, filtraciones o declaraciones retóricas sin acto normativo o físico.

---

## 4. Campos del Radar 2.0

Cada fila de la tabla calendarizada debe contener doce campos estructurados:

1. **ID:** Identificador unívoco con nomenclatura `E_YYYY_MM_DD_NombreCorto` (o `VEN_YYYY_MM_DD_NombreCorto` para ventanas promovidas).
2. **Fecha / ventana:** Fecha exacta (`YYYY-MM-DD`) o ventana temporal acotada (`YYYY-MM-DD/DD`).
3. **Confirmación:** Estado de certidumbre formal de la fecha:
   - `CONFIRMADO`: Fecha formalmente publicada por la institución u organismo primario responsable.
   - `ANUNCIADO`: Anuncio oficial unilateral o político sin formalización bilateral o legal definitiva.
   - `PROVISIONAL`: Calendario formal sujeto a revisión o condicionalidad expresa.
   - `RECURRENTE OFICIAL`: Serie estadística o subasta con periodicidad legalmente establecida.
4. **Actor:** Institución, organismo, regulador o emisor responsable de la acción o publicación.
5. **Tipo:** Tipología del acto (Subasta soberana, Decisión monetaria, Publicación regulatoria, Cumbre bilateral, Vencimiento fiscal, etc.).
6. **Vector:** Vector primario receptor del impacto (`V01`–`V06`). Transmisiones secundarias en descripción.
7. **Evento sensor:** Evento activo conectado (`Japón/Liquidez — Trigger A`, `Tariff Stack — Trigger B`, `CoWoS — sensor HBM`, etc.) o `NINGUNO — sensor estructural`.
8. **Tesis:** Tesis conectada directamente (`TESIS_01` a `TESIS_06`) o `NINGUNA`.
9. **Observable / Trigger:** De 1 a 4 métricas, variables cuantitativas o resoluciones cualitativas a inspeccionar en el momento del hito.
10. **Prioridad:** Calificación de urgencia analítica preliminar:
    - `RÉGIMEN`: Decisión binaria con capacidad de cambiar reglas de juego institucionales o monetarias.
    - `CRÍTICO`: Trigger próximo con tensión física o financiera observable en fase de activación.
    - `ELEVADO`: Hito capaz de alterar significativamente un chokepoint o acelerar un vector.
    - `LATENTE`: Sensor útil de control sin fricción previa documentada.
    *(Nota: `MONITORIZACIÓN` queda reservada exclusivamente para Observatorios Estructurales fuera de la tabla).*
11. **Descripción factual:** Síntesis del mecanismo físico, normativo o de flujos que se dirime.
12. **Fuente:** Enlace específico al documento primario oficial, orden regulatoria o calendario legal.

---

## 5. Ventanas Enriquecidas

Una **Ventana Enriquecida** es un hito del Radar que, por su excepcional complejidad e impacto sistémico, es promovido a una ficha analítica desplegada dentro del propio Radar. No existe un sistema paralelo fuera de la arquitectura del Radar.

### Criterios de Promoción (debe cumplir TODOS de A a F):
- **A. Temporalidad:** Fecha o ventana oficial estrictamente acotada.
- **B. Multivectorialidad:** Relevancia estructural simultánea para $\ge 2$ vectores o una tesis central.
- **C. Hipótesis causal ex ante:** Hipótesis explicativa previa no trivial sobre los escenarios de resolución.
- **D. Observables acotados:** De 1 a 4 variables o cláusulas observables concretas.
- **E. Resolución finita:** Capacidad de concluir inequívocamente en: `MATERIAL`, `NO MATERIAL`, `POSPUESTO` o `CANCELADO`.
- **F. No rutinario:** Exclusión estricta de series macroeconómicas cíclicas habituales.

### Estructura de Ficha de Ventana Enriquecida:
- Metadatos (ID, Fecha/ventana, Confirmación, Vector primario y secundarios, Evento sensor, Tesis).
- **Hipótesis ex ante:** Mecanismo causal postulado.
- **Observables (1–4):** Datos o acuerdos verificables que definirán el resultado.
- **Resultado material si:** Condiciones que obligan a modificar vectores o eventos.
- **Resultado no material si:** Condiciones de statu quo o absorción sin impacto de régimen.
- **Qué NO significaría:** Límites epistemológicos (evitar sobrerreacciones o malas interpretaciones).
- **Acción al resolverse:** Protocolo de actualización una vez consumado.

---

## 6. Observatorios Estructurales

Los procesos estructurales continuos o tensiones físicas sin una fecha fija conocida **NO se insertan en la tabla calendarizada**. Se registran en la sección de **Observatorios Estructurales**.

Campos de un Observatorio:
- Nombre del Observatorio y Vector(es) afectados.
- Variable física / financiera monitoreada.
- Fuentes primarias continuas (boletines, registros marítimos, despachos de carga, etc.).
- Umbral de fricción o condición de activación para apertura de Evento o promoción al Radar con fecha oficial.

---

## 7. Ciclo de Vida y Protocolo de Retiro de Hitos Ejecutados

Al cumplirse la fecha o ventana de un hito calendarizado, **está estrictamente prohibido que permanezca en la tabla futura**. En la siguiente revisión semanal debe ejecutarse el siguiente protocolo:

1. **Consulta primaria:** Acceso a la fuente oficial competente para verificar la ocurrencia real del hito.
2. **Extracción del dato:** registro de valor/unidad, periodo observado, fecha de publicación, enlace al documento específico y fecha de consulta. Si no se puede verificar, usar `NO VERIFICABLE`, sin inventar un resultado ni probar ausencia por silencio de una portada.
3. **Evaluación de observables:** Comparación frente a los observables o triggers ex ante.
4. **Clasificación de resolución:**
   - `MATERIAL`: El resultado altera restricciones, cruza umbrales o exige revisar Eventos/Vectores/Tesis.
   - `NO MATERIAL`: El evento ocurrió pero el resultado queda absorbido sin alteración de fricción ni cambio de estado.
   - `POSPUESTO`: La fecha fue formalmente aplazada por el organismo emisor (se actualiza fecha en futuros).
   - `CANCELADO`: El hito o cumbre fue anulado formalmente (se retira del radar).
   - `NO VERIFICABLE`: Falta de transparencia o publicación que impide auditar los observables (se documenta la opacidad).
5. **Traslado documental:** Mover la fila a la sección **Hitos Ejecutados / Consumidos** con su resultado real, evento afectado y acción derivada.
6. **Eliminación de futuros:** Supresión de la fila de la tabla futura principal.

---

## 8. Arquitectura y Mantenimiento del Archivo

- En la raíz de `231 Eventos` residirá **un único archivo de Radar activo**: `Radar_Eventos_YYYY_MM.md`.
- Al inicio de un nuevo mes calendario, o ante una reestructuración canónica autorizada, la versión vigente anterior se traslada a la subcarpeta `archivo/` aplicando la convención de sufijo de revisión: `Radar_Eventos_YYYY_MM_rN.md`.
- No deben coexistir radares activos de diferentes meses ni copias duplicadas en la raíz.

---

## 9. Lista de Control de Integridad Radar 2.0

Antes de dar por validado un Radar mensual o semanal:
- [ ] Horizonte temporal estrictamente comprendido entre 30 y 60 días desde la fecha de corte.
- [ ] Todos los IDs unívocos con formato estándar (`E_...` o `VEN_...`).
- [ ] Recuento declarado en encabezados idéntico al recuento real de filas de la tabla.
- [ ] Todas las filas tienen fecha/ventana, actor, observables, prioridad y estado del respaldo. Las referencias pendientes se declaran; presencia de enlace no equivale a contraste completo.
- [ ] Datos decisivos con periodo, publicación, enlace específico y consulta; ningún dato de otro año reutilizado como actual.
- [ ] Cifras de cobertura factual limitadas a lo realmente comprobado; nunca 100% por el mero recuento de URLs.
- [ ] Todas las filas incorporan su estado de confirmación (`CONFIRMADO`, `ANUNCIADO`, `PROVISIONAL`, `RECURRENTE OFICIAL`).
- [ ] Cero hitos vencidos o ejecutados dentro de la tabla futura.
- [ ] Sección de Observatorios Estructurales separada de la tabla calendarizada.
- [ ] Ventanas Enriquecidas auditadas contra los seis criterios (A–F) de promoción.
- [ ] Huecos reales de cobertura declarados explícitamente sin relleno artificial.
- [ ] Cero alteraciones ex ante de semáforos, tendencias, cargas o apertura automática de EVENTOS.

## Rectificación operativa — 19/09/2026 (TASK_116)

Para cada ejecución, el horizonte es [fecha local del corte, fecha local del corte + 60 días], ambos extremos incluidos: 60 días transcurridos y 61 fechas de calendario. Esta convención explícita evita utilizar el domingo nominal futuro como punto de partida. Se admiten ventanas iniciadas antes del corte cuyo final no haya vencido, identificadas como en curso. Las fechas de tabla se expresan completas (AAAA-MM-DD/AAAA-MM-DD).

El número de filas es resultado, no objetivo. Recuenta prioridades, vectores, IDs, doce columnas, fuentes y ventanas tras altas/bajas. Diferencia fecha confirmada ahora, calendario provisional, recurrencia oficial y fecha heredada no recontrastada. Presencia de enlace no equivale a verificación factual. No rellenes el tramo final con reuniones inventadas.

En hitos consumidos, MATERIAL significa información que cambia una evaluación o una restricción, no activación automática de un evento. Conserva las resoluciones históricas y añade una rectificación si se detecta error. No llames JMMC a una reunión de un subconjunto de países OPEP+ sin respaldo específico. No des por renovadas seis mensualidades de sanciones si el acto solo prorroga días.
