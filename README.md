# Programación Orientada a Objetos - UNAL

# Ana María Amaya Gómez

## Reto 2: Objetos y clases
Elija un problema de la vida real (sistema de gestión de biblioteca, negocio de compra-venta, automóvil, etc) que se pueda modelar a través de objetos y clases. Plantee las relaciones de clases, composiciones, propiedades y comportamientos del sistema en uno mas diagramas tipo UML.

## Tienda Online
Se tuvo en cuenta un sistema que gestione las compras de un usuario online.
Para esto partimos de la clase Usuario, quien realizará las acciones de compra dentro del sistema.

<div align="center">
<img width="246" alt="{800115FB-AF59-45EC-909B-6C82E0F6AD4C}" src="https://github.com/user-attachments/assets/766f8904-0b2b-4caf-8d02-9719a38b8c28">
</div>

Posterior a ello se considera la creación de las siguientes clases para los procesos que necesita desarrolar el usuario:
- Producto: La página presenta una seleción de productos que el usuario esté buscando para comprar.
- Carrito de compra: Le permite al usuario listar los productos deseados y así mismo verificar el costo total antes de pagar.
- Pagos: Realiza la transferencia y confirmación del dinero correspondiente a la compra, así mismo autoriza el pedido cuando el pago fue recibido correctamente.
- Pedido: Genera la orden de compra permitiendo al usuario finalizar el proceso.

Así es como se plantean las relaciones:

![Esquema](https://github.com/AnaAmaya200/Reto_2/blob/main/EsquemaBase.drawio.png)

Podemos concluir el sistema allí, sin embargo en caso tal de verlo como una página web realmente funcional se plantea dicha super clase como Pagina web donde además de eso se tienen presentes las siguientes clases relacionadas a la inferfaz con la que interactúa el usuario.
- Pagina web: es el Centro de control de todo lo ejecutado
- Menú: para una navegación ordenada
- Ajustes: Principalmente para que el usuario tenga control de la información que maneja la página

Con la siguiente relación:

