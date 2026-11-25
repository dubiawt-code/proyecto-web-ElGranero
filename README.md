# Nombre del emprendimiento
MiniMercado El Granero

## Integrantes
- Daniel Felipe Montero Saenz (@momomonda)
- Samuel Tuberquia David (@zVitallycode)
- Duban Lobo Zabala (@dubiawt-code)
  

## El cliente
El cliente es Nedyz Zabala, la dueña del MiniMercado El Granero en el barrio el espiritu santo en bello, ella vende productos para el consumo y el hogar, ella necesita una pagina facil de usar y rapida para ofrecer sus productos adomicilios

## El público
clientes que dessen realizar pedidos a domicilio

## Mapa del sitio

```text
el-granero-web/
│
├── index.html                  # Vista principal (Header, Hero, Categorías, Producto Destacado y Footer)
│
├── pages/                      # Vistas secundarias del sitio
│   ├── productos.html          # Catálogo completo con filtros por categoría y buscador
│   ├── ofertas.html            # Sección de promociones y descuentos del día
│   ├── contacto.html           # Información del local (Calle 10 # 25-30, horarios y contacto)
│   └── carrito.html            # Resumen de productos agregados y formulario de domicilio
│
├── css/                        # Hojas de estilo
│   └── styles.css              # Diseño general, layout, tarjetas y estilos responsivos
│
├── js/                         # Lógica e interactividad
│   ├── productos.js            # Base de datos de productos (Despensa, Fruver, Lácteos, Aseo)
│   ├── contador_y_carrito.js   # Control de cantidad [ + ] 1 [ - ], botón Agregar y persistencia del carrito
│   └── buscador.js             # Filtro dinámico desde la barra de búsqueda superior
│
├── assets/                     # Recursos estáticos
│   ├── img/
│   │   └── productos/          # Fotografías de los artículos del minimercado
│   └── icons/                  # Íconos de interfaz (lupa, carrito, ubicación, etc.)
│
└── README.md                   # Documentación del repositorio
```

## Paleta y tipografía
  --color-velvet-wine: #260212;
  --color-burgundy-stage: #4f0423;
  --color-impossible-red: #e10600;
  --color-blush-highlight: #ffc7c6;
  --color-butcher-black: #000000;
  --color-bone-white: #ffffff;

  Tipografia
  --font-sans-meat: 'sans-meat', 'Druk Wide', 'Knockout', 'Inter', 'Söhne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

## Boceto de la página de inicio
![Boceto](boceto.jpg) 

## Dueños de archivos
| Archivo | Dueño |
|---|---|
| index.html | Daniel Felipe Montero |
| servicios.html | Samuel Tuberquia |
| nosotros.html | Duban Lobo Zabala |
| contacto.html | Duban Lobo Zabala |
| css/kit.css y menú | Samuel Tuberquia |

## Pendientes
- [ ] Kit con las variables de la marca
- [ ] Menú igual en las 4 páginas
- [ ] Mejorar las paginas de HTML
- [ ] Empezar a construir el CSS
