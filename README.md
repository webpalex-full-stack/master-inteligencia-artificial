# Máster de Inteligencia Artificial aplicada al Desarrollo de Software

Este repositorio forma parte de mi formación en inteligencia artificial aplicada al desarrollo de software.

Lo utilizaré como espacio de pruebas, ejercicios y experimentación durante el programa **AI4Devs**, con el objetivo de profundizar en nuevas formas de desarrollar software utilizando herramientas de inteligencia artificial, agentes y automatización.

El repositorio tiene un propósito principalmente educativo y servirá como laboratorio para realizar ejercicios, probar herramientas y documentar aprendizajes a medida que avance el programa.

---

## Objetivo

El objetivo principal de esta formación es entender cómo está evolucionando el desarrollo de software con la incorporación de modelos de lenguaje, coding agents y nuevas herramientas capaces de participar de forma activa en el ciclo de desarrollo.

El interés no está únicamente en aprender a generar código mediante IA, sino en comprender cómo integrar estas herramientas de forma estructurada dentro de procesos reales de ingeniería de software.

Durante el programa se trabajan conceptos relacionados con:

- agentes de programación,
- contexto,
- especificaciones,
- automatización,
- testing,
- documentación,
- seguridad,
- observabilidad,
- arquitectura,
- DevOps,
- bases de datos,
- RAG,
- sistemas multiagente.

---

# Temario

El programa está organizado en diferentes módulos que recorren buena parte del ciclo de vida del desarrollo de software.

## Harness Engineering

Una de las primeras áreas del curso se centra en **Harness Engineering**.

El objetivo es entender cómo trabajar correctamente con herramientas de inteligencia artificial y coding agents.

Entre los temas tratados se encuentran:

- herramientas de programación asistida por IA,
- Claude Code,
- contexto,
- prompts,
- hooks,
- subagentes,
- plan mode,
- MCP,
- economía de tokens,
- modelos locales,
- routing de modelos.

La idea principal es aprender a configurar correctamente el entorno que rodea al modelo para que pueda trabajar de forma más efectiva.

---

## Spec Driven Development

Otro bloque importante está dedicado al desarrollo basado en especificaciones.

Antes de generar código es necesario definir correctamente qué debe construirse.

Durante este módulo se trabajan conceptos como:

- requisitos,
- PRD,
- especificaciones,
- épicas,
- historias de usuario,
- definición de tareas,
- relación entre requisitos y desarrollo.

El objetivo es reducir la ambigüedad y proporcionar mejores instrucciones a los agentes.

---

## OpenSpec

El programa profundiza también en herramientas y metodologías para trabajar con especificaciones estructuradas.

La idea es que las especificaciones puedan convertirse en una fuente de contexto para los agentes y acompañar al proyecto durante todo su ciclo de vida.

---

## Documentación y revisión adversarial

La documentación adquiere una importancia especial cuando los agentes participan en el desarrollo.

Durante este bloque se estudian técnicas para:

- generar documentación,
- mantener documentación viva,
- revisar especificaciones,
- detectar inconsistencias,
- realizar revisiones críticas,
- cuestionar soluciones generadas por IA.

El objetivo es mejorar la calidad del resultado antes de llegar a producción.

---

## Agent Guardrails

Los agentes pueden ejecutar acciones y modificar sistemas, por lo que necesitan límites claros.

Este módulo trabaja conceptos relacionados con:

- permisos,
- restricciones,
- control de acciones,
- seguridad,
- validación,
- supervisión.

El objetivo es entender cómo controlar el comportamiento de los agentes dentro de un entorno de desarrollo.

---

## IA aplicada a proyectos Legacy

Una parte especialmente interesante del programa está dedicada al uso de IA en proyectos existentes.

Trabajar sobre un proyecto nuevo es muy diferente de hacerlo sobre una base de código madura.

En este bloque se estudian aspectos como:

- comprensión de código existente,
- análisis de dependencias,
- documentación automática,
- refactorización,
- mantenimiento,
- modernización.

---

## IA en proyectos Polyrepo

Muchos sistemas reales están distribuidos entre varios repositorios.

Durante este módulo se estudia cómo trabajar con agentes cuando el contexto está repartido entre diferentes proyectos y componentes.

Esto introduce retos adicionales relacionados con:

- contexto,
- dependencias,
- integración,
- arquitectura,
- coordinación entre repositorios.

---

## Evaluación de agentes

Otro de los temas importantes es aprender a evaluar el comportamiento de los agentes.

No basta con que una solución parezca correcta.

Es necesario medir aspectos como:

- calidad,
- precisión,
- comportamiento,
- consistencia,
- seguridad,
- cumplimiento de requisitos.

---

# Ética, regulación y privacidad

La incorporación de inteligencia artificial al desarrollo de software también plantea cuestiones relacionadas con:

- privacidad,
- uso de datos,
- propiedad intelectual,
- regulación,
- seguridad,
- responsabilidad.

El programa dedica un módulo específico a estos aspectos.

