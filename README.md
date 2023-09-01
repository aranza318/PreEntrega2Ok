# PreEntrega2Ok
En esta presentacion he cambiado algunas ubicaciones, al abrir el archivo nos encontraremos con:
_Una carpeta de scr que contiene dentro:
A. Una carpeta dao que incluye:
  1. Carpeta fs: que tiene dentro los managers file sistem de cart y products.
  2. Carpeta models: contiene los modelos de producto, carrito y mensaje.
  3. Managers de carritos, productos y mensajes.
B. Una carpeta public que aloja a:
  1. Carpeta css: contiene los estilos.
  2. Carpeta images: contiene el logo del cliente.
  3. Cart.js: maneja los productos que entran al carrito por handlebars.
  4. Chat.js: trabaja con los endpoints de chat.
  5. RealTimeProducts.js: funciona junto al formulario.
C. Routes: que contiene a las diferentes rutas.
_Por otro lado estara la carpeta de Views que almacena:
A.Carpeta Layouts: donde se aloja el handelbars pricipal.
B. Handelbars: cart, products, product, realtimeproducts, home y chat.
_App: que conecta con mongoose y las demas dependencias para que la api se conecte con el mundo.
_Utils: aloja al __dirname.
