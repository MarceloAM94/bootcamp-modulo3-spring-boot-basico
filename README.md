# 🚀 Módulo 3 – Spring Boot: Desarrollo Web con Java

Este repositorio contiene ejercicios, notas, proyectos y configuraciones realizados durante el **Módulo 3** del bootcamp **Desarrollo Web Fullstack con Java** (CodiGo). En este módulo aprendemos a construir aplicaciones web con **Spring Boot**, utilizando una arquitectura limpia y conectando con bases de datos.

---

## 📚 Contenido del módulo

### 🔸 Introducción a Spring Boot

- ¿Qué es Spring Boot?
- Estructura de un proyecto Spring
- Inversión de control y contenedores de Spring
- Spring Initializr y dependencias comunes (`web`, `data-jpa`, `mysql`, etc.)
- Entorno de desarrollo (Maven, Spring Tools, IntelliJ, VS Code)

### 🔸 Desarrollo de Aplicaciones Web

- Controladores con `@RestController` y `@Controller`
- Mapear rutas con `@RequestMapping`, `@GetMapping`, `@PostMapping`, etc.
- Uso de `@RequestBody`, `@PathVariable`, `@RequestParam`
- Comunicación cliente-servidor con JSON

### 🔸 Persistencia de datos

- Conexión a MySQL con `application.properties`
- JPA + Hibernate (ORM)
- Anotaciones: `@Entity`, `@Id`, `@GeneratedValue`, `@Column`
- Repositorios con `JpaRepository`
- CRUD completo con base de datos

### 🔸 Documentación de API

- Uso de Swagger/OpenAPI para documentación automática
- Exploración y pruebas desde Swagger UI

### 🔸 Buenas prácticas y modelado

- Separación por capas (`Controller`, `Service`, `Repository`)
- Modelado de entidades y reglas de negocio
- Diagrama de clases (UML básico)

---

## 📁 Estructura del repositorio

```bash
bootcamp-modulo3-springboot/
├── README.md
├── /src
│   └── main/java/com/marceloamaya/proyecto/
│       ├── controller/
│       ├── service/
│       ├── model/
│       └── repository/
├── /resources
│   ├── application.properties
│   └── data.sql
├── /docs
│   └── diagrama_clases.png
├── /notas
│   └── comandos_spring.md
└── /recursos
    └── enlaces.txt
```

## ✅ Progreso

- [ ] Introducción a Spring Boot
- [ ] Crear API REST con controladores
- [ ] Conexión a base de datos y persistencia con JPA
- [ ] CRUD funcional con repositorio
- [ ] Documentación con Swagger
- [ ] Separación de capas (MVC)
- [ ] Mini proyecto con modelo de negocio real
- [ ] Despliegue local y empaquetado con Maven

---

## 🔗 Recursos útiles

- [Spring Boot Reference Docs](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [Spring Initializr](https://start.spring.io/)
- [Baeldung – Spring Boot](https://www.baeldung.com/spring-boot)
- [Swagger UI Demo](https://petstore.swagger.io/)
- [Thymeleaf (para proyectos con vistas)](https://www.thymeleaf.org/)

---

## ✍️ Autor

**Marcelo Amaya**  
Bootcamp Fullstack Java – CodiGo  
[GitHub](https://github.com/MarceloAM94)  
[LinkedIn](https://www.linkedin.com/in/marcelo-amaya-medina-614518268/)
