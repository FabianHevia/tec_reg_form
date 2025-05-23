# tec_reg_form
Prueba técnica jr resuelta para validar un formulario de registro resuelta.

# Enunciado
Estás trabajando en una aplicación web donde los usuarios pueden registrarse. Tu tarea es implementar la validación básica del formulario usando JavaScript puro.

# Tarea
Implementa un script en JavaScript que:

Valide que el campo nombre no esté vacío.
Valide que el correo electrónico sea válido (usa una expresión regular simple).
Valide que la contraseña tenga al menos 6 caracteres.
Valide que la confirmación de contraseña coincida con la contraseña introducida.
Muestre los errores en el div#errors si alguna validación falla.
Si todo está correcto, muestra un mensaje de éxito (por ejemplo: "Registro exitoso") en verde.

Detalles adicionales:

No debes usar alert() ni prompt().
Puedes usar addEventListener para manejar el evento submit.
Limpia los mensajes anteriores cada vez que se intente enviar el formulario.
No es necesario hacer una llamada real al backend.

# Ejemplo

Si el usuario envía el formulario con:

Nombre vacío
Contraseñas que no coinciden

Se debería mostrar algo como:

- El nombre es obligatorio.
- Las contraseñas no coinciden.

# Objetivos evaluados

Uso básico del DOM y eventos.
Manipulación de elementos del formulario.
Validación de datos con condiciones.
Manejo de errores y mensajes amigables.
Buenas prácticas de código (legibilidad, comentarios, etc.).

# Bonus
Agregar estilos dinámicos (clases) a los campos inválidos.
Usar funciones separadas por tipo de validación para modularizar mejor el código.