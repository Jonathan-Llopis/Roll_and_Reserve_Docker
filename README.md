# 🎲 Roll & Reserve  
**Plataforma de Reservas para Juegos de Mesa**  

Este repositorio contiene **Roll & Reserve**, una aplicación multiplataforma desarrollada como **proyecto final** del ciclo superior de **Desarrollo de Aplicaciones Multiplataforma (DAM)**. El objetivo es facilitar la gestión y reserva de mesas en locales de juegos de mesa, optimizando la experiencia tanto para usuarios como para propietarios de tiendas.

---

## 📄 Descripción General  
**Roll & Reserve** permite a los usuarios buscar, filtrar y reservar mesas según juegos específicos, horarios y plazas disponibles. Los propietarios pueden gestionar las mesas, añadir juegos y consultar estadísticas para mejorar sus servicios.
**Referencias:**
- [**Roll_and_Reserve_Bgg-Api**](https://github.com/Jonathan-Llopis/bgg-api/tree/28c7c111297c83dded0661907fb4b5231686b589): Repositorio utilizado para la integración de la API de BGG. [bgg-api](https://github.com/tnaskali/bgg-api) por [Thomas Naskali](https://github.com/tnaskali).
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

**Roll & Reserve** no solo simplifica la gestión de reservas, sino que fortalece la comunidad de jugadores de mesa, facilitando encuentros y promoviendo experiencias únicas.  
¡Gracias por visitar este repositorio! 😊

## Términos de Uso de la API XML de BoardGameGeek

Tu acceso a la API XML proporcionada por BoardGameGeek, LLC ("BGG") y tu uso de los datos proporcionados por BGG_XML_API y BGG_XML_API2, está sujeto a los Términos de Servicio generalmente aplicables a todas las características de BGG, que están disponibles en [términos](http://www.boardgamegeek.com/terms) y se incorporan aquí por referencia ("TOS"), y cualquier modificación a los mismos. Las palabras con mayúscula inicial utilizadas aquí sin definición tendrán el significado que se les atribuye en los TOS.

Además, debido a las características particulares de la API XML de BGG, al acceder y utilizar la información de la API XML de BGG, aceptas estar sujeto a los siguientes términos adicionales.

BGG te otorga una licencia mundial, no exclusiva y libre de regalías para reproducir y mostrar los datos disponibles a través de la API XML de BGG, incluidos los Envíos de Usuarios, únicamente para fines estrictamente no comerciales y únicamente según lo permitido por la API XML proporcionada por BGG. BGG tendrá el derecho de terminar esta licencia en cualquier momento y por cualquier motivo a su sola discreción.

El uso de la API XML, o de cualquiera de los datos en el sitio, para entrenar un sistema de IA (Inteligencia Artificial) o un modelo de lenguaje grande (LLM) está estrictamente prohibido.

Si deseas licenciar la API XML para uso comercial, por favor contacta a Daniel Karp.

No puedes modificar los datos, incluidos los Envíos de Usuarios, obtenidos a través de la API XML de BGG de ninguna manera. En todos los usos de la API XML de BGG, debes acreditar a BoardGameGeek por nombre como la fuente de los datos. Te pedimos que incluyas el siguiente logo (vinculado a BoardGameGeek) en los usos públicos de la API XML:

Usuario: dakarp

Reconoces que BGG puede cambiar la API XML de vez en cuando. Estos cambios pueden requerir que actualices tu implementación para asegurar el funcionamiento adecuado. Tu uso de la API XML de BGG no debe interferir con el funcionamiento normal de los servidores de BGG y reconoces que BGG puede monitorear la actividad de la API XML.

BGG se reserva el derecho de modificar estos términos en cualquier momento publicándolos en esta página.

Los textos disponibles a través de la API XML de BGG con la fuente designada como Wikipedia están disponibles para ti bajo la licencia de Creative Commons Attribution-NonCommercial-ShareAlike, disponible en http://creativecommons.org/licenses/by-nc-sa/3.0/ ![BoardGameGeek Logo](https://cf.geekdo-images.com/HZy35cmzmmyV9BarSuk6ug__thumb/img/gbE7sulIurZE_Tx8EQJXnZSKI6w=/fit-in/200x150/filters:strip_icc()/pic7779581.png)

...
