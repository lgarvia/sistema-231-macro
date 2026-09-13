* **Estado:** ⚫ AGOTADO
* **Fecha_cierre:** 2026-04-26
# Descripción del evento

## Estado operativo
⚫ AGOTADO

## Cierre del evento
- **Fecha de cierre:** 2026-05-01
- **Tipo de cierre:** Pérdida de relevancia
- **Desenlace:** El trigger continuo de liquidez en el mercado Repo no derivó en una ruptura operativa durante el ciclo de abril. El riesgo se integra en la monitorización estructural del RADAR.

Este evento se recategoriza por influencia directa del shock energético exterior que impide pivotar a la Fed, concentrando la tensión en las reservas del repo.

## Variable núcleo

- Nivel de saldos depositados en la facilidad ON RRP y spread de la tasa SOFR frente a Fed Funds.

## Condición mínima de activación

- Saldo del programa ON RRP aproximándose a cero (agotamiento de colchón) derivando en un pico de volatilidad interbancaria.

## Señal dominante

- Tasa SOFR (Secured Overnight Financing Rate).

## Contexto

El sistema financiero estadounidense enfrenta posibles episodios de estrés operativo ante el agotamiento paulatino de las facilidades Overnight Reverse Repo (ON RRP) de la Reserva Federal. La continua necesidad del Tesoro de emitir volúmenes titánicos de deuda choca con un mercado de reservas que podría tornarse ilíquido súbitamente, generando repuntes esporádicos en las tasas de financiamiento a corto plazo.

**Chokepoint potencial afectado:** Mercado de Repos (Repo Market) y cámaras de compensación en EE.UU.

---

## Acción asociada

(Vacío)

## Fichas relacionadas

- [[VECTOR_01_Arquitectura_monetaria_global]]: Efectos de la dominancia fiscal sobre la liquidez disponible del sistema.
- [[20 Académico/23 MOC/231 Eventos/Evento_E1_2026_01_30_Fed_Transicion_Warsh]]: Inercia de política monetaria en la que puede detonar esta tensión.
- [[50 Archivo/52 LinkedIn/2026_04_13_Más_de_22_billones_de_dólares_en_la_sombra]]: Análisis directo sobre la escala y opacidad del crédito privado y su vulnerabilidad frente a shocks de liquidez.
- [[50 Archivo/52 LinkedIn/2026_04_17_La_curva_de_tipos_lleva_décadas_anunciando]]: Perspectiva histórica de la curva de tipos como mecanismo de alerta ante la tensión estructural.

---

## Hechos verificables

- Disminución estadística demostrable de los saldos depositados en el programa ON RRP de la Reserva Federal de Nueva York a lo largo de los últimos trimestres.
- Crecimiento acelerado en las subastas de letras (T-Bills) y bonos de largo plazo por parte del Departamento del Tesoro.
- Actores: Reserva Federal (Front Office de NY), Departamento del Tesoro, Primary Dealers institucionales.

---

## Narrativas en conflicto

- Narrativa de transición elástica: El mercado de repo es suficientemente profundo para asimilar el shock de oferta del Tesoro sin que se disparen las tasas interbancarias ni intervenga la Fed.
- Narrativa de "crujido" (plumbing crisis): La escasez subyacente de liquidez obligará a la Fed a intervenir fuera de su mandato técnico, deteniendo el QT o volviendo a monetizar deuda para defender el suelo del sistema de pagos.

---

## Incentivos y poder

- El Departamento del Tesoro (Ejecutivo) necesita garantizar la colocación de deuda para sostener la actividad estatal (dominancia fiscal).
- La Reserva Federal busca evitar una repetición de la crisis del mercado repo de 2019, protegiendo su ya desgastada credibilidad técnica y el funcionamiento armónico del mercado de reservas.

---

## Tesis (Luis)

