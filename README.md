# NovaBank QA Testing Project

## Overview

Este proyecto simula el proceso de testing funcional de un módulo de **transferencias bancarias** dentro de una aplicación ficticia llamada NovaBank.

El objetivo del proyecto es demostrar habilidades de QA manual aplicando buenas prácticas de testing, documentación de casos de prueba y gestión de defectos.

---

## Testing Scope

Se realizaron pruebas sobre el módulo de **transferencias bancarias**, validando los siguientes aspectos:

- Validación de saldo disponible
- Confirmación de transferencias
- Manejo de doble confirmación
- Validación de datos de cuenta destino
- Manejo de expiración de sesión

---

## Testing Types

Durante este proyecto se aplicaron los siguientes tipos de pruebas:

- Functional Testing
- Exploratory Testing
- Negative Testing
- Business Rule Validation

---

## Tools Used

- Jira (bug tracking)
- Google Sheets (test cases)
- Chrome Browser

---

## Test Cases

Se diseñaron y ejecutaron **7 casos de prueba** enfocados en el comportamiento del sistema de transferencias.

Los test cases incluyen:

- Preconditions
- Test steps
- Test data
- Expected results
- Execution environment

---

## Test Execution Summary

Total Test Cases: **7**

Resultados:

| Resultado | Cantidad |
|--------|--------|
| Passed | 3 |
| Failed | 4 |

---

## Bug Reports

Durante la ejecución de pruebas se identificaron **4 defectos principales**:

1️⃣ El sistema permite transferir un monto mayor al saldo disponible.

2️⃣ El sistema permite intentar transferencias superiores al saldo disponible.

3️⃣ La transferencia permite confirmación mediante doble clic generando posible duplicación.

4️⃣ No existe una pantalla clara de confirmación de datos antes de ejecutar la transferencia.

Los defectos fueron registrados y gestionados utilizando **Jira**.

---

## Risk Analysis

Se realizó un análisis de riesgos enfocado en los posibles impactos de negocio dentro del módulo de transferencias.

Principales riesgos identificados:

- Transferencias duplicadas
- Transferencias con saldo insuficiente
- Falta de confirmación de datos críticos
- Manejo incorrecto de sesiones expiradas
- Errores durante interrupciones de red

El detalle completo puede encontrarse en la documentación del proyecto.

---

## Author

Nahuel Magnano  
QA Tester
