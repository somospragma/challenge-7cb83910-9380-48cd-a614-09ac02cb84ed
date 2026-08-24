# Diseño de una arquitectura de integración de alto rendimiento

El sistema de integración de una fintech necesita ser escalable y resiliente para manejar un alto volumen de transacciones en tiempo real. El objetivo es diseñar una arquitectura que garantice alta disponibilidad y rendimiento, utilizando brokers de mensajes y patrones de integración empresarial. El sistema debe ser capaz de manejar picos de carga y fallos parciales sin interrumpir el servicio.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Fundamentos de arquitecturas de software |
| **Nivel** | master-l3 |
| **Tipo** | practical |
| **Tiempo estimado** | 8-10 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Análisis del dominio y requisitos

**Objetivo:** Identificar los requisitos funcionales y no funcionales del sistema de integración.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Investiga y documenta los patrones de integración empresarial comunes.
- Identifica los brokers de mensajes más utilizados en la industria.
- Analiza el dominio de la fintech y enumera los requisitos de alta disponibilidad y rendimiento.

**Entregable:** Documento de requisitos funcionales y no funcionales.

<details>
<summary>Pistas de conocimiento</summary>

- Considera la diferencia entre alta disponibilidad y rendimiento.
- Piensa en cómo los brokers de mensajes pueden mejorar la escalabilidad del sistema.

</details>

### Fase 2: Diseño de la arquitectura

**Objetivo:** Proponer una arquitectura de integración que cumpla con los requisitos identificados.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Diseña una arquitectura utilizando un broker de mensajes y patrones de integración.
- Considera cómo manejar picos de carga y fallos parciales.
- Documenta las decisiones de diseño y los trade-offs considerados.

**Entregable:** Diagrama de la arquitectura propuesta y documento de decisiones de diseño.

<details>
<summary>Pistas de conocimiento</summary>

- Piensa en cómo los patrones de integración pueden mejorar la resiliencia del sistema.
- Considera el impacto de los trade-offs en la arquitectura final.

</details>

### Fase 3: Evaluación de la arquitectura

**Objetivo:** Evaluar la arquitectura propuesta en términos de alta disponibilidad y rendimiento.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Simula escenarios de alta carga y fallos parciales.
- Evalúa el comportamiento de la arquitectura en estos escenarios.
- Documenta los resultados y propone mejoras si es necesario.

**Entregable:** Informe de evaluación de la arquitectura con propuestas de mejora.

<details>
<summary>Pistas de conocimiento</summary>

- Considera el uso de pruebas de carga y caos para evaluar la arquitectura.
- Piensa en cómo los resultados de la evaluación pueden informar futuras decisiones de diseño.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un broker de mensajes y por qué se utiliza en arquitecturas de integración?
- **paraQueSirve**: ¿Para qué sirven los patrones de integración empresarial en una arquitectura de alto rendimiento?
- **comoSeUsa**: ¿Cómo se utiliza un patrón de integración para mejorar la resiliencia de un sistema?
- **erroresComunes**: ¿Cuáles son los errores comunes al diseñar una arquitectura de integración escalable?
- **queDecisionesImplica**: ¿Qué decisiones implica el diseño de una arquitectura de integración de alto rendimiento y alta disponibilidad?

## Criterios de Evaluacion

- Identificar y documentar los requisitos funcionales y no funcionales del sistema de integración.
- Proponer una arquitectura de integración que cumpla con los requisitos identificados.
- Evaluar la arquitectura propuesta en términos de alta disponibilidad y rendimiento.
- Documentar las decisiones de diseño y los trade-offs considerados.
- Proponer mejoras para la arquitectura basadas en los resultados de la evaluación.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
