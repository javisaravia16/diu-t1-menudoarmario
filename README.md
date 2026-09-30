# Documentación de la interfaz — Menudo armario
App android de tienda de ropa y calzado infantil (0 a 14 años) **Menudo armario**. Diseño basado en Material Design 3 y pensado para comprar rápido, con una mano y sin miedo a equivocarse de talla.

## 1. Justificación del diseño

### 1.1 Importancia del diseño centrado en el usuario

Quien compra ropa infantil casi nunca es quien la va a llevar. Compra una madre con el bebé en brazos, un padre en la cola del médico o un abuelo que no sabe qué talla usa su nieta. Si diseñamos pensando en el catálogo y no en estas personas, la app acaba siendo una web de tienda metida en un móvil: menús profundos, tallas confusas y formularios largos.

Por eso el proyecto sigue un proceso de diseño centrado en el usuario (ISO 9241-210): primero entender quién compra y en qué contexto, después decidir la estructura, prototipar y, por último, comprobar con personas reales si funciona. Cada decisión de la interfaz de este documento se apoya en un insight de la sección 2.4 o en un resultado de las pruebas de la sección 4.

### 1.2 Objetivos y metas del proyecto

| # | Objetivo | Cómo se mide | Meta |
| O1 | Comprar rápido | Tiempo desde Inicio hasta Confirmación en la tarea de compra | Menos de 2 minutos y al menos el 80 % de participantes lo consigue sin ayuda |
| O2 | Acertar con la talla | Participantes que eligen la talla correcta en la tarea de regalo usando la guía de tallas | 100 % de aciertos y menos de 30 s en la guía |
| O3 | Usable con una mano y accesible | Revisión de las 7 pantallas: áreas táctiles, posición de las acciones principales y contraste | 100 % de áreas táctiles ≥ 48 × 48 dp, acción principal siempre en la mitad inferior y todas las parejas de color ≥ 4,5:1 |

### 1.3 Beneficios esperados

Para quien compra
- Encuentra lo que busca en menos pasos gracias a la entrada por edad (Bebé, Niña, Niño).
- Menos dudas con las tallas: la guía está en el propio producto y traduce la talla a edad y altura.
- Puede deshacer errores (eliminar del carrito, datos mal escritos) sin empezar de nuevo.
- Puede comprar un regalo sin saber la talla exacta y cambiarlo en cualquier tienda física.

Para el negocio
- Menos devoluciones por talla equivocada, uno de los motivos de cambio más frecuentes en ropa infantil.
- Más pedidos terminados al reducir el checkout a una sola pantalla y permitir comprar como invitado.
- Más visitas a tienda física con la opción de recogida y cambio en tienda.
- Una base de diseño (tokens y componentes M3) reutilizable para futuras funciones y para una versión web.
