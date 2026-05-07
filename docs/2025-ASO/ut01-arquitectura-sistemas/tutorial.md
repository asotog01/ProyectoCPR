---
title: Tutorial - Exploración del Sistema
sidebar_position: 2
description: Guía práctica para identificar componentes del sistema en Linux y Windows.
---

## Prerrequisitos
Para este tutorial necesitaremos:
*   Una máquina virtual con Linux (Ubuntu/Debian).
*   Acceso a la terminal con permisos de sudo.

## Resumen del Tutorial
En esta práctica aprenderás a navegar por las entrañas del sistema operativo. Utilizaremos comandos como `uname`, `lsmod` y exploraremos el sistema de archivos `/proc` para entender cómo el kernel gestiona el hardware y los procesos en tiempo real.

## Diagrama de Flujo
```mermaid
graph TD
    A[Usuario] --> B[Terminal]
    B --> C[Llamada al Sistema]
    C --> D[Kernel]
    D --> E[Hardware]
```
