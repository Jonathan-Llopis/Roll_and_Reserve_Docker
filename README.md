# 🎲 Roll & Reserve  
**Plataforma de Reservas para Juegos de Mesa**  

Este repositorio contiene **Roll & Reserve**, una aplicación multiplataforma desarrollada como **proyecto final** del ciclo superior de **Desarrollo de Aplicaciones Multiplataforma (DAM)**. El objetivo es facilitar la gestión y reserva de mesas en locales de juegos de mesa, optimizando la experiencia tanto para usuarios como para propietarios de tiendas.

---

## 📄 Descripción General  
**Roll & Reserve** permite a los usuarios buscar, filtrar y reservar mesas según juegos específicos, horarios y plazas disponibles. Los propietarios pueden gestionar las mesas, añadir juegos y consultar estadísticas para mejorar sus servicios.
**Referencias:**
- [**Roll_and_Reserve_Bgg-Api**](https://github.com/Jonathan-Llopis/bgg-api/tree/28c7c111297c83dded0661907fb4b5231686b589): Repositorio utilizado para la integración de la API de BGG. [bgg-api](https://github.com/tnaskali/bgg-api) por [Thomas Naskali](https://github.com/tnaskali).
- [**BoardGameGeek**](https://boardgamegeek.com/): Utilizamos la base de datos de BoardGameGeek para realizar consultas, siendo esta la fuente de nuestros datos. Se aplican los términos de uso descritos en esta sección [Bgg Terms of Use](https://boardgamegeek.com/wiki/page/XML_API_Terms_of_Use#).
 
[![BoardGameGeek Logo](https://cf.geekdo-images.com/HZy35cmzmmyV9BarSuk6ug__thumb/img/gbE7sulIurZE_Tx8EQJXnZSKI6w=/fit-in/200x150/filters:strip_icc()/pic7779581.png)](https://boardgamegeek.com/)

---

## 🚀 Funcionalidades Principales  

### Usuario General  
1. **Pantalla de Login**  
   - Acceso seguro con validación de credenciales y recuperación de contraseña.  
2. **Pantalla de Registro**  
   - Creación de cuenta con nombre, correo, contraseña y avatar.  
3. **Pantalla Principal**  
   - Visualización de tiendas disponibles con filtros (horarios, juegos, ubicación).  
4. **Pantalla de Mesas**  
   - Consulta del estado de las mesas (libres, completas) y detalles del juego.  
5. **Pantalla de Reservas**  
   - Personalización de reservas: horarios, tipo de juego y cantidad de jugadores.  
6. **Valoraciones y Perfiles**  
   - Reseñas y puntuaciones para locales, juegos y usuarios.  

### Propietario de Local  
1. **Gestión de Mesas**  
   - Añadir, modificar y eliminar mesas en tiempo real.  
2. **Gestión de Juegos**  
   - Agregar nuevos juegos con detalles como dificultad, materiales y descripción.  
3. **Estadísticas y Análisis** *(Funcionalidad futura)*  
   - Consulta de mesas más populares, horarios pico y tendencias de uso.  

---

## 🛠️ Apartado Técnico  

- **Frontend:** Desarrollado con **Flutter** para garantizar compatibilidad multiplataforma (Android e iOS).  
- **Backend:** Implementado con **NestJS** y una base de datos **MariaDB** mediante **TypeORM**.  
- **Notificaciones:** Integración con **Firebase Cloud Messaging** para alertas en tiempo real.  
- **Control de Versiones:** Git y GitHub para la gestión del código.  

---

## 🎯 Metodología de Desarrollo  
Se ha seguido un enfoque **Agile/Scrum**, con las siguientes fases:  

1. **Planificación y Diseño Inicial:** Requisitos, wireframes y entorno técnico.  
2. **Desarrollo Backend:** APIs RESTful seguras con JWT y gestión de reservas.  
3. **Desarrollo Frontend:** Interfaz responsiva y comunicación con el backend.  
4. **Implementación de Funcionalidades Clave:** Gestión de usuarios, reservas y valoraciones.  
5. **Pruebas y Optimización:** Validación funcional y corrección de errores.  
6. **Documentación Final:** Manual técnico y guía de usuario.  

---

## 📆 Calendario de Trabajo  
| Fase                      | Duración           | Descripción                                     |  
|---------------------------|--------------------|------------------------------------------------|  
| **Planificación**         | 1-2 semanas       | Diseño inicial y requisitos.                   |  
| **Backend**               | 4 semanas         | Desarrollo de API y base de datos.             |  
| **Frontend**              | 5 semanas         | Implementación de interfaz de usuario.         |  
| **Gestión de Funcionalidades** | 4 semanas   | Valoraciones y panel de administración.        |  
| **Pruebas y Depuración**  | 6 semanas         | Optimización del rendimiento y pruebas finales.|  

---

## 🌟 Posibles Mejoras Futuras  
1. **Chat en Tiempo Real:** Comunicación entre jugadores para coordinar partidas.  
2. **Sistema de Invitaciones:** Invitar a amigos o contactos a mesas específicas.  
3. **Recomendaciones Personalizadas:** Sugerencias basadas en el historial del usuario.  
4. **Sistema de Eventos:** Organización de torneos y eventos temáticos.  
5. **Análisis Avanzado para Locales:** Dashboards interactivos y comparativas de rendimiento.  

---

## 👨‍🎓 Autor  
- **Jonathan Llopis Linares**  
- **Ciclo Formativo:** Desarrollo de Aplicaciones Multiplataforma (DAM)  
- **Centro Educativo:** IES L'Estacio (Ontinyent)

---

## 📚 Documentación  
La documentación del proyecto incluye:  
- **Manual de Usuario:** Guía completa para el uso de la aplicación.  
- **Manual Técnico:** Descripción de la arquitectura y funcionamiento del código.  
- **Informe Final:** Proceso de desarrollo, retos enfrentados y soluciones aplicadas.  

---

## 🤝 Contacto  
Si deseas colaborar o tienes alguna sugerencia, no dudes en ponerte en contacto:  
- **Email**: jonathan.llopis.linares@gmail.com
- **LinkedIn**:[ linkedin.com/in/jonathanllopislinares/](https://www.linkedin.com/in/jonathanllopislinares/)

---

## 🛠️ Configuración del Entorno de Desarrollo

### Prerrequisitos
- **Node.js** (versión 14 o superior)
- **Flutter** (versión 2.0 o superior)
- **Docker** y **Docker Compose**
- **MariaDB** (opcional si no se usa Docker)

### Pasos de Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/Jonathan-Llopis/Roll_and_Reserve_Docker.git
   cd Roll_and_Reserve_Docker
   ```

2. Instala las dependencias del backend:
   ```bash
   cd Roll_and_Reserve_DataBase
   npm install
   ```

3. Instala las dependencias del frontend:
   ```bash
   cd ../Roll_and_Reserve_App
   flutter pub get
   ```

4. Configura las variables de entorno:
   Crea un archivo `.env` en la raíz del proyecto y añade las siguientes variables:
   ```env
   WEB_SERVER_PORT=8080
   MYSQL_ROOT_PASSWORD=my-secret-pw
   MYSQL_DATABASE=nombre_de_la_base_de_datos
   MYSQL_USER=usuario_de_la_base_de_datos
   MYSQL_PASSWORD=contraseña_del_usuario
   MAIL_USER=mailUser
   MAIL_CLIENT_ID=Nothing
   MAIL_PASSWORD=passwordEmail
   ENABLE_TOKEN_VALIDATION=false
   MONGODB_URI=mongodb://admin:password@mongodb:27017
   MONGO_INITDB_ROOT_USERNAME=admin
   MONGO_INITDB_ROOT_PASSWORD=password
   ```

---

## 🐳 Ejecución de la Aplicación con Docker

### Comandos
1. Construye y levanta los contenedores:
   ```bash
   docker-compose up --build
   ```

2. Detén y elimina los contenedores:
   ```bash
   docker-compose down
   ```

### Variables de Entorno
Asegúrate de que las variables de entorno en el archivo `.env` están correctamente configuradas antes de ejecutar los comandos de Docker.

---

## 🌟 Cómo Contribuir

### Directrices para Pull Requests
1. **Fork** el repositorio y clona tu fork.
2. Crea una nueva rama para tu contribución:
   ```bash
   git checkout -b nombre-de-tu-rama
   ```
3. Realiza tus cambios y haz commit:
   ```bash
   git commit -m "Descripción de tus cambios"
   ```
4. Sube tus cambios a tu fork:
   ```bash
   git push origin nombre-de-tu-rama
   ```
5. Abre un **Pull Request** en el repositorio original.

### Estilo de Código
- Sigue las convenciones de estilo de código de **JavaScript** y **Dart**.
- Asegúrate de que tu código pasa todas las pruebas antes de enviar un pull request.

---

## 🐞 Reporte de Problemas y Solicitud de Funcionalidades

### Reporte de Problemas
Si encuentras algún problema, por favor repórtalo en el [issue tracker](https://github.com/Jonathan-Llopis/Roll_and_Reserve_Docker/issues).

### Solicitud de Funcionalidades
Si tienes alguna idea para una nueva funcionalidad, por favor crea un nuevo issue en el [issue tracker](https://github.com/Jonathan-Llopis/Roll_and_Reserve_Docker/issues) y describe tu propuesta en detalle.

---

## 📦 APK
Puedes descargar la última versión de la aplicación en formato APK desde el siguiente enlace:
[Descargar APK]([https://example.com/download/apk](https://drive.google.com/file/d/1oPt2QN-iVxijRUg30dLzihGOqhbV_RT1/view?usp=drive_link))

---

## 🌐 Enlace a la Aplicación
Puedes acceder a la aplicación en modo navegador desde el siguiente enlace:
[Acceder a la Aplicación](https://example.com/app)

---

## 📄 Presentación en PDF
Puedes descargar la presentación del proyecto en formato PDF desde el siguiente enlace:
[Descargar Presentación](https://example.com/download/presentation.pdf)

---

## 📚 Bibliografía Utilizada
- Manuales de Flutter y Dart.
- Documentación oficial de NestJS.
- Tutoriales de Firebase Cloud Messaging.
- Artículos y guías sobre MariaDB y TypeORM.
- Documentación de la API de BoardGameGeek.
