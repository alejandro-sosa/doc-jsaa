# Documentacion de rama: docs

**Proyecto:** user
**Creado:** 2026-03-10 16:46

> Este documento se actualiza automaticamente con cada push.



---

## Fecha: 2026-03-10 - 2026-03-10 16:46

### Rama: docs
**Proyecto:** user

### Resumen de cambios
RESUMEN DE CAMBIOS - RAMA DOCS / PROYECTO USER

1. Se agregaron metodos y controladores para la funcionalidad de restablecimiento de contrasena en el sistema de autenticacion.

2. Se actualizo el archivo SecurityConfig.java para incorporar nuevas configuraciones de seguridad relacionadas con el flujo de recuperacion de credenciales.

3. Se extendio AuthController.java con nuevos endpoints que permiten a los usuarios solicitar y procesar el restablecimiento de contrasena.

4. Se modifico AuthService.java incorporando la logica de negocio necesaria para validar solicitudes y generar tokens de recuperacion.

5. Se creo un nuevo archivo MailService.java para manejar el envio de correos electronicos con instrucciones de restablecimiento de contrasena a los usuarios.

Cambios realizados por: Alejandro
Fecha: 2026-03-10

### Commits
- aa24603 agrego metodos y controladores para restablecer contrase├▒a (por Alejandro, 2026-03-10)

### Archivos modificados
- M	pom.xml
- M	src/main/java/ar/com/tecnoaccion/config/SecurityConfig.java
- M	src/main/java/ar/com/tecnoaccion/controllers/AuthController.java
- M	src/main/java/ar/com/tecnoaccion/services/AuthService.java
- A	src/main/java/ar/com/tecnoaccion/services/MailService.java

