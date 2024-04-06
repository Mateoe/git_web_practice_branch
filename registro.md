# Titulo
Redirección inesperada al presionar multiples veces el botón "Create account & start publishing"

# Comportamiento esperado
Se espera que al llenar los campos de registro y presionar el botón "Create account & start publishing", si los campos son correctos siempre se inicie automáticamente la sesión en la interfaz de bienvenida del aplicativo.

# Comportamiento actual
Una vez se llenan los datos de registro correctamente y se presiona el botón "Create account & start publishing" multiples veces, se redirige de forma inesparada a la interfaz de inicio de sesión.

# Pasos para reproducir el error
1. Ingresar al aplicativo GHOST sin estar registrado.
2. Llenar los datos del formulario de registro.
3. Presionar multiples veces el botón de "Create account & start publishing".

# Evidencias

https://www.youtube.com/watch?v=ZXnhke04PdU

# Contexto

**App Version**: 5.80.0
**OS**: Ubuntu 22.04.3 LTS
**Browser**: Opera One 109.0.5097.38

# Información adicional
Una posible solución podría ser inhabilitar el botón una vez se presiona y se garantiza el inicio de sesión.