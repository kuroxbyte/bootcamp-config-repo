# config-repo

Configuración externalizada de los microservicios del banco, servida por `config-server`.

| Archivo | Aplica a |
|---|---|
| `application.yaml` | Todos los servicios |
| `customer-service.yaml` | customer-service |
| `account-service.yaml` | account-service |
| `credit-service.yaml` | credit-service |
| `transaction-service.yaml` | transaction-service |

Los valores usan variables de entorno con un valor por defecto (`${VARIABLE:defecto}`),
de modo que la misma configuración sirve en local y en Docker.
