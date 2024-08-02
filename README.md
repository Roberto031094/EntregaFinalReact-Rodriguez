Unas aclaraciones del proyecto:

-Hay cosas en la ruta "detalle" que van a ser un poco diferentes a como venimos trabajando ya que las cambié para que se pareciesen un poco a los eCommerce de mascotas que usá como referencia:
  1) Como los "productos" son realmente seres vivos, cambié la palabra Stock por Disponibilidad. Por la misma razón el stock por item es reducido (3), ya que en algunos sitios no te dejaba llevar más de 1 por compra.
  2) Con esta misma lógica, hice que el usuario solo pudiera agregarlos al carrito de a uno, por más que haya un contador de stock.
  3) Los elementos que pertenecen a un mismo Item se guardan por separado en localStorage, ya que a cada uno se le genera una key única usando su Id+.Date.

-Estando ya en CartView, los items se eliminan de la misma forma a como se guardan, o sea, por separado.

-Las librerías que usé son Bootstrap, toastify y SweetAlert. Esto por que se me hacen más "amigables" en lo que respecta a la experiencia del usuario.

-Sobre Firebase:
 1) Al enviar la orden desde Checkout, el mensaje va a tardar unos segundos en aparecer. Es un SweetAlert sencillo.
 2) Hice muy pocas pruebas, pero hasta ahora no ha habido problemas con el envío de datos a la Database.
 3) El proyecto es de prueba y lo creé la semana pasada, a sí que deberpia estar vigente hasta finales de agosto.




Sin más que agregar, me despido. 
