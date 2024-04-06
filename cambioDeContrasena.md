# Titulo
Vulnerabilidad por prevalencia de información despues del cambio de contraseña.

# Comportamiento esperado
Se espera que luego de cambiar la contraseña desde el perfil del usuario los datos de la contraseña no aparezcan en la interaz.

# Comportamiento actual
Al actalizar el password desde el perfil del usuario es posible abrir nuevamente el formulario y ver los datos de la contraseña anterior y la nueva contraseña.

# Pasos para reproducir el error
1. Iniciar sesión en en aplicativo GHOST.
2. Seleccionar el menú del usuario.
3. Seleccionar la opción de "Your profile".
4. Ir a la sección de Password.
5. Presionar el botón de change password.
6. Llenar los datos del formulario de cambio de contraseña.
7. Presionar el botón de change password.
8. Esperar a que desaparezca el formulario
9. Presionar nuevamente el botón de change password.
10. Cambiar el tipo de campo de cualquier password desde el html.
11. Se visualiza el valor del campo.

# Evidencias

https://www.youtube.com/watch?v=kDvCST4nKuc

# Contexto

**App Version**: 5.80.0
**OS**: Ubuntu 22.04.3 LTS
**Browser**: Opera One 109.0.5097.38

# Información adicional
Una posible solución sería reiniciar el contenido de los campos despues de que el cambio de password sea exitoso.