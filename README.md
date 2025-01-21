# 📚 Proyecto Librería

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📝 Descripción

Este proyecto es un cliente para invocar la **API RESTful** 'https://gutendex.com/books' diseñada para consultar libros. Incluye funcionalidades para:

- 📖 **Gestión de libros**: registro de libros y consulta por varios parámetros.
- ✍️ **Gestión de autores**: registro y consulta de autores.
- 🗂️ **Estadísticas**: Top 10 libros más descargados.

---

## ⚙️ Tecnologías Utilizadas

- **JDK 17**: Lenguaje de programación java.
- **Spring Boot**: Framework para el desarrollo de aplicaciones basadas en Java.
- **Gradle**: Herramienta para la gestión de dependencias y construcción del proyecto.
- **PostgreSQL**: Base de datos relacional para el almacenamiento de datos de libros y autores.
- **GitHub**: Repositorio para el control de versiones y colaboración.

---

## 🚀 Funcionalidades

### 🌟 Funcionalidades implementadas:
- Consulta por título
- Consultar todos los libros.
- Consultar todos los autores.
- Consulta de autores vivos en un determinado año.
- Consulta Libro en un determinado idioma.
- Consulta Autor por nombre.
- Consulta Autores por año de nacimiento.
- Consulta Autores por año de fallecimiento
- Insertar Libro.
- Top 10 libros más descargados.

---

### 📂 Estructura del proyecto
```
src/
├── main/
│   ├── java/valverde/com/mx/literalura/
│   │   ├── util/          # Clase de utilería
│   │   ├── models/        # Entidades JPA
│   │   ├── repositories/  # Interfaces de acceso a datos
│   │   ├── services/      # Lógica de negocio
│   └── resources/
│       ├── application.properties  # Configuración de Spring
├── test/  # Pruebas unitarias e integración
```

## 📖 Opciones al ejecutar el programa
### Menú Principal
![Menu principal](assets/menu.png)

### Submenú
![Submenu](assets/submenu.png)

---
### 💻 Desarrollado por:
- Nombre: Oriana Belen Aguilar
- Email: orianaaguilar28@gmail.com
- LinkedIn: https://www.linkedin.com/in/oriana-aguilar-805205256/

