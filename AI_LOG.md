## Uso de IA

Utilicé IA para determinar la manera de manejarme con PostgreSQL, ya que era la tecnología en la que menos experiencia tenía. Luego la usé en general para armar el código: comencé con prompts para generar la base y después fui paso a paso según mi criterio.

- Prompts generales:

> tengo que trabajar con postgres en go, qué clientes existen, cuál me conviene y por qué?

> como hago para trabajar con las queries SQL de la mejor manera? existen herramientas para eso?

> necesito hacer un docker compose que cree una imagen con postgres y utilice dos más para frontend y backend que están en repos de git separados y públicos, cómo podría hacer?

- Prompts backend:

> inicializá un proyecto en go con el nombre "nw-back", instalá chi para ruteo, pgx como cliente postgres, gofakeit para generar datos mockeados, y godotenv para leer archivos .env

> organiza la estructura de carpetas con cmd, internal, vamos a tener dos puntos de entrada, /api para la api rest, y /seed para la generación de información fake

- Prompts frontend:

> inicializa un proyecto con vite con el nombre "nw-front", usemos react, TS, tailwind, react router, instala también mantine, crea la carpeta pages con un archivo donde estén todas las rutas

Luego le fui pasando los endpoints del back, con los formatos de respuesta para cada caso.

> genera la página /customers, pegale a ... en el back, vas a recibir esta respuesta (tipos del código de go), genera una tabla con esos datos con las columnas ...
