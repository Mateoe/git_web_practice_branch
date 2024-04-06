# Titulo
Redirección inesperada al presionar multiples veces el botón "Sign in"

# Comportamiento esperado
Se espera que al llenar los campos de inicio de sesión y presionar el botón "Sign in", si los campos son correctos siempre se ingrese a la interfaz principal del aplicativo.

# Comportamiento actual
Una vez se llenan los datos de inicio de sesión y se presiona el botón "Sign in" multiples veces, se redirige de inesperada a una ventana de error (Page not found).

# Pasos para reproducir el error
1. Ingresar al aplicativo GHOST estando previamente registrado.
2. Llenar los datos del formulario de inicio de sesión del usuario registrado.
3. Presionar multiples veces el botón de "Sign in".

# Evidencias

https://www.youtube.com/watch?v=aHPJQBHTuTw

# Contexto

**App Version**: 5.80.0
**OS**: Ubuntu 22.04.3 LTS
**Browser**: Opera One 109.0.5097.38

# Información adicional
Una posible solución podría ser inhabilitar el botón una vez se presiona, hasta que se valide si es posible iniciar la sesión.