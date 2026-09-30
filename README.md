# Menudo Armario · App Android de ropa infantil

Tarea 1 de Diseño de Interfaces de Usuario: diseño centrado en el usuario y prototipo de alta fidelidad en Figma con **Material Design 3** para una cadena de tiendas de ropa y calzado infantil de 0 a 14 años.

- **Autor:** Francisco Javier Saravia Ogazón
- **Usuario de GitHub:** [javisaravia16](https://github.com/javisaravia16)

![Captura destacada: detalle de producto con la guía de tallas](capturas/prototipo/03b-guia-tallas.png)

## Enlaces

| Recurso | Enlace |
|---------|--------|
| Archivo de Figma | [Abrir en Figma](https://www.figma.com/design/Nrh4iQ6bEis6kerCMDAQs0/T1-Menudo-armario-javier-saravia) (compartido con la docente como «puede editar») |
| Prototipo navegable | [Abrir prototipo](https://www.figma.com/proto/Nrh4iQ6bEis6kerCMDAQs0/T1-Menudo-armario-javier-saravia?page-id=60824%3A73&node-id=60824-658&starting-point-node-id=60824%3A658&scaling=min-zoom&content-scaling=fixed) |
| Documentación completa | [DOCUMENTACION.md](DOCUMENTACION.md) |
| Tokens de la guía de estilo | [diseno/estilos.json](diseno/estilos.json) |

## Índice de la documentación

1. [Justificación del diseño](DOCUMENTACION.md#1-justificación-del-diseño)
   - [1.1 Importancia del diseño centrado en el usuario](DOCUMENTACION.md#11-importancia-del-diseño-centrado-en-el-usuario)
   - [1.2 Objetivos y metas del proyecto](DOCUMENTACION.md#12-objetivos-y-metas-del-proyecto)
   - [1.3 Beneficios esperados](DOCUMENTACION.md#13-beneficios-esperados)
2. [Investigación y análisis de usuarios](DOCUMENTACION.md#2-investigación-y-análisis-de-usuarios)
   - [2.1 Datos demográficos y segmentación](DOCUMENTACION.md#21-datos-demográficos-y-segmentación)
   - [2.2 Personas](DOCUMENTACION.md#22-personas)
   - [2.3 Análisis de la competencia](DOCUMENTACION.md#23-análisis-de-la-competencia)
   - [2.4 Insights y hallazgos clave](DOCUMENTACION.md#24-insights-y-hallazgos-clave)
3. [Diseño de la interfaz](DOCUMENTACION.md#3-diseño-de-la-interfaz)
   - [3.1 Mapa de navegación](DOCUMENTACION.md#31-mapa-de-navegación)
   - [3.2 Wireframes](DOCUMENTACION.md#32-wireframes)
   - [3.3 Guía de estilo Material Design 3](DOCUMENTACION.md#33-guía-de-estilo-material-design-3)
   - [3.4 Prototipo de alta fidelidad](DOCUMENTACION.md#34-prototipo-de-alta-fidelidad)
4. [Validación y pruebas](DOCUMENTACION.md#4-validación-y-pruebas)
   - [4.1 Metodología](DOCUMENTACION.md#41-metodología)
   - [4.2 Resultados](DOCUMENTACION.md#42-resultados)
   - [4.3 Iteraciones y mejoras](DOCUMENTACION.md#43-iteraciones-y-mejoras)
5. [Entrega y documentación final](DOCUMENTACION.md#5-entrega-y-documentación-final)
   - [5.1 Justificación del diseño propuesto](DOCUMENTACION.md#51-justificación-del-diseño-propuesto)
   - [5.2 Recomendaciones y pasos a seguir](DOCUMENTACION.md#52-recomendaciones-y-pasos-a-seguir)
6. [Referencias bibliográficas](DOCUMENTACION.md#6-referencias-bibliográficas)

## Estructura del repositorio

```
diu-t1-menudoarmario/
├── README.md              ← esta portada
├── DOCUMENTACION.md       ← documento principal (secciones 1 a 6)
├── diseno/
│   └── estilos.json       ← tokens de la guía de estilo M3
└── capturas/
    ├── wireframes/        ← PNG de baja fidelidad (7)
    ├── prototipo/         ← PNG de alta fidelidad 360×800 (7 + guía de tallas + 2 en oscuro)
    └── iteracion/         ← antes.png y despues.png
```

## Resumen del diseño

- **Color semilla** `#E0694E` (coral) con esquema claro y oscuro de Material Theme Builder; todas las parejas color/on-color superan 4,5:1.
- **Navigation bar** con tres destinos: Inicio, Carrito y Favoritos.
- **Componentes propios:** `TarjetaProducto` (normal, favorito, agotado) y `SelectorTalla` (disponible, seleccionada, sin stock).
- **Flujo de compra completo:** Inicio → Catálogo → Detalle → talla → Carrito → Checkout → Confirmación.
- **Herramientas:** Figma, Material 3 Design Kit, Material Theme Builder, VS Code, Git y Zotero.
