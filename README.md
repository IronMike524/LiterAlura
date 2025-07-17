# LiterAlura 📚

¡Bienvenido a LiterAlura!  
Este proyecto es un pequeño catálogo de libros de dominio público usando la [API de Gutendex](https://gutendex.com/) y Java Spring Boot.

## ¿Qué puedes hacer?

- Buscar libros por título y ver su información.
- Guardar tu historial de libros consultados durante la sesión.
- Ver el Top 10 de los libros más descargados (según lo que buscaste en esa ejecución).
- Buscar autores por nombre, año de nacimiento o fallecimiento.
- Consultar estadísticas de descargas de tus libros buscados.

## ¿Cómo funciona?

El menú es interactivo por consola. Solo ejecuta la app y sigue las instrucciones.  
Puedes buscar títulos clásicos (“quijote”, “hamlet”, “alice in wonderland”, etc.) y probar todas las opciones del menú.  
Los resultados y búsquedas se mantienen solo mientras la app está abierta.

## ¿Tecnologías usadas?

- Java 17
- Spring Boot 3.2+
- Maven
- Jackson (para leer JSON)
- PostgreSQL (preparado para la versión con base de datos)
- API Gutendex (no requiere autenticación)

## ¿Cómo lo ejecuto?

1. Clona el repositorio.
2. Configura tu base de datos local si quieres persistencia (opcional, solo para la versión avanzada).
3. Ejecuta la aplicación desde IntelliJ o desde la terminal con:
