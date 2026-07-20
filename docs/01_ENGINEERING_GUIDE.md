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

Este documento define la metodología utilizada para construir y mantener este proyecto.

Su objetivo es establecer un proceso de desarrollo claro, repetible y escalable que permita diseñar un universo de forma coherente a lo largo del tiempo.

Todo el contenido del proyecto deberá seguir las convenciones descritas en esta guía.

---

# What is Narrative Engineering?

Narrative Engineering es una metodología para diseñar universos narrativos utilizando principios propios de la ingeniería de software.

En lugar de construir una historia de forma improvisada, el universo se desarrolla mediante procesos documentados, decisiones deliberadas y una arquitectura organizada.

El objetivo no consiste únicamente en escribir ficción.

Consiste en diseñar un sistema capaz de sostener múltiples historias sin perder coherencia.

---

# Engineering Principles

Todo el desarrollo del proyecto deberá respetar los siguientes principios.

## Single Responsibility

Cada documento debe tener un único propósito.

Cada archivo debe responder una única pregunta importante.

---

## Documentation First

Las decisiones importantes deberán documentarse antes de formar parte del canon.

La documentación es parte del producto.

---

## Canon First

Nada pertenece oficialmente al universo hasta formar parte del Canon.

Las ideas no son Canon.

Los borradores no son Canon.

Las conversaciones no son Canon.

---

## Consistency Over Creativity

La creatividad nunca deberá romper la coherencia del universo.

Una buena idea que contradice el canon deberá modificarse o descartarse.

---

## Incremental Development

El universo crecerá mediante pequeñas decisiones bien documentadas.

No se diseñará todo desde el principio.

El proyecto evolucionará de manera iterativa.

---

# Development Workflow

Toda nueva idea deberá seguir el siguiente proceso.

```text
Idea
    │
    ▼
Discusión
    │
    ▼
Investigación
    │
    ▼
Documentación
    │
    ▼
Validación
    │
    ▼
Canon
    │
    ▼
Narrativa
```

Ningún elemento deberá aparecer en una historia sin haber recorrido este flujo.

---

# Repository Workflow

Cada commit deberá representar una decisión importante del proyecto.

No se realizarán commits ambiguos como:

- Update
- Changes
- More work
- Fix

Cada commit deberá explicar claramente qué cambió y por qué.

---

# Conventional Commits

Este proyecto utiliza el estándar **Conventional Commits** adaptado al desarrollo de un universo narrativo.

## Types

| Type | Uso |
|------|-----|
| feat | Nueva funcionalidad del proyecto o nuevo elemento importante del universo. |
| docs | Cambios en la documentación. |
| fix | Corrección de errores o inconsistencias. |
| refactor | Reorganización sin cambiar el significado del contenido. |
| style | Cambios de formato o estilo. |
| chore | Configuración, estructura o mantenimiento del repositorio. |

---

## Examples

```text
feat(project): initialize narrative engineering framework

docs(charter): improve project philosophy

feat(history): create ancient civilizations

feat(culture): define northern tribes

fix(history): resolve chronological inconsistency

refactor(canon): reorganize political documentation
```

---

# Branch Strategy

Las ramas deberán representar una línea de trabajo claramente identificable.

Ejemplos:

```text
feature/history

feature/religions

feature/politics

feature/world

feature/cultures

feature/fantastic-system

feature/characters
```

La rama `main` siempre representará la versión oficial del proyecto.

---

# Language Convention

Este proyecto utiliza dos idiomas de forma intencional.

## English

Se utiliza para:

- nombres de archivos
- nombres de carpetas
- títulos
- ramas
- commits
- estructura documental
- términos técnicos

## Español

Se utiliza para:

- documentación
- comentarios
- explicaciones
- decisiones
- contenido creativo
- worldbuilding

---

# Documentation Principles

Todo documento deberá cumplir las siguientes reglas.

- Tener una única responsabilidad.
- Evitar información duplicada.
- Mantener una estructura consistente.
- Escribirse pensando en el largo plazo.
- Poder comprenderse de forma independiente.

---

# Decision Process

Antes de incorporar cualquier idea al proyecto deberán responderse, como mínimo, las siguientes preguntas.

- ¿Qué problema resuelve?
- ¿Por qué existe?
- ¿Qué consecuencias produce?
- ¿Cómo afecta al resto del universo?
- ¿Es coherente con el canon?
- ¿Puede mantenerse a largo plazo?

Si una idea no puede responder estas preguntas, todavía no está lista para formar parte del proyecto.

---

# Project Evolution

Este proyecto evolucionará mediante pequeñas iteraciones.

Cada nueva decisión deberá mejorar el universo sin comprometer su coherencia.

El crecimiento del proyecto tendrá prioridad sobre la velocidad de desarrollo.

---

# Final Statement

Narrative Engineering no busca acelerar la escritura.

Busca construir un universo capaz de sostener historias durante muchos años.

La documentación, el canon y la metodología forman parte del producto tanto como la propia narrativa.

---

> *"Engineering is not the opposite of creativity. It is what allows creativity to endure."*