---

# Bases de datos e inteligencia artificial

El curso también aborda nuevas formas de trabajar con datos utilizando herramientas de IA.

Entre otros conceptos se estudian:

- bases de datos tradicionales,
- búsqueda semántica,
- embeddings,
- campos vectoriales,
- recuperación de información.

Estos conceptos son especialmente importantes para construir aplicaciones basadas en RAG.

---

# Backend, TDD y testing

La IA también puede participar en la generación y mantenimiento de tests.

Durante este módulo se estudian aspectos relacionados con:

- TDD,
- pirámide de testing,
- tests unitarios,
- tests de integración,
- automatización,
- validación de comportamiento.

---

# Frontend y Design Systems

El programa también incluye una parte dedicada al desarrollo frontend.

Entre los temas tratados se encuentran:

- Design Systems,
- componentes reutilizables,
- consistencia visual,
- testing de frontend,
- generación asistida por IA.

---

# DevSecOps

La inteligencia artificial puede participar también en tareas relacionadas con infraestructura y despliegue.

Durante estos módulos se trabajan conceptos relacionados con:

- CI/CD,
- infraestructura,
- automatización,
- seguridad,
- observabilidad,
- monitorización.

---

# RAG

Uno de los laboratorios del programa está dedicado a construir un chatbot basado en documentación.

Este tipo de arquitectura se conoce habitualmente como:

**Retrieval-Augmented Generation (RAG)**

El objetivo es permitir que un modelo pueda responder utilizando información recuperada desde una fuente documental.

Durante este laboratorio se utilizan tecnologías relacionadas con:

- recuperación de información,
- embeddings,
- LangChain,
- Streamlit,
- modelos de lenguaje.

---

# Sistemas multiagente

Otro de los laboratorios está dedicado a sistemas formados por varios agentes.

En lugar de tener un único modelo realizando toda la tarea, diferentes agentes pueden especializarse en responsabilidades distintas.

Durante este bloque se estudian herramientas y conceptos como:

- LangGraph,
- PydanticAI,
- AutoGen,
- MCP,
- coordinación entre agentes,
- monitorización.

---

# Model Context Protocol

Uno de los conceptos importantes del programa es **MCP — Model Context Protocol**.

MCP permite conectar modelos de inteligencia artificial con herramientas y fuentes externas mediante un protocolo estándar.

Algunos ejemplos de estas fuentes pueden ser:

- sistemas de archivos,
- repositorios Git,
- documentación,
- APIs,
- herramientas de desarrollo,
- servicios externos.

Este repositorio se utilizará también para realizar algunas pruebas relacionadas con MCP.

---

# Agentic Engineering

Uno de los conceptos centrales de la formación es **Agentic Engineering**.

El desarrollo de software está evolucionando desde un modelo en el que la inteligencia artificial simplemente sugiere código hacia otro en el que los agentes pueden realizar tareas más completas.

Esto introduce nuevas responsabilidades dentro del desarrollo de software:

- definir correctamente los problemas,
- proporcionar contexto,
- establecer restricciones,
- supervisar agentes,
- revisar resultados,
- validar soluciones.

---

# Objetivos de aprendizaje

A lo largo del programa espero profundizar en:

- Agentic Engineering
- Harness Engineering
- Context Engineering
- Spec Driven Development
- Coding Agents
- Model Context Protocol
- RAG
- Sistemas multiagente
- Testing asistido por IA
- DevSecOps
- Observabilidad
- Seguridad
- Arquitectura
- Evaluación de agentes

---

# Uso de este repositorio

Este repositorio podrá contener diferentes tipos de contenido:

- ejercicios del curso,
- ejemplos,
- pruebas técnicas,
- documentación,
- experimentos,
- pequeños proyectos,
- configuraciones,
- notas de aprendizaje.

El contenido irá evolucionando a medida que avance el programa.

No se trata de un proyecto de producción, sino de un entorno de experimentación destinado exclusivamente al aprendizaje.

---

# Primeras pruebas

Una de las primeras pruebas del curso consiste en experimentar con herramientas capaces de acceder a fuentes externas mediante MCP.

Por ejemplo:

- acceso controlado a archivos locales,
- integración con GitHub,
- lectura de documentación,
- uso de herramientas desde un agente.

Este repositorio permitirá realizar algunas de estas pruebas de forma segura.

---

# Conclusión

La inteligencia artificial está cambiando rápidamente la forma en la que se desarrolla software.

La evolución no afecta únicamente a la generación de código.

También afecta a:

- análisis,
- arquitectura,
- especificaciones,
- testing,
- documentación,
- automatización,
- infraestructura,
- seguridad,
- mantenimiento.

El objetivo de este repositorio es acompañar ese proceso de aprendizaje y servir como espacio práctico durante el máster.

A medida que avance la formación, se irán incorporando nuevos experimentos, ejercicios y ejemplos relacionados con el uso profesional de inteligencia artificial en ingeniería de software.
