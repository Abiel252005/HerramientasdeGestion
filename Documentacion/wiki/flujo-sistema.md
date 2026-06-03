# Diagrama simple del flujo del sistema

## Flujo principal

```text
Usuario
  ↓
Landing Page pública
  ↓
Login / Registro
  ↓
Validación de credenciales y OTP mediante API
  ↓
Redirección por rol
  ├── Administrador / Manager → Panel administrativo
  │       ├── Dashboard global
  │       ├── Usuarios
  │       ├── Huertos
  │       ├── Regiones
  │       ├── Detección de plagas IA
  │       ├── Chatbot IA
  │       ├── Estadísticas
  │       └── Reportes
  └── Usuario productor → Dashboard de usuario
          ├── Seguimiento de huerto
          ├── Recomendaciones
          └── Consulta de información
```

## Explicación

El usuario accede a la landing page, revisa la información del proyecto y entra al módulo de autenticación. Después del inicio de sesión, el sistema valida la sesión y el rol del usuario. Los administradores ingresan al panel administrativo para supervisar usuarios, huertos, regiones, plagas, chatbot, estadísticas y reportes. Los usuarios productores acceden a su dashboard para consultar información relacionada con sus huertos y recomendaciones.
