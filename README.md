# Master Inteligencia Artificial — Repositorio de aprendizaje y pruebas

Este repositorio forma parte de mi proceso de formación en inteligencia artificial aplicada al desarrollo de software.

Lo utilizaré principalmente durante el máster **AI4Devs**, como espacio de pruebas para experimentar con herramientas, conceptos y metodologías relacionadas con el desarrollo de software asistido por inteligencia artificial.

La intención de este repositorio no es construir inicialmente un producto destinado a producción, sino disponer de un entorno seguro donde poder practicar sin afectar a proyectos profesionales ni exponer código perteneciente a mi empresa.

---

## Sobre mí

Soy desarrollador de software con varios años de experiencia profesional, principalmente trabajando como **Full Stack Developer**, aunque actualmente mi mayor especialización está en backend.

Mi stack habitual está relacionado principalmente con:

- .NET
- C#
- Entity Framework Core
- SQL Server
- APIs REST
- Angular
- Arquitecturas backend
- Git
- Azure DevOps

Durante los últimos años he trabajado en proyectos reales de cierta complejidad, con aplicaciones que tienen bastante lógica de negocio, múltiples capas, migraciones de base de datos, integraciones, procesos de mantenimiento y código legacy.

Uno de mis objetivos profesionales es evolucionar progresivamente hacia un perfil de **arquitectura de software**, especialmente dentro del ecosistema .NET.

Al mismo tiempo, considero que la inteligencia artificial está cambiando de forma importante la manera en la que desarrollamos software y quiero aprender a utilizar estas herramientas correctamente, no simplemente como generadores de código.

---

# Por qué estoy haciendo este máster

Hasta ahora he utilizado inteligencia artificial principalmente mediante herramientas conversacionales.

Mi herramienta principal ha sido ChatGPT Plus.

El flujo de trabajo que utilizo actualmente suele ser bastante manual.

Por ejemplo, cuando tengo que desarrollar una nueva funcionalidad, suelo proporcionar a la IA diferentes partes del contexto:

- requisitos funcionales,
- entidades,
- DTOs,
- handlers,
- repositorios,
- servicios,
- mappings,
- consultas SQL,
- migraciones,
- tests,
- fragmentos de código relacionados.

La IA me ayuda a analizar el cambio y proponer modificaciones.

Sin embargo, posteriormente soy yo quien aplica cada cambio manualmente dentro del proyecto.

Después reviso los diffs, comparo código, cuestiono algunas decisiones y corrijo aquellas propuestas que no considero adecuadas.

Este sistema me resulta bastante útil porque me obliga a revisar el código generado.

Sin embargo, sigue siendo un proceso muy artesanal.

La IA no conoce directamente el repositorio, no puede recorrer libremente el proyecto, no puede ejecutar comandos y tampoco puede realizar cambios completos de forma autónoma.

Precisamente uno de mis objetivos con este máster es aprender a dar el siguiente paso.

---

# Del asistente al agente

Una de las ideas que quiero explorar durante esta formación es la transición entre utilizar una IA como asistente y utilizarla como agente.

En un modelo tradicional de asistente, el flujo podría ser:

1. El desarrollador selecciona código.
2. Copia el código.
3. Lo envía a la IA.
4. La IA propone una solución.
5. El desarrollador aplica manualmente los cambios.

En un modelo agéntico, el flujo puede evolucionar hacia algo diferente:

1. El desarrollador define correctamente el problema.
2. El agente recibe acceso controlado al proyecto.
3. Analiza la estructura del repositorio.
4. Localiza los archivos relevantes.
5. Propone un plan.
6. Modifica diferentes archivos.
7. Ejecuta comandos.
8. Ejecuta tests.
9. Verifica los resultados.
10. El desarrollador revisa el trabajo realizado.

El desarrollador continúa siendo responsable del resultado, pero cambia parcialmente su función.

Ya no se limita únicamente a escribir código.

También debe:

- definir correctamente el problema,
- proporcionar contexto,
- establecer restricciones,
- revisar decisiones,
- validar código generado,
- detectar edge cases,
- supervisar agentes,
- controlar la calidad final.

Este cambio de mentalidad es una de las razones principales por las que estoy realizando esta formación.

