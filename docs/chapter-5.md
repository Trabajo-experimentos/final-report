## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

| Tipo de Herramienta  | Herramienta Utilizada                         | Propósito                              |
|----------------------|-----------------------------------------------|----------------------------------------|
| IDE                  | Visual Studio Code / WebStorm / IntelliJ Idea | Desarrollo frontend y backend          |
| Control de versiones | Git + GitHub                                  | Versionamiento y trabajo colaborativo  |
| Testing              | Gherkin                                       | Acceptance Tests                       |
| API Client           | Postman / Swagger                             | Validación de endpoints                |
| Base de Datos        | Postgres                                      | Almacenamiento persistente             |
| Documentación        | Swagger (OpenAPI)                             | Generación automática de documentación |
| Gestión de proyecto  | Trello                                        | Control ágil de tareas y User Stories  |

**Configuraciones adicionales:**  
El entorno de desarrollo utiliza variables `.env`, dependencias gestionadas con `npm`, y scripts configurados para automatizar pruebas y despliegues.

---

### 5.1.2. Source Code Management.

El control de versiones se gestiona con **GitHub** bajo la metodología **GitFlow Workflow**, que define ramas estables y de desarrollo:

- `develop`: rama principal de desarrollo.
- `feature/*`: ramas por funcionalidad.

**Convenciones:**
- Semantic Versioning (`v1.0.0`, `v1.1.0`, etc.)
- Conventional Commits (`feat:`, `fix:`, `docs:`)

**Repositorio donde se realizó el código:**

<br>

**Repositorio del proyecto actual:**

---

### 5.1.3. Source Code Style Guide & Conventions.

Guías de estilo aplicadas:

- TypeScript Style Guide.
- Gherkin Conventions for Readable Specifications.
- Clases en camelCase
- Uso de inglés en todo el código.

---

### 5.1.4. Software Deployment Configuration.

El despliegue de la landing page se realiza en Vercel

El despliegue del frontend se realiza en netlify

El despliegue del backend se realiza en **FreeSQL** para la base de datos.

**Pasos del pipeline:**
1. Build del proyecto (`npm run build`)
2. Ejecución de pruebas (`npm run test`)
3. Despliegue automatizado en entorno cloud
4. Validación mediante Postman y Swagger

<div style="page-break-after: always;"></div>

**Deployment Diagram (C4):**


<div style="page-break-after: always;"></div>

## 5.2. Product Implementation & Deployment.
### 5.2.1. Sprint Backlogs.
### 5.2.2. Implemented Landing Page Evidence
### 5.2.3. Implemented Frontend-Web Application Evidence
### 5.2.4. Acuerdo de Servicio - SaaS
### 5.2.5. Implemented Native-Mobile Application Evidence
### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence
### 5.2.7. RESTful API documentation
### 5.2.8. Team Collaboration Insights
## 5.3. Video About-the-Product
