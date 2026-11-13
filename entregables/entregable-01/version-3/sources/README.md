# Sources

Notas de la investigación de noviembre de 2026 para el entregable E01, versión 2.4. No forman parte del PDF ni de la presentación.

**Cambios v2.3 → v2.4.** Reestructuración del `informe.tex` en cuatro secciones puras que calcan los requisitos del enunciado del curso: (1) Ficha ejecutiva con subsecciones Problema, Objetivo SMART, Solución propuesta y Beneficios; (2) Evaluación económica con Inversión, Costos, Beneficios, Indicadores (ROI/VAN/TIR/TCO) y Sensibilidad; (3) Project Charter; (4) Matriz de interesados clave. Lo que antes eran secciones autónomas ("Cómo se engancha al banco" y "Habilidades y perfiles") pasó a subsubsecciones de "Solución propuesta". Cierre como sección sin numerar. No cambió el contenido técnico ni las cifras; solo la agrupación.

**Cambios v2.2 → v2.3.** El Excel y las notas de `sources/` no cambiaron. El `informe.tex` se consolidó fusionando lo mejor de las versiones 2.2 y 3: resumen ejecutivo al inicio, FODA y análisis de alternativas (A0-A3), objetivo con criterios de éxito verificables al cierre y separación de objetivos de negocio, charter como ficha tabular legible, hito H0 de Kick-off en mes 1, supuestos y restricciones integrados, risk register con P×I (8 riesgos, severidad y respuesta), benefits register con dueño post-proyecto, matriz de interesados con poder/interés y acción principal, matriz de engagement actual vs. deseado, y captions en todas las tablas. Se eliminaron el WBS detallado, el cronograma detallado y la matriz RACI de entregables, que se delegan al Entregable E02 (línea base de alcance, cronograma y costo). Se corrigieron las tablas largas que descuadraban en la versión 2.2 reemplazando `longtable` por `tabularx` con anchos relativos a `\textwidth`.

**Cambios v2 → v2.2.** Se reestructuró el `informe.tex` siguiendo el PMBOK 6 §4.1.3.1 para el charter y el PMBOK 7 §4 para el business case. Se añadieron FODA, análisis de alternativas, separación objetivos del proyecto vs. de negocio, requisitos de alto nivel, WBS preliminar, cronograma con ruta crítica, criterios de éxito por hito, autoridad del director del proyecto, comité de dirección, RACI, criterios de aprobación y salida, assumption log, risk register, benefits register, clasificación poder/interés/impacto y engagement actual vs. deseado.

| Nota | Qué guarda |
| --- | --- |
| [agentes-financieros.md](agentes-financieros.md) | Productos comparables: Revolut AIR, Cleo, Mercado Pago, Erica, Fargo, Clara, Salvador, Plin WhatsApp y otros. |
| [marco-peru.md](marco-peru.md) | Conducta de mercado, seguridad de la información, datos personales, Ley del Mercado de Valores y cifras de Credicorp 2024. |
| [integracion.md](integracion.md) | Cómo se pensó el enganche a los sistemas del banco, las habilidades y los perfiles. |

Lo que el caso usa de estas notas: las cifras de Credicorp (13,7 millones de clientes, 76 % digital, 13,7 millones de usuarios activos de Yape), Clara, Salvador, el límite de Erica, AIR, Mago y Plin, y las normas SBS, la Ley 29733 y el Decreto Supremo 020-2023-EF.

Lo que se leyó y no entra al modelo: el ahorro de Klarna, el portafolio de modelos de DBS y cualquier VAN ajeno. No hay un VAN publicado de un agente equivalente.

Lo que queda solo como contexto, y por eso no está en el informe: los nombres de la plataforma de eventos y del repositorio en reposo, y la lista de pruebas de comportamiento. Esa lista era una nota de trabajo, no un alcance del entregable.

No se usa como cifra del banco lo que la prensa atribuye a Yape (400 000 consultas al mes, o más de 17 millones de usuarios). La cifra que se cita es la de Credicorp: 13,7 millones de usuarios activos mensuales.
