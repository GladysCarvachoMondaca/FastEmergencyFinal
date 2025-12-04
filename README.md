============================================================ 🚑
 FAST EMERGENCY - SISTEMA DE GESTIÓN DE VOLUNTARIADO
Este proyecto contiene todo el código fuente, dependencias y configuraciones listas para ejecutar.

NOTAS IMPORTANTES:

Se incluyen las carpetas 'node_modules' para facilitar la ejecución.
Se incluye el archivo '.env' con las credenciales de base de datos.
Requiere tener MongoDB corriendo localmente.
INSTRUCCIONES DE INICIO RÁPIDO
PASO 1: ENCENDER EL BACKEND (Servidor)

Abra una terminal en la carpeta "BackEnd".

Ejecute el siguiente comando: npm run dev

(Si falla, intente con: node index.js)

Debería ver el mensaje: "Servidor backend corriendo en el puerto 3000"
PASO 2: ENCENDER EL FRONTEND (Página Web)

Abra otra terminal nueva en la carpeta "FrontEnd".
Ejecute el siguiente comando: npm run dev
Abra el link que aparece (ej: http://localhost:5173/) en su navegador.
PASO 3: CARGAR DATOS DE PRUEBA (SEEDS)
Si la base de datos está vacía, ejecute estas peticiones POST para crear los albergues y usuarios necesarios (en este orden):

Crear Albergues: [POST] http://localhost:3000/api/albergues/seed

Crear Usuarios: [POST] http://localhost:3000/api/usuarios/seed

SOLUCIÓN DE PROBLEMAS
Si al ejecutar 'npm run dev' aparecen errores extraños (debido a que se descargó en un sistema operativo diferente):

Borre la carpeta 'node_modules' dentro de BackEnd y FrontEnd.
Ejecute 'npm install' en ambas carpetas.
Vuelva a intentar 'npm run dev'.
============================================================ Autor: Martin Araya - Francisco Villagran - Romina Mondaca
