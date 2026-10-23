# Historias de Usuario — Sauz Store

> Cada historia sigue la estructura: **Como / Quiero / Para**, criterios de aceptación, prioridad y estimación.

---

## US-01 — Registro de usuario
**Como** usuario
**Quiero** crear una cuenta
**Para** poder utilizar la plataforma.

### Criterios de aceptación
- El usuario debe ingresar nombre.
- El usuario debe ingresar correo electrónico.
- El usuario debe ingresar contraseña.
- El sistema debe validar los datos (correo con formato válido, contraseña con mínimo de caracteres).
- El sistema no debe permitir registrar un correo ya existente.
- El usuario debe recibir confirmación del registro.

**Prioridad:** Alta
**Estimación:** 5 puntos
**Épica / Feature:** 1 / 1.1

---

## US-02 — Recuperar contraseña
**Como** usuario
**Quiero** recuperar mi contraseña
**Para** poder acceder nuevamente a mi cuenta.

### Criterios de aceptación
- El usuario debe poder solicitar la recuperación con su correo.
- El sistema debe informar si el correo no está registrado.
- El usuario debe poder establecer una nueva contraseña.
- El sistema debe confirmar que la contraseña fue cambiada.

**Prioridad:** Media
**Estimación:** 3 puntos
**Épica / Feature:** 1 / 1.1

---

## US-03 — Inicio de sesión
**Como** usuario
**Quiero** iniciar sesión
**Para** acceder a mi cuenta.

### Criterios de aceptación
- El usuario debe ingresar correo y contraseña.
- El sistema debe validar las credenciales.
- Si las credenciales son incorrectas, se debe mostrar un mensaje de error claro.
- Si son correctas, el usuario accede a su cuenta.
- El usuario debe poder cerrar sesión.

**Prioridad:** Alta
**Estimación:** 5 puntos
**Épica / Feature:** 1 / 1.2

---

## US-04 — Visualizar productos
**Como** usuario
**Quiero** visualizar los productos
**Para** conocer las opciones disponibles.

### Criterios de aceptación
- Se debe mostrar una lista de productos con imagen, nombre y precio.
- Solo se muestran productos disponibles.
- La vista debe adaptarse a computador y celular.
- Si no hay productos, se debe mostrar un mensaje informativo.

**Prioridad:** Alta
**Estimación:** 3 puntos
**Épica / Feature:** 2 / 2.1

---

## US-05 — Buscar productos
**Como** usuario
**Quiero** buscar productos por nombre
**Para** encontrar rápidamente lo que necesito.

### Criterios de aceptación
- Debe existir un campo de búsqueda visible.
- Los resultados deben coincidir con el texto ingresado.
- Si no hay resultados, se debe mostrar un mensaje claro.

**Prioridad:** Media
**Estimación:** 3 puntos
**Épica / Feature:** 2 / 2.1

---

## US-06 — Filtrar productos por categoría y talla
**Como** usuario
**Quiero** filtrar productos por categoría y talla
**Para** ver solo las prendas que me interesan.

### Criterios de aceptación
- Se puede filtrar por categoría (camisetas, pantalones, vestidos, etc.).
- Se puede filtrar por talla.
- Los filtros se pueden combinar.
- Se pueden limpiar los filtros.

**Prioridad:** Media
**Estimación:** 5 puntos
**Épica / Feature:** 2 / 2.2

---

## US-07 — Ver detalle de un producto
**Como** usuario
**Quiero** ver el detalle de un producto
**Para** conocer sus características, colores, tallas y precio.

### Criterios de aceptación
- Se muestra imagen, nombre, descripción, precio, tallas y colores.
- Se indica si hay disponibilidad.
- Existe un botón para agregar al carrito.

**Prioridad:** Alta
**Estimación:** 3 puntos
**Épica / Feature:** 2 / 2.2

---

## US-08 — Agregar productos al carrito
**Como** cliente
**Quiero** agregar productos al carrito
**Para** reunir lo que deseo comprar.

### Criterios de aceptación
- El cliente debe seleccionar talla y color antes de agregar.
- El carrito muestra la cantidad de productos agregados.
- No se puede agregar más cantidad que el stock disponible.

**Prioridad:** Alta
**Estimación:** 5 puntos
**Épica / Feature:** 3 / 3.1

---

## US-09 — Modificar o eliminar productos del carrito
**Como** cliente
**Quiero** modificar o eliminar productos del carrito
**Para** ajustar mi compra antes de pagar.

### Criterios de aceptación
- Se puede cambiar la cantidad de cada producto.
- Se puede eliminar un producto del carrito.
- El total se actualiza automáticamente.

**Prioridad:** Media
**Estimación:** 3 puntos
**Épica / Feature:** 3 / 3.1

---

## US-10 — Realizar pedido
**Como** cliente
**Quiero** realizar un pedido
**Para** recibir mis prendas en mi dirección.

### Criterios de aceptación
- El cliente debe estar autenticado.
- Debe ingresar dirección de envío.
- Se muestra un resumen del pedido antes de confirmar.
- Al confirmar, se genera un número de pedido.

**Prioridad:** Alta
**Estimación:** 8 puntos
**Épica / Feature:** 4 / 4.1

---

## US-11 — Pagar el pedido en línea
**Como** cliente
**Quiero** pagar mi pedido en línea
**Para** finalizar la compra de forma segura.

### Criterios de aceptación
- Se ofrecen al menos dos métodos de pago.
- El sistema confirma si el pago fue exitoso o fallido.
- El estado del pedido se actualiza según el resultado del pago.

**Prioridad:** Alta
**Estimación:** 8 puntos
**Épica / Feature:** 4 / 4.2

---

## US-12 — Consultar historial de pedidos
**Como** cliente
**Quiero** consultar mi historial de pedidos
**Para** hacer seguimiento a mis compras.

### Criterios de aceptación
- Se listan los pedidos del cliente con fecha, total y estado.
- Se puede ver el detalle de cada pedido.

**Prioridad:** Media
**Estimación:** 3 puntos
**Épica / Feature:** 4 / 4.1

---

## US-13 — Crear y editar productos (administrador)
**Como** administrador
**Quiero** crear y editar productos
**Para** mantener el catálogo actualizado.

### Criterios de aceptación
- Se puede registrar nombre, descripción, precio, categoría, tallas, colores e imagen.
- Se puede editar un producto existente.
- Solo el administrador puede acceder a esta función.

**Prioridad:** Alta
**Estimación:** 5 puntos
**Épica / Feature:** 5 / 5.1

---

## US-14 — Gestionar inventario (administrador)
**Como** administrador
**Quiero** gestionar el inventario
**Para** saber qué prendas hay disponibles.

### Criterios de aceptación
- Se puede ver el stock por producto, talla y color.
- Se puede actualizar el stock manualmente.
- Los productos sin stock se marcan como agotados.

**Prioridad:** Media
**Estimación:** 5 puntos
**Épica / Feature:** 5 / 5.1

---

## US-15 — Gestionar pedidos (administrador)
**Como** administrador
**Quiero** gestionar los pedidos
**Para** cambiar su estado y atender a los clientes.

### Criterios de aceptación
- Se listan todos los pedidos con su estado.
- Se puede cambiar el estado (pendiente, pagado, enviado, entregado, cancelado).
- Se puede ver el detalle de cada pedido.

**Prioridad:** Media
**Estimación:** 5 puntos
**Épica / Feature:** 5 / 5.2
