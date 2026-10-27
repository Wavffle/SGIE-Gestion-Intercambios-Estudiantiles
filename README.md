<p align="center">
  <img src="src/main/resources/Logo%20SGIE.png" alt="Logo SGIE" width="250"/>
</p>

<p align="center">
  Aplicación de escritorio para la gestión de programas de intercambio estudiantil, convenios internacionales y postulaciones académicas.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Java%20Swing-UI-4479A1?style=for-the-badge" alt="Java Swing"/>
  <img src="https://img.shields.io/badge/FlatLaf-Dark%20Theme-6C63FF?style=for-the-badge" alt="FlatLaf"/>
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
</p>

---

## Sobre el proyecto

**SGIE** es un sistema de información desarrollado en Java para facilitar la administración de programas de intercambio estudiantil. La aplicación centraliza la gestión de usuarios, convenios internacionales y postulaciones, ofreciendo funcionalidades diferenciadas según el rol de cada usuario.

El proyecto utiliza una interfaz gráfica de escritorio con Java Swing y FlatLaf, junto con persistencia de datos mediante SQLite.

## Funcionalidades principales

- **Gestión de usuarios:** acceso al sistema según el rol asignado.
- **Convenios internacionales:** consulta, creación, edición y administración de convenios.
- **Postulaciones:** creación y seguimiento de solicitudes de intercambio estudiantil.
- **Gestión por roles:** funcionalidades específicas para estudiantes, funcionarios y auditores.
- **Seguimiento de solicitudes:** consulta de estados, comentarios e interacciones asociadas a las postulaciones.
- **Persistencia de datos:** almacenamiento local mediante SQLite.
- **Exportación de información:** generación de reportes en formato CSV.
- **Interfaz gráfica:** diseño de escritorio con Java Swing y tema oscuro mediante FlatLaf.

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| Java | Lenguaje de programación |
| Java Swing | Interfaz gráfica de usuario |
| FlatLaf | Personalización visual de la interfaz |
| SQLite | Persistencia de datos |
| OpenCSV | Exportación de información a CSV |
| Git y GitHub | Control de versiones y alojamiento del proyecto |

## Arquitectura y conceptos aplicados

El desarrollo aplica conceptos de programación orientada a objetos y organización del código mediante gestores y clases especializadas.

- **Herencia y polimorfismo:** modelado de distintos tipos de usuarios.
- **Encapsulamiento:** organización y protección del estado de los objetos.
- **Enumeraciones:** representación de estados y categorías del sistema.
- **Excepciones personalizadas:** manejo de errores asociados a reglas de negocio.
- **Persistencia de datos:** interacción con una base de datos SQLite.
- **Separación de responsabilidades:** organización de la interfaz gráfica y la lógica de gestión.

## Ejecución del proyecto

### Requisitos previos

- JDK de Java compatible con el código fuente.
- Un IDE compatible con Java, como IntelliJ IDEA, Eclipse o Visual Studio Code con soporte para Java.
- Las dependencias del proyecto correctamente configuradas.

### Ejecutar desde un IDE

1. Clona o descarga este repositorio y abrelo en tu IDE.
2. Comprueba que las dependencias necesarias estén disponibles, incluyendo FlatLaf, el controlador JDBC de SQLite y OpenCSV.
3. Localiza el archivo de entrada:

   `src/main/java/Main.java`

4. Ejecuta el método `main()` de la clase `Main`.

## Credenciales de demostración

El proyecto incluye usuarios de prueba para acceder a las distintas funcionalidades.

| Rol | RUT | Contraseña |
|---|---|---|
| Auditor | `100000003` | `123a` |
| Estudiante | `111111111` | `123` |
| Funcionario | `100000001` | `123f` |

## Contexto académico

Proyecto desarrollado para la asignatura **INF2236 — Programación Avanzada**, como parte de la implementación de un sistema de información orientado a la gestión de programas de intercambio estudiantil.

### Integrantes

- Annais Paulette Legua Flores
- Benjamin Antonio Brito Veloso
- Iván Moisés Ferreira León

---

<p align="center">
  <sub>SGIE · Sistema de Gestión de Intercambios Estudiantiles</sub>
</p>