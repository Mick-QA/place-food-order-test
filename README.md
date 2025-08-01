# place-food-order-test
Prueba manual para verificar el proceso de realizar un pedido de alimentos en una app de entrega.

**ID:** QAUL-OC36 
**Nombre del caso:** Verificar que el usuario pueda realizar un pedido de alimentos correctamente  
**Precondiciones:** 
- Usuario con cuenta activa y sesión iniciada  
- Método de pago registrado  
- Dirección de entrega guardada en el perfil  

**Pasos:**
1. Iniciar sesión en la aplicación.
2. Navegar al menú o listado de restaurantes.
3. Seleccionar un restaurante disponible.
4. Elegir uno o más productos del menú.
5. Agregar los productos a la cesta.
6. Ir al carrito y confirmar los productos seleccionados.
7. Proceder a la pantalla de pago.
8. Seleccionar la dirección y método de pago.
9. Confirmar el pedido.
10. Verificar que se muestre un mensaje de confirmación y el número de pedido.
11. Ir a la sección de "Mis pedidos" para revisar el estado del pedido.

**Resultado esperado:**
- El sistema debe permitir completar todo el flujo de pedido sin errores.
- Debe mostrarse un mensaje claro de confirmación.
- El pedido debe aparecer en la lista de "Mis pedidos" con el estado “En preparación” o similar.

**Resultado obtenido:**
✅ El usuario pudo completar el proceso de pedido sin errores.  
✅ Se mostró el mensaje: *“Tu pedido ha sido confirmado. Número de pedido #485721”*  
✅ El pedido apareció en la sección de "Mis pedidos" con estado: *En preparación*

**Estado de la prueba:** PASADA ✅