---

# Objetivos del repositorio

Este repositorio servirá como entorno de experimentación durante el máster.

No existe inicialmente una única aplicación que deba desarrollarse hasta producción.

La idea es utilizarlo para diferentes ejercicios.

Entre otras cosas quiero practicar:

## Uso de coding agents

Experimentar con herramientas capaces de trabajar directamente sobre un repositorio.

Por ejemplo:

- Claude Code
- herramientas compatibles con MCP
- agentes de programación
- asistentes integrados en entornos de desarrollo

El objetivo no será simplemente conseguir que la IA genere código.

El objetivo será aprender a controlar correctamente el proceso.

---

## Context engineering

Otro de los aspectos que quiero estudiar es cómo proporcionar contexto de forma eficiente.

Un modelo puede ser muy potente, pero si recibe un contexto incorrecto o incompleto puede producir soluciones técnicamente válidas que no encajen con el proyecto.

Por eso quiero experimentar con diferentes mecanismos para proporcionar contexto:

- documentación del proyecto,
- README,
- archivos de instrucciones,
- especificaciones,
- convenciones,
- arquitectura,
- ejemplos existentes,
- documentación técnica.

---

## MCP

También utilizaré este repositorio para experimentar con **Model Context Protocol (MCP)**.

MCP permite conectar modelos de inteligencia artificial con herramientas y fuentes externas mediante un protocolo estándar.

Algunas posibles integraciones podrían incluir:

- GitHub,
- filesystem,
- documentación,
- APIs,
- bases de datos,
- herramientas de desarrollo.

Una de las primeras pruebas realizadas durante el precurso consistió precisamente en conectar Claude Desktop con el filesystem local mediante MCP.

Claude pudo acceder a una carpeta autorizada y leer un archivo sin necesidad de copiar manualmente su contenido dentro del chat.

Posteriormente utilizaré también la integración con GitHub para permitir que Claude pueda consultar este repositorio.

---

# Seguridad y aislamiento

Este repositorio es deliberadamente independiente de los proyectos profesionales en los que trabajo.

Actualmente mi empresa no utiliza herramientas de inteligencia artificial de forma corporativa dentro del flujo de desarrollo.

Por ese motivo no quiero conectar repositorios profesionales mediante cuentas personales de herramientas de IA.

Antes de plantear cualquier adopción empresarial quiero comprender correctamente:

- cómo funcionan los agentes,
- qué permisos necesitan,
- qué datos utilizan,
- cómo gestionan el contexto,
- cómo se controla el acceso,
- qué riesgos existen,
- qué beneficios reales aportan.

Este repositorio permite experimentar con libertad sin comprometer información profesional.

---

# Principios de trabajo

Durante el máster intentaré aplicar algunos principios.

## 1. La IA no sustituye la revisión

Todo código generado debe ser revisado.

Que una solución compile no significa necesariamente que sea correcta.

También debe evaluarse:

- mantenibilidad,
- legibilidad,
- seguridad,
- arquitectura,
- rendimiento,
- consistencia con el proyecto.

---

## 2. Problem framing antes que prompting

Una de las ideas importantes del curso es que formular correctamente el problema es más importante que intentar escribir prompts extremadamente sofisticados.

Antes de pedir una solución intentaré definir:

- qué problema existe,
- cuál es el objetivo,
- qué restricciones hay,
- qué comportamiento se espera,
- qué partes del sistema pueden verse afectadas.

---

## 3. Pensamiento sistémico

Los cambios en software raramente afectan a una única clase.

Por ejemplo, añadir un nuevo campo puede implicar cambios en:

- base de datos,
- entidad,
- DTO,
- comando,
- handler,
- repositorio,
- mapper,
- API,
- frontend,
- tests,
- documentación.

Por eso quiero desarrollar una visión más sistémica de los cambios.

---

## 4. Edge cases

La IA suele resolver correctamente el happy path.

Sin embargo, el software real también debe gestionar situaciones excepcionales.

Por ejemplo:

- datos inexistentes,
- valores nulos,
- registros duplicados,
- errores de autorización,
- concurrencia,
- estados inconsistentes,
- datos antiguos,
- problemas de red,
- operaciones parciales.

