# Engineering Guide

> *"A universe is not discovered. It is engineered."*

---

## Document Information

| Property | Value |
|----------|-------|
| Version | 0.1.0 |
| Status | Foundation |
| Last Updated | 2026-07-20 |

---

# Purpose

Este documento define la metodología utilizada para desarrollar **Narrative Engineering**.

Su propósito es establecer un proceso de trabajo claro, consistente y escalable que permita construir un universo de forma ordenada a lo largo del tiempo.

Toda decisión relacionada con la forma de trabajar deberá documentarse en este archivo.

---

# What is Narrative Engineering?

Narrative Engineering es una metodología para construir universos narrativos utilizando principios de ingeniería de software.

En lugar de improvisar una historia, el universo se desarrolla mediante documentación, procesos definidos y decisiones deliberadas.

El objetivo no consiste únicamente en escribir ficción.

El objetivo consiste en **ingenierizar un universo**.

---

# Documentation Architecture

La documentación del proyecto sigue dos principios fundamentales.

## Single Responsibility

Cada documento responde una única pregunta.

## Single Source of Truth

Cada tipo de conocimiento posee un único lugar oficial donde vivir.

La siguiente tabla define la responsabilidad de cada documento del proyecto.

| Document | Responsibility |
|----------|----------------|
| README | ¿Qué es este proyecto? |
| PROJECT_CHARTER | ¿Por qué existe este proyecto? |
| ENGINEERING_GUIDE | ¿Cómo se desarrolla este proyecto? |
| AI_COLLABORATION | ¿Cómo debe colaborar una IA? |
| AI Sessions | ¿Qué se discutió durante el desarrollo (por sesión)? |
| Git History | ¿Qué cambió en el repositorio? |

Ningún documento deberá duplicar información perteneciente a otro.

Antes de agregar contenido a un documento deberá verificarse que dicho documento sea la fuente oficial para ese tipo de conocimiento.

---

# Engineering Principles

Toda actividad realizada dentro del proyecto deberá respetar los siguientes principios.

## Documentation First

Las decisiones importantes deberán documentarse antes de implementarse.

La documentación forma parte del producto.

---

## Incremental Development

El proyecto evolucionará mediante pequeños avances bien definidos.

Cada commit deberá representar una mejora concreta.

---

## Consistency Over Creativity

La creatividad nunca deberá comprometer la coherencia del proyecto.

---

## Long-Term Thinking

Toda decisión deberá tomarse pensando en la evolución del proyecto y no únicamente en las necesidades inmediatas.

---

## Traceability

Toda decisión importante deberá poder rastrearse a través de la documentación y el historial del proyecto.

---

# Development Workflow

Toda nueva idea seguirá el siguiente flujo de trabajo.

```text
Idea
    │
    ▼
Análisis
    │
    ▼
Documentación
    │
    ▼
Implementación
```

Este flujo garantiza que las decisiones importantes sean analizadas antes de incorporarse al proyecto.

---

# Repository Workflow

El repositorio evolucionará mediante pequeños commits con un propósito claramente definido.

Cada commit deberá representar una decisión o un avance concreto.

Se evitarán commits ambiguos o excesivamente grandes.

---

# Commit Convention

El proyecto utiliza el estándar **Conventional Commits**.

## Commit Structure

```text
type(scope): summary

Descripción del cambio en español.
```

### Rules

- El encabezado del commit deberá escribirse en inglés.
- La descripción deberá escribirse en español.
- Cada commit deberá representar una única decisión de ingeniería.
- Un commit podrá modificar varios archivos siempre que pertenezcan al mismo cambio lógico.
- Cambios no relacionados deberán registrarse en commits independientes.

### Example

```text
feat(project): initialize narrative engineering

Se establece la estructura inicial del proyecto.

- Se crea el README.
- Se incorpora el PROJECT_CHARTER.
- Se agrega el ENGINEERING_GUIDE.
- Se documenta la metodología inicial.
```

---

# Branch Strategy

Las ramas deberán utilizar nombres descriptivos en inglés.

Ejemplos:

```text
feature/world

feature/history

feature/cultures

feature/politics

feature/religions
```

La rama `main` siempre representará el estado oficial del proyecto.

---

# Language Convention

Este proyecto utiliza dos idiomas de forma intencional.

## English

Se utilizará para:

- nombres de archivos
- nombres de carpetas
- títulos de documentos
- ramas
- commits (encabezado)
- términos técnicos

## Español

Se utilizará para:

- documentación
- explicaciones
- comentarios
- contenido creativo
- worldbuilding
- commits (descripción)

---

# Documentation Principles

Toda documentación deberá cumplir las siguientes reglas.

- Tener una única responsabilidad.
- Evitar información duplicada.
- Mantener una estructura consistente.
- Escribirse pensando en el largo plazo.
- Ser comprensible de forma independiente.

---

# Final Statement

Narrative Engineering aplica principios de ingeniería al proceso creativo.

La creatividad construye el universo.

La documentación preserva su conocimiento.

La metodología garantiza su evolución.

---

> *"Engineering is not the opposite of creativity. It is what allows creativity to endure."*