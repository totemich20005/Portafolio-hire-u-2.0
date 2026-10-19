# 🧡 HIRE-U | Conectando talento con oportunidades

**HIRE-U** es una plataforma web orientada a conectar a los egresados de la Universidad de San Buenaventura con empresas y oportunidades laborales, facilitando el acercamiento entre el talento profesional y el mercado de trabajo.

El proyecto nace como una iniciativa académica de Ingeniería de Sistemas y busca ofrecer un espacio digital donde los egresados puedan fortalecer su perfil profesional y conocer oportunidades acordes con su formación, mientras las empresas encuentran talento preparado para afrontar nuevos retos.

> **Nuestro propósito:** transformar el talento de nuestros egresados en nuevas oportunidades profesionales.

---

## 📌 Tabla de contenido

- [Acerca del proyecto](#-acerca-del-proyecto)
- [Objetivos](#-objetivos)
- [Características principales](#-características-principales)
- [Tecnologías utilizadas](#-tecnologías-utilizadas)
- [Arquitectura del proyecto](#-arquitectura-del-proyecto)
- [Base de datos](#-base-de-datos)
- [Metodología de desarrollo](#-metodología-de-desarrollo)
- [Instalación y ejecución](#-instalación-y-ejecución)
- [Equipo de desarrollo](#-equipo-de-desarrollo)
- [Estado del proyecto](#-estado-del-proyecto)
- [Contribuciones](#-contribuciones)

## 🚀 Acerca del proyecto

HIRE-U es una propuesta de red profesional y empleabilidad inspirada en plataformas como LinkedIn, pero enfocada en las necesidades de la comunidad de egresados de la Universidad de San Buenaventura.

La plataforma busca centralizar información profesional y oportunidades laborales en un mismo entorno digital, promoviendo la conexión entre egresados y empresas.

El proyecto contempla el desarrollo de una interfaz intuitiva, una estructura de información organizada y una base de datos que permita gestionar los datos necesarios para el funcionamiento de la solución.

## 🎯 Objetivos

### Objetivo general

Desarrollar una plataforma web que facilite la conexión entre los egresados de la Universidad de San Buenaventura y las empresas, promoviendo la empleabilidad y el desarrollo profesional mediante herramientas digitales.

### Objetivos específicos

- Facilitar la consulta de oportunidades laborales.
- Permitir la organización de la información académica y profesional de los egresados.
- Proporcionar un espacio para que las empresas gestionen su información y sus ofertas laborales.
- Diseñar una interfaz intuitiva, moderna y adaptable a diferentes dispositivos.
- Organizar y administrar la información mediante una base de datos relacional.
- Aplicar buenas prácticas de desarrollo de software y gestión de proyectos.

## ✨ Características principales

### 👨‍🎓 Perfiles profesionales

Estructura orientada a registrar la información personal, académica y profesional de los egresados, incluyendo su formación y experiencia laboral.

### 🏢 Gestión de empresas

Organización de la información de las empresas, sus datos de contacto y su actividad dentro de la plataforma.

### 💼 Ofertas laborales

Gestión de información relacionada con las oportunidades de empleo que pueden ser consultadas por los egresados.

### 📝 Postulaciones

Estructura de datos para relacionar a los egresados con las ofertas laborales de su interés.

### 🔐 Interfaz de acceso y registro

Diseño de pantallas para el acceso y registro de usuarios, junto con una navegación orientada a facilitar el uso de la plataforma.

### 📱 Diseño adaptable

Interfaz web diseñada con herramientas de desarrollo frontend para ofrecer una experiencia organizada en diferentes tamaños de pantalla.

*Nota: estas características representan el alcance funcional planteado para HIRE-U. Su disponibilidad efectiva depende de la implementación de cada módulo.*

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso en el proyecto |
|---|---|
| HTML5 | Estructura de las páginas web. |
| CSS3 | Estilos, identidad visual y diseño de interfaces. |
| JavaScript | Interactividad y comportamiento del frontend. |
| Bootstrap 5.3.3 | Componentes y diseño adaptable. |
| Bootstrap Icons | Iconografía de la interfaz. |
| Animate.css | Animaciones visuales. |
| MySQL | Gestión y almacenamiento de información relacional. |
| MySQL Workbench 8.0 | Diseño y administración de la base de datos. |
| Java | Desarrollo de formularios de escritorio y conexión con la base de datos en los componentes trabajados. |
| Apache NetBeans | Entorno de desarrollo para los componentes Java. |
| Git y GitHub | Control de versiones y alojamiento del repositorio. |
| GitHub Pages | Publicación de la versión web estática. |

**Importante:** la inclusión de una tecnología en esta lista no significa que todos los componentes estén integrados actualmente en producción. La integración debe verificarse en el código y la configuración del proyecto.

## 🏗️ Arquitectura del proyecto

HIRE-U se plantea mediante una separación por capas, con el objetivo de organizar sus componentes y facilitar el mantenimiento y la evolución del sistema.

1. **Capa de presentación:** interfaz visual, páginas web, formularios y navegación del usuario.
2. **Capa de lógica de negocio:** validaciones, reglas del sistema y procesamiento de las operaciones.
3. **Capa de acceso a datos:** consultas y operaciones de lectura, inserción, actualización y eliminación.
4. **Capa de persistencia:** base de datos MySQL, encargada de almacenar la información estructurada.

Esta organización permite identificar las responsabilidades de cada componente y facilita la incorporación progresiva de nuevas funcionalidades.

## 🗄️ Base de datos

La base de datos del proyecto se denomina `Hireu` y contempla entidades para organizar la información relacionada con los usuarios, las empresas y las oportunidades laborales.

Entre las tablas trabajadas se encuentran:

| Tabla | Propósito |
|---|---|
| `Empresa` | Información de las empresas registradas. |
| `Egresado` | Datos personales y profesionales de los egresados. |
| `OfertaLaboral` | Información de las ofertas de empleo. |
| `Postulacion` | Relación entre egresados y ofertas laborales. |
| `Experiencia` | Información de experiencia profesional. |
| `Estudios` | Información de formación académica. |
| `Auditoria` | Registro de operaciones y eventos auditados. |

El diseño contempla operaciones CRUD (crear, consultar, actualizar y eliminar) mediante procedimientos almacenados, así como el uso de disparadores (*triggers*) para registrar determinados eventos en la tabla de auditoría.

La estructura definitiva, las relaciones y las restricciones deben consultarse en el script SQL del proyecto.

## 🔄 Metodología de desarrollo

Para organizar el desarrollo académico de HIRE-U se trabaja con principios de metodologías ágiles y el marco de trabajo **Scrum**.

Sus elementos de trabajo incluyen:

- **Product Owner:** priorización de los requisitos y definición del valor del producto.
- **Scrum Master:** acompañamiento al proceso Scrum y apoyo para resolver impedimentos.
- **Development Team:** diseño, programación, pruebas y construcción de los incrementos.
- **Product Backlog:** lista priorizada de funcionalidades e historias de usuario.
- **Sprint Backlog:** tareas e historias seleccionadas para cada sprint.
- **Sprint Review:** revisión del incremento desarrollado.
- **Sprint Retrospective:** identificación de mejoras para el siguiente ciclo.

El objetivo es desarrollar el producto de manera incremental, revisar los avances y adaptar las funcionalidades según los requisitos del proyecto.

## 💻 Instalación y ejecución

### 1. Clonar el repositorio

Abre una terminal y ejecuta:

```bash
git clone https://github.com/totemich20005/Portafolio-hire-u-2.0.git
```

### 2. Ingresar a la carpeta

```bash
cd Portafolio-hire-u-2.0
```

### 3. Abrir el proyecto

Abre la carpeta en Visual Studio Code o en tu editor de código preferido.

Verifica que el archivo principal de la página sea `index.html` y que las rutas a los archivos CSS, JavaScript, imágenes y logotipo correspondan con la estructura real del repositorio.

### 4. Ejecutar la versión web

Abre `index.html` en un navegador o utiliza una extensión de servidor local, como Live Server, en Visual Studio Code.

Si el proyecto requiere servicios de backend o conexión con MySQL, estos deben configurarse por separado. GitHub Pages permite publicar contenido web estático, pero no ejecuta directamente una aplicación Java conectada a MySQL ni un servidor backend.

### 5. Configurar GitHub Pages

Para publicar la versión web estática:

1. Ingresa al repositorio en GitHub.
2. Abre **Settings**.
3. Selecciona **Pages**.
4. Configura la fuente de publicación y la rama correspondiente.
5. Selecciona la carpeta que contiene `index.html`.
6. Guarda los cambios y espera a que termine la publicación.

Verifica que `index.html` esté ubicado en la raíz de la carpeta publicada o en la ubicación configurada para GitHub Pages.

## 👥 Equipo de desarrollo

Proyecto integrador académico de Ingeniería de Sistemas.

- **Andrés Quintero**
- **Andrés Cardozo**
- **Andrés Martinez**
- **Sebastian Rodriguez**

El equipo participa en las actividades de análisis, diseño, desarrollo y documentación del proyecto, de acuerdo con la distribución de responsabilidades establecida.

## 📈 Estado del proyecto

**Etapa:** desarrollo académico e implementación progresiva.

HIRE-U se encuentra en proceso de construcción y mejora. El proyecto contempla el diseño de la interfaz web, la organización de los requisitos, la estructuración de la base de datos y el desarrollo gradual de funcionalidades.

Las funcionalidades disponibles deben validarse con la versión actual del código antes de considerarse terminadas o listas para producción.

### Próximas mejoras

- Completar e integrar los módulos funcionales.
- Fortalecer las validaciones de formularios.
- Integrar de forma segura el frontend con el backend y la base de datos.
- Implementar autenticación y control de acceso.
- Desarrollar pruebas funcionales y de integración.
- Mejorar la documentación técnica y el manual de usuario.
- Evaluar accesibilidad, seguridad y rendimiento.

## 🤝 Contribuciones

Las mejoras y propuestas para HIRE-U pueden organizarse mediante ramas de Git, commits descriptivos y solicitudes de cambio (*pull requests*).

Flujo recomendado:

1. Crear una rama para la funcionalidad o corrección.
2. Realizar los cambios necesarios.
3. Probar el comportamiento de los componentes modificados.
4. Registrar los cambios con un mensaje descriptivo.
5. Revisar e integrar los cambios en la rama principal.

## 📄 Licencia

Proyecto de carácter académico. La licencia de distribución debe definirse explícitamente antes de autorizar su reutilización o redistribución.

---

**HIRE-U — El siguiente paso en tu vida profesional empieza aquí.** 🧡
