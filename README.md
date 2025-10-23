# RESULTADOS.

**¿Cuál es la diferencia entre autenticación y autorizacion?**
Autenticación:	Verificar quién eres.	Cuando inicias sesión con tu correo y contraseña, el sistema verifica si eres un usuario válido.
Autorización:	Determinar qué puedes hacer.	Aunque estés logueado, no todos los usuarios pueden acceder a la sección de administración; se revisa si tu usuario tiene permisos.

**¿Cuál es la función del token JWT en la guía?**
El token JWT (JSON Web Token) sirve para autenticación y autorización:

1) Autenticación: Confirma que el usuario inició sesión correctamente.
2) Autorización: Permite al usuario acceder a rutas protegidas enviando el token en cada petición, y el servidor valida que tenga permisos.
