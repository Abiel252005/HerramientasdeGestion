# Normas básicas de trabajo colaborativo

## Uso de ramas

- `main` o `master`: rama estable.
- `develop`: rama de integración de avances.
- `feature/nombre-funcion`: ramas para nuevas funciones.
- `fix/nombre-error`: ramas para corrección de errores.

## Commits

Los commits deben ser claros y breves. Ejemplos:

```text
feat: agregar vista de reportes
fix: corregir validación de login
docs: actualizar manual de instalación
style: ajustar estilos de landing page
```

## Pull requests

Antes de fusionar cambios:

1. Verificar que el proyecto compile.
2. Revisar que no se suban archivos innecesarios como `node_modules/`.
3. Describir qué se modificó.
4. Solicitar revisión de al menos un integrante.

## Organización de documentación

Toda la documentación técnica debe mantenerse dentro de `docs/wiki/` y actualizarse cuando cambie la instalación, rutas, arquitectura o flujo de trabajo.

## Buenas prácticas

- No trabajar directamente en la rama estable.
- No subir contraseñas, tokens ni llaves privadas.
- Mantener nombres de archivos claros.
- Documentar errores conocidos.
- Usar issues o tareas para organizar pendientes.
