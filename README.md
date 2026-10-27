# ChakrIA

Del saber ancestral a la práctica validada en tu chakra. Aplicación web de un solo fichero que acompaña la asignatura **Agroecología Agrícola** (Itinerario 1, nivel 6, Carrera de Agropecuaria, Universidad Politécnica Estatal del Carchi, Ecuador) y sirve a cualquier estudiante de agronomía, agropecuaria o ciencias ambientales.

**Usar la app:** https://fborrasumh.github.io/chakria/

**Idiomas:** español (por defecto), inglés y portugués; selector en la barra superior (o `?lang=en` / `?lang=pt` en la URL).

## Qué hace

- **Temario.** Las 12 sesiones del sílabo en cuatro unidades (diseño de sistemas agroecológicos; manejo ecológico del suelo y del agua; insumos orgánicos; sanidad, fruticultura y horticultura orgánicas), con ideas clave, una pregunta para la propia chakra, seguimiento de lo trabajado y glosario.
- **Laboratorio de cálculos con problemas individualizados.** Cada estudiante escribe un código o alias y recibe sus propios problemas, siempre los mismos para ese código (la profesora puede reproducirlos sin guardar nada): uso equivalente de la tierra (UET/LER) de la asociación maíz–fréjol, cosecha de agua de lluvia, relación C/N de una mezcla para compost, dilución de un bioinsumo en la mochila y dosis de abono orgánico por cama. La solución la calcula el código; si la respuesta es errónea, recalcula los errores típicos (media de las C/N, litros en vez de m³, olvidar el coeficiente de escorrentía, por mil en vez de por ciento, no convertir t/ha…) y dice cuál se cometió. «Mis datos» aplica la misma fórmula a los datos de la finca.
- **Diagnóstico de sostenibilidad.** 20 indicadores rápidos de calidad del suelo y salud del cultivo (método de Nicholls, Altieri y colaboradores), puntuados de 1 a 10 para dos sistemas; gráfico de ameba, medias, indicadores por debajo de 5, cobertura de los 13 principios agroecológicos (HLPE 2019; Wezel et al. 2020) por las prácticas de la finca y prácticas sugeridas para los puntos críticos. Opcionalmente, la IA razona un plan de transición; el código comprueba que cada propuesta apunta a un indicador crítico real.
- **Validación de una práctica ancestral** (el resultado de aprendizaje del sílabo). Ficha con origen, quién comparte el saber, consentimiento previo, libre e informado, descripción, mecanismo hipotético, principios y referencias, y un ensayo con testigo y repeticiones. El código calcula medias, diferencia, prueba t de Welch y g de Hedges, y **decide el nivel de validación** (0 sin documentar · 1 documentada · 2 fundamentada · 3 con evidencia local · 4 con evidencia experimental local) con reglas explícitas. La IA, si se usa, solo revisa la ficha: fortalezas y debilidades con cita literal verificada y preguntas de mejora; si emite un veredicto de validación, se avisa de que se ignora.
- **Lectura crítica y debate.** La IA extrae pregunta, diseño, hallazgos, limitaciones, principios y argumentos para el debate «agricultura tradicional frente a agroecología»; cada hallazgo y argumento lleva una cita que el código comprueba en el texto, y se señalan las cifras que no están en él.
- **Práctica de parcial.** 24 preguntas con explicación, por parcial o de todo el temario, sin IA y sin conexión.
- **Portafolio.** Informe Word, CSV de indicadores y archivo JSON para seguir en otro ordenador. Todo se genera en el navegador, sin librerías externas.
- **Ejemplo sin clave** en los tres idiomas, con datos ficticios marcados como tales.

## Privacidad

Todo el trabajo se guarda en el navegador (IndexedDB). La clave de IA (OpenAI, Google Gemini o Anthropic Claude) se guarda solo en el navegador y la paga cada persona; sin clave, todo funciona salvo las tres revisiones de IA. Hacia el proveedor sale únicamente lo que se pide revisar (la ficha, el artículo o el resumen del diagnóstico, nunca el nombre del estudiante), con correos y teléfonos enmascarados y tras un aviso previo con una muestra de lo que sale.

## Límites

- Los problemas usan valores típicos (por ejemplo, contenidos de C y N de materiales) y modelos simplificados.
- Los indicadores son una guía de campo para comparar sistemas, no una certificación; la relación práctica → principio es didáctica.
- El nivel de validación resume un ensayo en un solo lugar y campaña: no permite generalizar. La prueba de Welch compara parcelas; si el diseño tiene bloques, hace falta otro análisis.
- La práctica de parcial es orientativa: no sustituye a la evaluación de la profesora.
- Probado con IA simulada (incluidas citas y cifras inventadas, desvíos y veredictos); no se ha probado con una clave real. Las respuestas reales de la IA pueden equivocarse: por eso se verifican sus citas.

## Autoría

Fernando Borrás Rocher (Universidad Miguel Hernández de Elche) y María Cristina Silva Cazar (Universidad Politécnica Estatal del Carchi).

Sigue el sílabo de Agroecología Agrícola (0811BIT1AA6UP-AJ2025, PAO 2026 B) de la profesora María Cristina Silva Cazar: su resultado de aprendizaje («valida prácticas y productos ancestrales con enfoque agroecológico»), sus unidades, el proyecto en la Finca San Francisco y el debate entre agricultura tradicional y agroecología.

ORCID: Fernando Borrás Rocher [0000-0002-5519-4573](https://orcid.org/0000-0002-5519-4573) · María Cristina Silva Cazar [0009-0000-2440-3267](https://orcid.org/0009-0000-2440-3267)

## Cómo citar

Borrás Rocher, F. y Silva Cazar, M. C. (2026). *ChakrIA* (v1.0.0) [Software]. (DOI en trámite)

## Licencia

MIT. Véase [LICENSE](LICENSE).
