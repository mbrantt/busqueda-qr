# **Búsqueda del Tesoro con Códigos QR**

## **Descripción del Proyecto**
Una aplicación móvil en la que los jugadores siguen pistas a través de códigos QR escondidos en diferentes lugares. Al completar cada misión, los jugadores desbloquean medallas digitales y, en misiones especiales, cupones o descuentos como recompensa.

## **Características Clave**
1. **Selección de Misión**: Los jugadores eligen misiones basadas en su ubicación.
2. **Escaneo de Códigos QR**: Cada código desbloquea la siguiente pista.
3. **Medallas y Recompensas**: Por completar misiones, los jugadores ganan medallas y, en juegos especiales, códigos de descuento.
4. **Tablero de Líderes**: Clasificación de jugadores según las misiones completadas.

## **Tecnología Utilizada**
- **Backend**: Node.js + Express
- **Frontend**: React Native (pendiente de desarrollo)
- **Base de Datos**: MongoDB

## **Instalación y Configuración**
1. Clona este repositorio y navega al directorio del backend:
   ```bash
   git clone <url-del-repositorio>
   cd backend
2. Instala las dependencias y configura las variables de entorno en .env (ejemplo: PORT=3000 y DB_URI=<tu_conexion_a_mongodb>).

3. Inicia el servidor de desarrollo:
    ```bash
    npm run dev
## **Estructura del Proyecto**
```bash
backend/
├── config/        # Configuración de la base de datos y variables de entorno
├── controllers/   # Lógica de los endpoints
├── models/        # Modelos de datos
├── routes/        # Rutas de la API
├── middleware/    # Middleware para autenticación y otros procesos
├── utils/         # Utilidades generales
├── .env           # Variables de entorno
├── server.js      # Archivo principal del servidor
└── package.json   # Archivo de configuración de Node
