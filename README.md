<h1 align="left">
  Studying Java Spring
  <img src="https://github.com/user-attachments/assets/9705bdff-b786-4a16-bd2c-498ea325cc12" alt="Spring_Boot svg" width="30"/>
  <img src="https://github.com/user-attachments/assets/1c9c584c-1d92-43e5-ad41-6389bafd28b3" width="30"/>
</h1>

Examples and notes on **Spring Framework** and **Spring Boot**.

## Spring vs Spring Boot

- **Spring**: Comprehensive framework for Java applications
- **Spring Boot**: Extension that simplifies setup with auto-configuration, embedded server, and dependency management


## Project Structure

| Folder/File | Purpose |
|---|---|
| `pom.xml` | Maven dependency management |
| `.mvn/` | Maven configurations |
| `src/main/java/` | Application source code |
| `src/main/resources/` | Configuration files and static resources |
| `src/test/java/` | Unit tests |

**Configuration files** (`application.properties` or `application.yml`): Define server port, database credentials, and profiles (dev, prod, test)

# Annotations

Spring relies on annotations (prefixed with `@`) to configure classes, methods, and fields for dependency injection, routing, exception handling, etc.

# Dependencies

| Dependency | Description |
|---|---|
| **Spring Boot DevTools** | Auto-restart during development |
| **Spring Web** | REST APIs, HTTP request handling, MVC integration |
| **Lombok** | Auto-generates getters, setters, constructors |

# Key Annotations

| Annotation | Purpose |
|---|---|
| **@SpringBootApplication** | Main class - enables auto-configuration and package scanning |
| **@RestController** | HTTP controller that returns JSON/XML responses |
| **@Service** | Business logic component |
| **@Autowired** | Dependency injection |
| **@Bean** | Registers a bean for Spring to manage |
| **@Configuration** | Configuration class with bean definitions |
| **@RequestBody** | Converts request body to method parameter |
| **@PathVariables** | Captures URL path values |
| **@Getter, @Setter, @AllArgsConstructor** | Lombok - auto-generates getters, setters, constructors |

## Extras

**Architecture**: ![Spring-Boot-Workflow-Architecture-1024x614](https://github.com/user-attachments/assets/00a33542-c5c3-4b35-9055-34ffce968c36)

**Stateless vs Stateful**
- **Stateless**: Each request contains all necessary info (tokens, etc.) - no server-side state
- **Stateful**: Server maintains client state between requests
