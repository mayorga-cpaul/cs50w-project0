## Explicación del HTML de Clon de Amazon

Este archivo README explica la estructura y los componentes del código HTML proporcionado, que representa una página web simplificada similar a Amazon. El código está organizado en secciones como el encabezado, la sección hero, la sección de tienda y el pie de página. A continuación, se explica cada parte importante:

### Sección de Encabezado
La sección de encabezado contiene la barra de navegación y el logotipo de la página clon de Amazon.

- **Barra de Navegación**: La barra de navegación (`<div class="navbar">`) incluye varios elementos:
  - **Logotipo de Amazon**: Se muestra dentro de un contenedor `<div class="nav-logo">`.
  - **Dirección de Entrega**: Una sección que muestra la dirección de entrega y la ubicación.
  - **Barra de Búsqueda**: Permite a los usuarios buscar productos en el sitio web.
  - **Enlaces de Inicio de Sesión y Cuenta**: Proporciona enlaces para iniciar sesión, acceder a la cuenta del usuario y gestionar pedidos.
  - **Ícono de Carrito**: Muestra el número de artículos en el carrito de compras del usuario.

- **Panel**: Un panel de navegación secundario que contiene varias opciones como "Ofertas del día", "Servicio al Cliente", "Registro", "Tarjetas de Regalo" y "Vender".

### Sección Hero
La sección hero (`<section class="hero-section">`) muestra un mensaje sobre la experiencia de Amazon. Esta sección contiene un solo `<div class="hero-msg">` con texto de muestra.

### Sección de Tienda
La sección de tienda (`<section class="shop-section">`) muestra múltiples cajas de productos, cada una representando una categoría o tipo de producto diferente.

- **Cajas de Producto**: Una serie de elementos `<div class="box">`, cada uno representando una categoría de producto. Dentro de cada caja, hay:
  - **Nombre de la Categoría**: Se muestra como un encabezado `<h2>`.
  - **Imagen de la Categoría**: Una imagen de fondo que representa la categoría.
  - **Enlace "Ver Más"**: Un enlace para explorar más productos dentro de la categoría.

### Sección de Pie de Página
El pie de página (`<footer>`) contiene varias secciones con enlaces e información sobre Amazon.

- **Sección Superior**: Contiene un enlace "Volver arriba".
- **Sección Media**: Dividida en columnas, cada una contiene enlaces relacionados con diferentes categorías, como "Conócenos", "Gana dinero con nosotros" y "Productos de Pago de Amazon".
- **Sección Inferior**: Similar a la sección media, presenta más enlaces relacionados con los servicios y ofertas de Amazon.
- **Información de Derechos de Autor**: Contiene información legal sobre los términos de uso y los derechos de autor de Amazon.

### Recursos Externos
- **Iconos FontAwesome**: El código HTML importa iconos de FontAwesome para elementos visuales como búsqueda, carrito, barras, etc.
- **Hoja de Estilos CSS**: El código HTML incluye una hoja de estilos externa (`style.css`) para dar estilo a la página web. Esta hoja de estilos se encuentra en la carpeta "styles" en relación con el archivo HTML.

### Uso de SASS

```
sass components/_index.style.scss styles/style.css
```