Detectar estos casos continúa siendo una responsabilidad importante del desarrollador.

---

# Qué quiero aprender

Durante esta formación quiero mejorar especialmente en las siguientes áreas:

- Agentic Engineering
- Harness Engineering
- Context Engineering
- Spec Driven Development
- Model Context Protocol
- Coding Agents
- Code Review asistido por IA
- Testing con IA
- Arquitectura asistida por IA
- Automatización del ciclo de desarrollo
- RAG
- sistemas multiagente
- observabilidad de agentes
- seguridad
- evaluación de modelos
- DevSecOps asistido por IA

También quiero aprender a distinguir cuándo una herramienta de IA realmente aumenta la productividad y cuándo simplemente introduce trabajo adicional de revisión.

---

# Herramientas

Durante el curso probablemente experimentaré con diferentes herramientas.

Actualmente utilizo principalmente:

- ChatGPT Plus
- GitHub
- Visual Studio
- Visual Studio Code
- .NET
- SQL Server

Durante el máster quiero incorporar progresivamente:

- Claude Desktop
- Claude Code
- MCP
- coding agents
- herramientas de automatización
- herramientas de evaluación

El objetivo no es dominar diez herramientas distintas.

Prefiero entender bien los principios y dominar unas pocas herramientas que pueda utilizar de forma profesional.

---

# Evolución esperada

Mi punto de partida podría resumirse así:

**IA como chat**

↓

**IA con contexto manual**

↓

**IA conectada a herramientas mediante MCP**

↓

**Coding agent trabajando sobre un repositorio**

↓

**Agentes ejecutando tareas completas**

↓

**Desarrollador supervisando y orquestando el proceso**

El objetivo final no es dejar de programar.

El objetivo es aprender a utilizar la inteligencia artificial como multiplicador de capacidad sin perder el conocimiento técnico necesario para validar correctamente las soluciones.

---

# Estado actual

Este repositorio se encuentra actualmente en una fase inicial.

Durante las primeras semanas probablemente contendrá:

- documentación,
- pequeños experimentos,
- ejemplos,
- pruebas de MCP,
- ejercicios del máster,
- código experimental.

La estructura evolucionará a medida que avance la formación.

---

# Primer experimento con GitHub y Claude

Uno de los primeros experimentos de este repositorio consiste precisamente en utilizar este README como fuente de contexto.

Claude Desktop está conectado a GitHub mediante su integración correspondiente.

El objetivo de la prueba es pedirle a Claude que acceda a este repositorio y:

1. Lea este README.
2. Analice su contenido.
3. Identifique los objetivos principales.
4. Resuma la finalidad del repositorio.
5. Explique cuáles son las motivaciones del desarrollador.
6. Identifique las tecnologías y conceptos que quiero aprender.

La prueba permitirá comprobar que Claude puede obtener información directamente desde GitHub sin que el contenido del README tenga que ser copiado manualmente dentro del chat.

Este pequeño ejercicio representa precisamente uno de los primeros cambios de mentalidad del curso:

**pasar de llevar manualmente el contexto hasta la IA a permitir que la IA obtenga el contexto mediante herramientas controladas.**

---

# Conclusión

Este repositorio representa un entorno de aprendizaje.

No pretende demostrar que la inteligencia artificial pueda sustituir el trabajo de un desarrollador.

La intención es precisamente la contraria: aprender cómo debe evolucionar el trabajo del desarrollador cuando aparecen herramientas capaces de realizar una parte creciente de las tareas de implementación.

Mi objetivo es pasar progresivamente de utilizar la IA únicamente como asistente conversacional a comprender cómo trabajar profesionalmente con agentes.

Esto implica aprender a:

- delegar,
- proporcionar contexto,
- escribir buenas especificaciones,
- supervisar,
- revisar,
- validar,
- medir resultados.

El reto no consiste simplemente en conseguir que una IA escriba código.

El verdadero reto consiste en conseguir que produzca software útil, mantenible y coherente con los requisitos, manteniendo siempre el criterio técnico y la responsabilidad final del desarrollador.

Este repositorio será mi laboratorio para aprender a hacerlo.
