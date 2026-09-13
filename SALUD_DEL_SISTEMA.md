# SALUD DEL SISTEMA 231

> **Actualizado:** 2026-08-29  
> **Estado:** operativo tras calibración semanal W35  
> **Copia previa:** 231 Eventos_pre_reparacion_2026_08_17.zip

## 1. Inventario canónico

- **Eventos activos:** 5.
- **E0 activos:** 3.
- **E1 activos:** 2.
- **Eventos cerrados en directorio canónico:** 16.
- **Radar vigente:** 1.
- **Hitos del radar:** 23.
- **Ventana del radar:** 30/08–30/09/2026 (y octubre).
- **Tesis activas:** 6.
- **Vectores activos:** 6.

## 2. Calidad verificable

| Control | Resultado | Método |
|:---|:---:|:---|
| Fichas activas con fecha de revisión 29/08 | 5/5 | Campo “Última actualización” |
| Fichas activas con triggers explícitos | 5/5 | Revisión de secciones de activación |
| Última entrada con fuente primaria específica | 5/5 | URL de documento o página institucional concreta |
| Eventos de fondo retirados del activo | 3 | Taiwán, GNSS y pensiones |
| Cifras 2024 usadas como 2026 | 0 en superficies activas | Búsqueda de la contaminación conocida |
| Radar con fecha, ID y fuente por fila | 23/23 | Recuento de tabla |
| Discrepancia entre total declarado y filas | 0 | 23 filas / total 23 |

No se publica una etiqueta genérica de “entropía baja”: la salud se expresa mediante controles observables y reproducibles.

## 3. Eventos activos

| Evento | Clase | Presión | Tendencia | Peso | Vector primario |
|:---|:---:|:---:|:---:|:---:|:---:|
| [[Evento_E1_2026_06_15_Lloyds_War_Risk_Ormuz_BabelMandeb]] | E1 | P4 | ↑ | 4 | V02 |
| [[Evento_E0_2026_08_16_Japon_Carry_Trade_y_Liquidez_Septiembre]] | E0 | P4 | ↑ | 4 | V01 |
| [[Evento_E0_2026_07_08_Grid_Stress_IA]] | E0 | P4 | ↑ | 4 | V02 |
| [[Evento_E0_2026_CoWoS_Capacity]] | E0 | P4 | ↑ | 4 | V03 |
| [[Evento_E1_2026_07_24_US_Tariff_Stack]] | E1 | P4 | ↑ | 4 | V04 |

## 4. Carga primaria reproducible

**Contribución = presión × peso × tendencia**, contando una vez cada evento en su vector primario. Escala: P4=4; ↑=1,2; →=1,0; ↓=0,8.

| Vector | Eventos | Carga | Lectura operativa |
|:---|---:|---:|:---|
| V01 | 1 | 19,2 | Elevada, acelerando |
| V02 | 2 | 38,4 | Crítica por acumulación, acelerando |
| V03 | 1 | 19,2 | Elevada, acelerando |
| V04 | 1 | 19,2 | Crítica, acelerando |
| V05 | 0 | 0,0 | Seguimiento estructural, sin evento activo |
| V06 | 0 | 0,0 | Seguimiento estructural, sin evento activo |

**Carga total:** 96,0, frente a 92,8 en la revisión anterior (+3,2). El aumento procede exclusivamente del cambio de tendencia de CoWoS de → a ↑ tras confirmar NVIDIA compromisos de capacidad por 279 B$ y restricción de oferta hasta FY2028.

La carga no es una probabilidad. El número de eventos se muestra para evitar interpretar como intensidad económica lo que también es volumen de sensores.

## 5. Correcciones materiales ejecutadas

- NVIDIA publicó resultados FY2027 Q2 (96,2 B$ de ingresos, 89,0 B$ Data Center, guía Q3 de 108 B$ y debut de Vera Rubin con ~20% del mix); CoWoS eleva tendencia a ↑ manteniendo P4 y triggers A–D inactivos.
- En Jackson Hole, Kevin Warsh reafirmó el objetivo del 2%, empleo en 4,1% y atacó el *forward guidance* y el «salón de espejos»; se integra en V01 como contrapeso doctrinal a la dominancia fiscal.
- Balance de la Fed H.4.1 del 27/08 sitúa reservas en 2.916,8 B$ y TGA en 959,4 B$; la prueba SRF del 25/08 fue de solo 3 M$, sin estrés repo.
- La deuda federal bruta cruzó $40T el 18/08; se distingue de la deuda en manos del público ($32,28T).
- Las recompras del Tesoro en 10-30 años (al menos 4 B$ por operación desde el 09/09) se clasifican como gestión de liquidez de duración, no como QE ni reducción de deuda neta.
- Section 338 aplicable desde el 22/08 sobre Canadá; contraranceles canadienses monitorizados para el 08/09.
- El radar purga los hitos consumidos de finales de agosto y queda reconciliado en 23 hitos futuros para septiembre y octubre.

## 6. Próximas comprobaciones

- Vencimientos DOE 202(c) (01–26/09) e ISM manufacturero de agosto (01/09).
- Subasta JGB 30Y (03/09) y NFP de agosto de EE. UU. (04/09).
- Reunión OPEP+ (06/09) y flujos mensuales de valores en Japón (08/09).
- Contraranceles canadienses (08/09) y EIA STEO (09/09).
- Inicio de recompras del Tesoro en tramo largo (09/09) y ventas mensuales de TSMC (10/09).
- Consejo de Gobierno del BCE (10/09) y CPI de EE. UU. (11/09).
- Ventana de liquidez TGA/repo, FOMC de la Fed y Banco de Japón (15–18/09).

## 7. Regla de mantenimiento

La actualización semanal se ejecuta con [[Prompt_Actualizacion_Eventos]]. El radar se mantiene con [[Prompt_Radar_Eventos]]. No debe haber más de un radar activo ni abrirse una ficha por una tensión estructural sin ventana o trigger material.
