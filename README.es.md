<!-- hide -->
# ¡Construye una App de Comercio Electrónico Básica con Next.js!
<!-- endhide -->

## 🌱 ¿Cómo iniciar este proyecto?

No clones este repositorio porque vamos a utilizar una plantilla diferente.

> ⚠ ¡Necesitarás tener Node.js instalado si lo haces localmente, pero todo eso ya está instalado en Codespaces o Gitpod!

## 📝 Instrucciones

### Paso 1: Configura el Proyecto

- [ ] Configura el proyecto base siguiendo los pasos dados en la documentación oficial de NextJS: https://nextjs.org/docs/getting-started/installation.

- [ ] Sigue las instrucciones en el README del repositorio para configurar tu entorno de desarrollo.

### Paso 2: Planifica la Estructura de la App

- [ ] Define las páginas que tendrá tu aplicación, como:

  - Página principal que muestra una lista de productos.
  - Página de detalles de producto.
  - Carrito de compras.
  - Página de checkout.

- [ ] Decide cómo estructurarás los componentes y las rutas en Next.js.

### Paso 3: Crea la Lista de Productos

- [ ] Crea un conjunto de datos de ejemplo para tus productos. Puedes crear un archivo `products.js` con un array de objetos que representen los productos.

```json
[
  {
    id: 1,
    name: 'Producto 1',
    price: 19.99,
    image: '/images/product1.jpg',
    description: 'Descripción del Producto 1',
  },
  // ...más productos
]
```

- [ ] En la página principal (`pages/index.js`), importa la lista de productos y muestra cada producto con su nombre, imagen y precio.

### Paso 4: Crea la Página de Detalles del Producto

- [ ] Crea una página dinámica para los detalles del producto en `pages/product/[id].js`.

- [ ] Usa `getStaticPaths` y `getStaticProps` para generar páginas estáticas para cada producto.

### Paso 5: Implementa el Carrito de Compras

- [ ] Utiliza el hook `useState` o `useContext` para manejar el estado del carrito de compras.

- [ ] Crea un contexto (`CartContext`) para compartir el estado del carrito en toda la aplicación.

- [ ] Envuelve tu aplicación con el `CartProvider` en `_app.js`.

### Paso 6: Crea la Página del Carrito

- [ ] Crea una página `/cart` que muestre los productos añadidos al carrito.

- [ ] Permite al usuario modificar la cantidad o eliminar productos del carrito.

### Paso 7: Crea la Página de Checkout

- [ ] Crea una página `/checkout` donde el usuario pueda ingresar sus datos y confirmar la compra.

- [ ] No es necesario procesar pagos reales; puedes simular el proceso.

### Paso 8: Mejora la Interfaz de Usuario

- [ ] Utiliza CSS o una librería como Tailwind CSS o Bootstrap para mejorar el diseño de tu aplicación.

- [ ] Asegúrate de que la aplicación sea responsiva y funcione bien en diferentes dispositivos.

## Sección de Bonus

### Características Adicionales para Practicar y Mejorar el Proyecto

1. **Filtrado y Búsqueda:** Implementa funcionalidades para filtrar productos por categoría y buscar por nombre.

2. **Cantidad en el Carrito:** Permite al usuario seleccionar la cantidad de cada producto en el carrito.

3. **Persistencia de Datos:** Almacena el estado del carrito en `localStorage` para que persista al recargar la página.

4. **Autenticación de Usuario:** Implementa un sistema básico de registro e inicio de sesión.

5. **Integración con una API:** Conecta tu aplicación con una API real o simulada para obtener los productos.

6. **Optimización SEO:** Aprovecha las características de renderizado en el servidor de Next.js para mejorar el SEO.

7. **Paginación:** Si tienes muchos productos, agrega paginación a la lista de productos.

8. **Procesamiento de Pagos:** Integra un servicio como Stripe para procesar pagos reales.

¡Explora diferentes mejoras para hacer tu aplicación de comercio electrónico más completa y funcional!
