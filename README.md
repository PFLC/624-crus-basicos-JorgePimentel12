
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.
APORTACION

Escalabilidad
Comenta sobre cómo la aplicación podría escalarse para manejar un mayor volumen de usuarios o datos. ¿Qué consideraciones de diseño podrían hacerse para mejorar la escalabilidad?

Internacionalización y Localización
Si la aplicación está destinada a un público global, podrías discutir la implementación de soporte para múltiples idiomas y regiones.

Pruebas
Menciona la importancia de las pruebas en el desarrollo de software y sugiere algunas estrategias para probar la aplicación, como pruebas unitarias, pruebas de integración y pruebas de aceptación.

Seguridad Adicional
Además de la nota de seguridad existente, podrías agregar información sobre cómo implementar medidas adicionales de seguridad, como autenticación de dos factores, cifrado de contraseñas y protección contra ataques de fuerza bruta.

Optimización de Rendimiento
Si es relevante para tu aplicación, podrías discutir estrategias para optimizar el rendimiento, como la optimización de consultas SQL, el uso de almacenamiento en caché y la compresión de recursos estáticos.

Mantenimiento y Actualizaciones
Habla sobre la importancia del mantenimiento continuo de la aplicación
![image](https://github.com/PFLC/624-crus-basicos-JorgePimentel12/assets/114130129/9f51a82f-ce4b-4fb8-b06b-812d5464be7e)

