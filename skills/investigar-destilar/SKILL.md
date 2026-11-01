---
name: investigar-destilar
description: Investigar proyectos sociales, ONG e infraestructura comunitaria y convertir fuentes primarias en fichas y aprendizajes Markdown verificables. Usar al incorporar documentos, estudiar un proyecto, comparar experiencias, actualizar la wiki o revisar contradicciones y calidad de evidencia.
---

# Investigar y destilar conocimiento

Propósito: crear una memoria acumulativa de **qué se intentó, qué se aprendió, bajo qué condiciones y con qué evidencia**. La wiki no es un directorio de ONG, un depósito de PDFs ni una guía técnica certificada.

## 1. Formular una pregunta útil

- Registrar la necesidad de un potencial usuario, el sector, el territorio y el tipo de decisión que intenta tomar.
- Especificar qué respuesta permitiría actuar mejor. Si no hay una pregunta, no forzar una síntesis.
- Consultar la agenda y las páginas existentes antes de crear nuevos archivos.

## 2. Localizar y seleccionar fuentes

- Priorizar documentos producidos por equipos ejecutores, evaluadores, organismos técnicos y universidades: sistematizaciones, informes finales, manuales, datos, artículos técnicos y entrevistas documentadas.
- Buscar también fuentes que cuestionen, contextualicen o contradigan los resultados encontrados.
- Para cada fuente registrar: título, autores/organización, fecha de publicación, URL canónica, fecha de consulta, alcance, permisos/licencia conocidos, sección o páginas relevantes.
- Nunca asumir que poder acceder a un PDF autoriza copiarlo íntegramente al repositorio. Preferir referencias y síntesis originales.
- No convertir ausencia de documentación pública en afirmaciones sobre la gestión o conocimiento interno de una ONG.

## 3. Extraer evidencia antes de sintetizar

Para cada afirmación, registrar:

- Qué afirma exactamente la fuente y dónde puede verificarse (página, sección, tabla o fragmento localizable).
- Clase: **objetivo**, **método aplicado**, **resultado reportado**, **resultado medido**, **resultado verificado externamente**, **testimonio**, **recomendación del autor** o **inferencia del agente**.
- Lugar, período, participantes y condiciones de implementación, cuando consten.
- Indicadores con sus denominadores, unidades, método de medición y fecha. No combinar cifras de distintas fechas sin explicarlo.
- Limitaciones, resultados negativos, incertidumbres y posibles factores alternativos.

Una inferencia debe anunciarse como inferencia, nunca atribuirse a los autores. Evitar porcentajes de confianza inventados.

## 4. Crear la ficha de proyecto

Usar [plantillas/proyecto.md](../../plantillas/proyecto.md) como guía. Incluir problema, actores, solución, contexto, proceso de implementación, resultados y evidencia, dificultades, decisiones modificadas, lecciones expresadas por los autores, información faltante y fuentes. Marcar la ficha como borrador si aún no fue revisada.

Si una intervención está en curso, no penalizarla por no disponer todavía de resultados finales.

## 5. Destilar conocimiento transversal

- Revisar [conocimiento/index.md](../../conocimiento/index.md) para ampliar una página existente cuando corresponda.
- Crear una página de tema solo si hay un aprendizaje operativo, una comparación significativa, una contradicción o una pregunta abierta bien delimitada; **no** por el simple hecho de resumir otro PDF.
- Diferenciar las conclusiones de cada fuente de la síntesis nueva. Explicar la relación con enlaces a las fichas y documentos.
- Explicitar transferibilidad: qué condiciones deberían comprobarse antes de adaptar una experiencia a otro territorio.
- No tratar experiencias de organizaciones relacionadas como validaciones independientes sin comprobarlo.
- Usar [plantillas/conocimiento.md](../../plantillas/conocimiento.md) como estructura mínima.

## 6. Mantener la wiki

- Actualizar índices de fuentes, proyectos y conocimiento con enlaces relativos y una descripción breve.
- Registrar en [investigacion/bitacora.md](../../investigacion/bitacora.md) qué se incorporó, qué cambió y qué preguntas siguen abiertas.
- En revisiones periódicas, detectar contradicciones, citas rotas, afirmaciones sin respaldo, documentación reemplazada y páginas duplicadas.
- Si una fuente nueva contradice una anterior, conservar ambas posturas y explicar el conflicto; no sobrescribir silenciosamente.
- El historial Git complementa la trazabilidad, pero no reemplaza las citas.

## 7. Control de calidad antes de proponer cambios

Confirmar:

- [ ] La pregunta investigada y el aporte diferencial están claros.
- [ ] Las fuentes son localizables y tienen autor/fecha cuando están disponibles.
- [ ] Cada afirmación sustantiva tiene respaldo específico, no una lista genérica de enlaces.
- [ ] Se separan hechos, testimonios, inferencias y recomendaciones.
- [ ] Se incluyen límites, incertidumbre y condiciones de aplicación.
- [ ] Las cifras están contextualizadas y las contradicciones identificadas.
- [ ] No se publican datos sensibles, material protegido no autorizado ni recomendaciones de seguridad como certificadas.
- [ ] Se actualizaron las conexiones, índices y bitácora.
- [ ] El contenido queda pendiente de revisión humana; no autoaprobar ni auto-fusionar el PR.

## Formato de entrega

Resumir siempre: **fuentes revisadas**, **hallazgos verificables**, **aprendizajes nuevos**, **qué no sabemos**, **páginas creadas/modificadas** y **pregunta siguiente**.

Si el material no aporta aprendizaje más allá de un resumen institucional, decirlo y recomendar no incorporarlo todavía.
