# RcParts - Ecommerce Demo

**RcParts** es una tienda de demostración en línea para la venta de productos de modelos a radio control. Este proyecto está desarrollado en **ReactJS** y utiliza diversas dependencias modernas para una experiencia de usuario fluida y profesional.

## Índice

- [Descripción](#descripción)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [Dependencias](#dependencias)

## Descripción

Este proyecto es una **demo** de un ecommerce que ofrece una variedad de productos para **radio controlados**, como autos, drones, y accesorios relacionados. La tienda incluye funcionalidades básicas como:

- Vista de productos
- Carrito de compras
- Checkout
- Notificaciones y alertas con **React-Toastify** y **SweetAlert2**

El objetivo de este proyecto es mostrar una posible implementación de una tienda online utilizando **ReactJS** con varias herramientas y bibliotecas para mejorar la experiencia del usuario.

## Tecnologías utilizadas

- **[ReactJS](https://reactjs.org/)**: Biblioteca de JavaScript para construir interfaces de usuario.
- **[Bootstrap 5](https://getbootstrap.com/)**: Framework de CSS para diseñar interfaces responsivas y modernas.
- **[Firebase](https://firebase.google.com/)**: Plataforma para autenticación y base de datos en tiempo real.
- **[React-Bootstrap](https://react-bootstrap.github.io/)**: Componentes de Bootstrap para React.
- **[React Router](https://reactrouter.com/)**: Enrutamiento dinámico para navegación entre vistas.
- **[React-Icons](https://react-icons.github.io/react-icons/)**: Biblioteca de iconos para React.
- **[React-Loading-Skeleton](https://www.npmjs.com/package/react-loading-skeleton)**: Indicadores de carga animados. (utilizado en los links del navbar)
- **[React-Spinners](https://www.npmjs.com/package/react-spinners)**: Indicadores de carga animados. (utilizado en la vista mientras se carga los productos)
- **[React-Toastify](https://fkhadra.github.io/react-toastify/)**: Notificaciones para mostrar mensajes en la interfaz de usuario. (utilizado cuando se agrega, quita o vacía los productos del carrito)
- **[SweetAlert2](https://sweetalert2.github.io/)**: Ventanas emergentes personalizadas para alertas. (utilizado para recibir confirmación de parte del usuario cuando se quita o vacía el carrito)
- **[Yup](https://github.com/jquense/yup)**: Biblioteca para validación de formularios. (utilizado para validar el formulario checkout)

## Instalación

Para comenzar a usar este proyecto, sigue estos pasos:

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/pablomailhet/reactjs.git
   ```

2. **Instala las dependencias**:

   Una vez clonado el repositorio, entra en el directorio del proyecto y ejecuta:

   ```bash
   cd reactjs
   npm install
   ```

3. **Configura Firebase**:

    Para usar la base de datos de Firebase, necesitarás crear el archivo `.env` en la raiz del proyecto con las siguientes claves. Los valores serán proporcionados por el desarrollador:
    
    - `VITE_API_KEY`
    - `VITE_AUTH_DOMAIN`
    - `VITE_PROJECT_ID`
    - `VITE_STORAGE_BUCKET`
    - `VITE_MESSAGING_SENDER_ID`
    - `VITE_APP_ID`

4. **Ejecuta la aplicación**:

   Después de instalar las dependencias y configurar Firebase, ejecuta el siguiente comando para iniciar la aplicación en modo de desarrollo:

   ```bash
   npm run dev
   ```

   La aplicación se ejecutará de forma local en `http://localhost:5173/` y de forma remote en `https://pm-reactjs.vercel.app/`

## Uso

- **Navegación**: Utiliza la barra de navegación para explorar las diferentes categorías de productos y acceder al carrito de compras.
- **Agregar al carrito**: Selecciona productos y agrégales al carrito para proceder con la compra.

Este proyecto está orientado a ser una demostración, por lo que el proceso de pago no está integrado con ningún sistema real.

## Dependencias

El proyecto utiliza las siguientes dependencias:

```json
"dependencies": {
  "bootstrap": "^5.3.3",              // Framework de CSS para diseño responsivo
  "firebase": "^11.0.1",              // Autenticación y base de datos en tiempo real
  "react": "^18.3.1",                 // Biblioteca de JavaScript para interfaces de usuario
  "react-bootstrap": "^2.10.5",       // Componentes de Bootstrap para React
  "react-dom": "^18.3.1",             // Módulo de React para manipular el DOM
  "react-icons": "^5.3.0",            // Iconos para React
  "react-loading-skeleton": "^3.5.0", // Indicadores de carga animados
  "react-router-dom": "^6.27.0",      // Enrutamiento para React
  "react-spinners": "^0.14.1",        // Indicadores de carga animados
  "react-toastify": "^10.0.6",        // Notificaciones en la UI
  "sweetalert2": "^11.14.5",          // Alertas personalizadas
  "yup": "^1.4.0"                     // Validación de formularios
}
```

### Notas:

Este README.md proporciona un punto de partida claro y detallado para cualquier usuario que quiera entender y trabajar con tu proyecto. Puedes ajustarlo y expandirlo según tus necesidades específicas.