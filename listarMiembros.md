# Titulo
El numero de miembros no se actualiza correctamente.

# Comportamiento esperado
Se espera que luego de ingresar un nuevo miembro, la numeración que se encuentra al lado de la pestaña "Members" se actualice correctamente.

# Comportamiento actual
No se actualiza el valór de la numeración que se encuentra al lado de la pestaña "Members" hasta que se ingresa a la pestaña y se listan los miembros.

# Pasos para reproducir el error
1. Iniciar sesión en en aplicativo GHOST.
2. Ingresar a pestaña "Members".
3. Presionar el botón New member.
4. Diligencir la información del formulario.
5. Presionar el botón Save.
6. Presionar alguna otra pestaña de la barra lateral.
7. Visualizar el contador que se encuentra al lado de la pestaña "members".


# Evidencias

https://www.youtube.com/watch?v=ud2CjLm9DO0

# Contexto

**App Version**: 5.80.0
**OS**: Ubuntu 22.04.3 LTS
**Browser**: Opera One 109.0.5097.38

# Información adicional
Una posible solución sería actualizar dinámicamente el contexto de la variable del contador.