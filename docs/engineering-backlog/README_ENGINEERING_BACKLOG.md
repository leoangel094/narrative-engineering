# Engineering Backlog

> *"Every future idea deserves to be preserved before it deserves to be built."*

---

# Document Information

| Property | Value |
|----------|-------|
| Version | 1.0.0 |
| Status | Active |
| Last Updated | 2026-07-21 |

---

# Purpose

El **Engineering Backlog** es el registro oficial de todas las oportunidades de trabajo conocidas que el proyecto podría desarrollar en el futuro.

Su propósito no es administrar tareas.

Su propósito es preservar conocimiento.

Toda idea, mejora, investigación o propuesta que aún no forme parte del desarrollo activo del proyecto deberá registrarse aquí para evitar que dependa únicamente de la memoria.

Este documento responde únicamente a la siguiente pregunta:

> **¿Qué es el Engineering Backlog y cómo debe utilizarse?**

---

# Scope

El Engineering Backlog registra oportunidades futuras para el proyecto.

Entre ellas pueden encontrarse:

- mejoras metodológicas;
- investigaciones;
- mejoras de documentación;
- propuestas de worldbuilding;
- nuevos sistemas del universo;
- mejoras arquitectónicas;
- experimentos;
- ideas surgidas durante sesiones con IA;
- cualquier otra oportunidad que aporte valor al proyecto.

Registrar una oportunidad **no implica** que vaya a desarrollarse.

Únicamente garantiza que el proyecto ha decidido conservar ese conocimiento.

---

# Philosophy

Las buenas ideas suelen aparecer antes de que el proyecto esté preparado para desarrollarlas.

El Engineering Backlog existe para preservar esas oportunidades hasta que llegue el momento adecuado para evaluarlas.

El objetivo no es crear una lista de tareas.

El objetivo es evitar que el conocimiento desaparezca.

Cada oportunidad registrada representa una decisión consciente de conservar una idea para el futuro.

---

# Engineering Principles

Todo Backlog Item deberá respetar los siguientes principios.

- Preservar conocimiento antes que planificar trabajo.
- Una oportunidad por documento.
- Documentar el razonamiento, no únicamente la idea.
- Evitar información duplicada.
- Mantener una única fuente oficial para cada oportunidad.
- Actualizar las oportunidades en lugar de reemplazarlas.
- Conservar incluso las oportunidades rechazadas como parte del conocimiento del proyecto.

---

# File Naming Convention

Cada oportunidad registrada deberá almacenarse como un documento independiente.

Los archivos seguirán el siguiente formato.

```text
001-short-descriptive-name.md
```

Ejemplos.

```text
001-create-document-templates.md

002-design-canon-structure.md

003-design-supernatural-system.md
```

## Naming Rules

Todos los nombres de archivo deberán cumplir las siguientes reglas.

- utilizar únicamente inglés;
- utilizar letras minúsculas;
- separar palabras mediante guiones (`-`);
- comenzar con un identificador numérico de tres dígitos;
- describir claramente la oportunidad registrada;
- mantener un nombre corto y fácil de identificar.

El identificador numérico representa el orden histórico en que la oportunidad fue incorporada al Engineering Backlog.

El nombre del archivo representa la identidad histórica del Backlog Item.

Si la oportunidad evoluciona durante el proyecto, el contenido del documento deberá actualizarse.

El nombre del archivo únicamente deberá modificarse cuando exista una razón excepcional.

---

# Classification

Cada Backlog Item deberá clasificarse utilizando tres dimensiones independientes.

## Value

Describe el valor que la oportunidad aporta al proyecto.

Valores permitidos.

- Essential
- Important
- Optional

---

## Timeline

Describe cuándo se considera apropiado desarrollar la oportunidad.

Valores permitidos.

- Current
- Next
- Future

---

## Status

Describe el estado actual de la oportunidad.

Valores permitidos.

- Proposed
- Approved
- In Progress
- Completed
- Rejected

Cada dimensión responde una pregunta diferente.

- **Value** → ¿Qué tan importante es?
- **Timeline** → ¿Cuándo debería desarrollarse?
- **Status** → ¿En qué estado se encuentra?

Estas dimensiones son completamente independientes entre sí.

---

# Relationship with Other Documents

El Engineering Backlog únicamente preserva oportunidades futuras.

No reemplaza ningún otro documento del proyecto.

| Document | Responsibility |
|----------|----------------|
| README | Explica qué es el proyecto. |
| PROJECT_CHARTER | Define el propósito y la visión del proyecto. |
| ENGINEERING_GUIDE | Define la metodología de desarrollo. |
| AI_COLLABORATION | Define cómo debe colaborar una IA. |
| AI Sessions | Documenta las sesiones de trabajo con IA. |
| ADR | Documenta decisiones oficiales del proyecto. |
| Canon | Documenta la verdad oficial del universo. |
| Git History | Documenta la evolución del repositorio. |

Cada tipo de conocimiento posee un único lugar oficial donde vivir.

---

# Final Statement

No todas las oportunidades llegarán a desarrollarse.

Pero toda oportunidad valiosa merece ser preservada.

El Engineering Backlog existe para garantizar que el conocimiento sobreviva el tiempo suficiente para ser evaluado con criterio y no dependa únicamente de la memoria.

---

> *"Ideas preserved today become opportunities tomorrow."*