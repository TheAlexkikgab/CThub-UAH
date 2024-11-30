# CThub-UAH
Proyecto con el Framework DjangoRest para el Club de Crecimiento Técnológico de la UAH
___
# Proyecto: Plataforma del Club de Crecimiento Tecnológico

El Club de Crecimiento Tecnológico busca fomentar el aprendizaje y la colaboración en el ámbito tecnológico. Este proyecto tiene como objetivo desarrollar una plataforma web que permita a los usuarios acceder a contenido exclusivo del club, como cursos, dinámicas y actividades, además de mantenerlos informados con una sección de noticias. La plataforma estará diseñada con tecnologías modernas como Django, Django REST Framework y React, ofreciendo una experiencia interactiva y funcional.
___
# Objetivos del Proyecto
## Objetivo General
Desarrollar una plataforma web para centralizar la gestión de contenidos, actividades y noticias del Club de Crecimiento Tecnológico.

## Objetivos Específicos:
Permitir el registro e inicio de sesión de usuarios (miembros del club).
Gestionar contenido educativo, como cursos y actividades, de forma organizada.
Facilitar la entrega y revisión de tareas o dinámicas asignadas por los administradores del club.
Incorporar una sección de noticias para anunciar eventos, nuevas dinámicas y actualizaciones del club.
Proveer una experiencia de usuario moderna e intuitiva con interfaces responsivas.
___
# Características del Proyecto
Autenticación de Usuarios:

Registro, inicio de sesión y recuperación de contraseñas.
Roles de usuario (Administrador, Usuario Miembro).
Gestión de Cursos y Actividades:

Los administradores podrán crear y gestionar cursos y actividades.
Los usuarios podrán visualizar contenido asociado a los cursos en los que estén inscritos.
Entrega de Tareas:

Sistema para que los usuarios puedan subir archivos o completar actividades asignadas.
Los administradores podrán revisar y calificar las entregas.
Sección de Noticias:

Publicación de artículos relacionados con el club.
Visualización de noticias en formato de lista o detalle.
Interfaz de Usuario (Frontend):

Navegación intuitiva y diseño atractivo con React.
Compatibilidad con dispositivos móviles y navegadores modernos.
Backend (API):

Django REST Framework para gestionar las funcionalidades del sistema.
API RESTful para comunicación eficiente con el frontend.
___
# Estructura del Proyecto
Frontend (React):

Librerías principales: React, React Router, Axios.
Estilo: CSS o frameworks como TailwindCSS o Bootstrap.
Funcionalidades: Registro e inicio de sesión, vista de cursos, noticias y actividades.
Backend (Django + DRF):

Django REST Framework para la creación de endpoints.
Base de datos: PostgreSQL.
Gestión de usuarios y autenticación con tokens (JWT).
Base de Datos:

Tablas principales:
Usuarios
Cursos
Actividades
Entregas
Noticias

# Metodología de Desarrollo
Fase de Diseño:

Recolección de requisitos y diseño de la arquitectura del sistema.
Bocetos o wireframes de las pantallas principales.
Fase de Desarrollo:

Semana 1: Configuración inicial del backend y frontend, implementación del sistema de autenticación.
Semana 2: Desarrollo de los módulos de cursos y actividades.
Semana 3: Implementación de la sección de noticias.
Semana 4: Integración de frontend y backend, pruebas iniciales.
Fase de Pruebas:

Pruebas de funcionalidad, rendimiento y corrección de errores.
Validación con miembros del club.
Fase de Despliegue:

Configuración en un servidor de producción (Heroku, AWS, etc.).
Publicación y entrega al club.
___
# Recursos Necesarios
Herramientas de Desarrollo:

Editor de código (VS Code).
GitHub para control de versiones y colaboración.
Equipo de Trabajo:

Backend Developer(s): Configuración del servidor y creación de endpoints.
Frontend Developer(s): Diseño e implementación de la interfaz de usuario.
QA Tester(s): Pruebas del sistema.
Infraestructura:

Base de datos PostgreSQL (local durante el desarrollo, remota en producción).
Servicio de hosting para el despliegue (Heroku o similares).
___
# Roles en el Equipo
Project Manager: Supervisión general y planificación de tareas.
Backend Developer: Implementación de funcionalidades en Django y DRF.
Frontend Developer: Diseño e interacción en React.
Tester: Validación de las funcionalidades y experiencia de usuario.
___
Este proyecto no solo permitirá gestionar eficientemente el contenido del club, sino que también servirá como una oportunidad de aprendizaje y práctica en tecnologías modernas como Django, Django REST Framework y React. La colaboración entre los miembros del equipo será clave para garantizar el éxito del proyecto.
