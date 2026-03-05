| Riesgo                                 | Impacto | Probabilidad | Nivel | Mitigación                            |
| -------------------------------------- | ------- | ------------ | ----- | ------------------------------------- |
| Transferencia duplicada por doble clic | Alto    | Media        | Alto  | Validación de transacción única       |
| Transferir más dinero del saldo        | Alto    | Media        | Alto  | Validación de saldo en backend        |
| Sesión expira durante transferencia    | Medio   | Media        | Medio | Guardar estado de transacción         |
| Error de red durante confirmación      | Alto    | Baja         | Medio | Sistema de rollback                   |
| Datos incorrectos de cuenta destino    | Alto    | Baja         | Medio | Confirmación visual antes de ejecutar |
