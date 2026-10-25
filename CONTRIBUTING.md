# Cómo contribuir a control-versiones-equipo1

## Ramas

- `main` siempre debe tener código que funcione. No se suben cambios directamente.
- Cada tarea se trabaja en su propia rama: `feature/nombre-de-la-tarea`.
- Los arreglos urgentes van en ramas `hotfix/descripcion`.

## Mensajes de commit

- Un commit debe representar un cambio.
- Utilizamos estos formatos:
  - `feat: añade una nueva funcionalidad`
  - `fix: corrige un error`
  - `docs: actualiza la documentación`
- Los mensajes deben ser cortos y no llevar punto final.

## Pull requests

- Cada Pull Request debe enlazar la Issue que resuelve, por ejemplo: `closes #5`.
- Otro miembro del equipo debe revisar y aprobar los cambios antes de fusionarlos.
- Después de fusionar el Pull Request, se borra la rama.

## Lo que nunca se sube

- Contraseñas, tokens ni claves privadas.
- Archivos de configuración personal, como `.env`, `.vscode/` e `.idea/`.