El mercado repo ya no es sólo el termómetro del sistema regulado, sino la válvula de escape de una crisis de liquidez sistémica de la que participan más de 22 billones de dólares operando en el *Shadow Banking*. La curva de tipos invertida lleva décadas advirtiendo de este estrangulamiento: cuando la SOFR se dispara, el problema no es que falte dinero en los bancos, es que falta liquidez en un universo de fondos de crédito paralelos que la Reserva Federal no puede rescatar directamente. La tensión actual entre el agotamiento del ON RRP, la dominancia fiscal del Tesoro (QRA) y este endeudamiento invisible hace que el potencial de crujido sea sistémicamente mayor y más incontrolable que en 2019.

---

## Implicaciones

- Restricción de crédito sistémico si las cámaras de compensación (FICC) elevan los requerimientos de margen.
- Intervención de emergencia de la Fed, frenando el QT o activando facilidades permanentes, lo que vulneraría su discurso anti-inflación.

---

## Señales a vigilar

- Variación diaria del volumen depositado en el ON RRP.
- Spreads de la tasa SOFR respecto al límite superior de los Fed Funds al final de la jornada y fin de mes.
- Volumen de colocación y bid-to-cover ratio en las grandes subastas del US Treasury.

---

## Vector dominante

* **Vector principal:** V01
* **Justificación:** Fricción base de liquidez, agravada por $22T de shadow banking operando fuera de la red de seguridad.

* **Vectores secundarios (si aplica):**
  * V06 → Trazabilidad cruzada obligatoria.

---

## Estado 

🟠 Activación avanzada

## Triggers de activación (E0 → E1)

- El saldo diario del programa ON RRP alcanza niveles estadísticos cero.
- Disparo sostenido (spike) de la tasa SOFR superior a 50 puntos básicos por encima de la banda alta de los Fed Funds.
- Comunicado oficial de la Reserva Federal anunciando la reinyección permanente de liquidez (fin temporal del QT) o la activación de Standing Repo Facilities de emergencia.
- Fallos confirmados en la liquidación intradía institucional de bonos del Tesoro (FICC).

---

## Actualización factual reciente
- **26/04/2026**: Integración operativa: La asimetría entre el volumen del Shadow Banking ($22 billones) y el perímetro de seguridad de la Fed (Standing Repo Facility) se consolida como el principal riesgo de ruptura estructural del Q2.
- **19/04/2026**: Las métricas de liquidez diaria muestran un drenaje continuo del ON RRP ante alta emisión de T-Bills. La tensión se acumula pre-Refunding.

- **18/03/2026**: FOMC mantiene tipos en 3.50%–3.75%. Powell anuncia intención de permanecer como Chair pro tem. La política monetaria opera bajo presión externa (shock energético Brent +50%) y presión interna (interinidad institucional).
- **27/03/2026**: SOFR cotiza en 3.63%, estable pero con precedentes preocupantes. En septiembre 2025, la Standing Repo Facility (SRF) registró su mayor disposición desde su creación (~$18.5B en un solo día), con SOFR disparándose a 4.42%. El episodio confirmó el adelgazamiento progresivo de las reservas bancarias.
- **31/03/2026**: El FSB y analistas alertan de riesgos de estabilidad en el mercado repo por el estrechamiento continuado de reservas. Los saldos ON RRP siguen en mínimos estructurales. El Tesoro afronta el Quarterly Refunding de mayo con Brent por encima de $100/barril y un entorno fiscal de $38T de deuda.
- **31/03/2026**: Contexto agravante: la guerra en Medio Oriente (día 30+) genera un shock inflacionario importado que complica la hoja de ruta del QT y podría forzar a la Fed a intervenir prematuramente en el mercado de repos para defender la estabilidad del sistema de pagos.

---

## Pulsos de Salida

> Registro de cuándo este evento ha alimentado un output observable. Campo de trazabilidad — no es gate de archivado.

| Fecha | Canal | Referencia |
| :--- | :--- | :--- |
| — | — | Sin pulsos registrados aún |

---

Estado del evento: 🟠 Activación avanzada (pre-ruptura operativa - drenaje ON RRP, presión Treasury, contexto energético)
Última actualización: 2026-04-13
Estado cognitivo: Observación intensificada (Riesgo de fontanería global)
