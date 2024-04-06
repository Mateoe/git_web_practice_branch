# Titulo
Bloqueo de la opción para alternar entre modo oscuro y modo claro cuando el nombre de usuario es un epacio en blanco (" ").

# Comportamiento esperado
Se espera que el usuario pueda alternar entre modo oscuro y modo claro cuando lo desee.

# Comportamiento actual
Si en nombre de usuario se cambia por un espacio en blanco (" ") y posterior a ello se intenta cambiar el modo de visibilidad a modo oscuro el botón se bloquea y no permite retornar al modo claro.

# Pasos para reproducir el error
1. Iniciar sesión en en aplicativo GHOST.
2. Seleccionar el menú del usuario.
3. Seleccionar la opción de "Your profile".
4. Cambiar el contenido del campo Full name por un espacio en blanco.
5. Presionar el botón "Save".
6. Volver a la interfaz principal.
7. Cambiar el modo de visivilidad a modo oscuro.
8. Intentar cambiar nuevamente el modo de visibilidad a modo claro.

# Evidencias

https://www.youtube.com/watch?v=aV1Qakp1K30

# Contexto

**App Version**: 5.80.0
**OS**: Ubuntu 22.04.3 LTS
**Browser**: Opera One 109.0.5097.38

# Información adicional
Una posible solución sería establecer un numero mínimo de caracteres para el Full name del usuario (diferentes a espacio en blanco).