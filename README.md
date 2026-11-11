<h1 align="center">Adrián Ducuara</h1>
<p align="center">
  <b>Data Analysis · Cybersecurity · Backend & Cloud</b><br>
  Software Engineering student · Escuela Colombiana de Ingeniería Julio Garavito · Bogotá, Colombia
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/adrian-ducuara"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:adrianducuara844@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/DUCU844/DUCU844/blob/main/CV_Adrian_Ducuara.pdf"><img src="https://img.shields.io/badge/CV-PDF-333333?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="CV"></a>
</p>

<p align="center"><a href="#english">English</a> · <a href="#español">Español</a></p>

---

## English

Software Engineering student with a versatile profile: I build and deploy full systems end to end, and I focus on two areas.

- **Data analysis and machine learning:** regression and classification models implemented from first principles, CNN experiments, RAG pipelines with LLMs, and metrics-driven monitoring with Prometheus and Grafana.
- **Cybersecurity:** security for AI agents (RBAC/JWT, prompt-injection mitigation, audit logs), OAuth2/JWT authentication with Auth0, static binary analysis and reverse engineering (GDB, QEMU), and cryptography with GPG.
- **Backend and cloud:** Java / Spring Boot microservices, WebSockets, hexagonal architecture, Docker and AWS.

## Español

Estudiante de Ingeniería de Sistemas con un perfil versátil: construyo y despliego sistemas completos, y me enfoco en dos áreas.

- **Análisis de datos y machine learning:** modelos de regresión y clasificación implementados desde cero, experimentos con CNN, pipelines RAG con LLMs y monitoreo basado en métricas con Prometheus y Grafana.
- **Ciberseguridad:** seguridad para agentes de IA (RBAC/JWT, mitigación de prompt injection, audit logs), autenticación OAuth2/JWT con Auth0, análisis estático de binarios e ingeniería inversa (GDB, QEMU) y criptografía con GPG.
- **Backend y nube:** microservicios en Java / Spring Boot, WebSockets, arquitectura hexagonal, Docker y AWS.

---

## Featured projects · Proyectos destacados

### UNO Power-Ups Arena · Capstone

**EN:** Real-time multiplayer UNO with power-ups and chat, built end to end as a microservice system: React client, API gateway, three Spring Boot services, and Prometheus/Grafana observability with business KPIs. Every repository has CI, tests with coverage, and Docker images.

**ES:** UNO multijugador en tiempo real con power-ups y chat, construido de punta a punta como sistema de microservicios: cliente React, API gateway, tres servicios Spring Boot y observabilidad con Prometheus/Grafana y KPIs de negocio. Cada repositorio tiene CI, pruebas con cobertura e imagen Docker.

| Repository | EN | ES | Stack |
|---|---|---|---|
| [GameService](https://github.com/UNO-POWER/GameService) | Real-time game engine, power-ups and chat over a single STOMP WebSocket, JWT on connect, in-memory concurrent model | Motor de partida en tiempo real, power-ups y chat sobre un WebSocket STOMP, JWT al conectar, modelo concurrente en memoria | Java 21 · Spring Boot · WebSocket/STOMP |
| [FRONT](https://github.com/UNO-POWER/FRONT) | Web client with REST through the gateway and WebSocket to the game engine | Cliente web con REST vía gateway y WebSocket al motor de juego | React 18 · TypeScript · Tailwind · Vite |
| [APIGATEWAY](https://github.com/UNO-POWER/APIGATEWAY) | Single REST entry point: routing, JWT validation, structured logs with traceId | Punto de entrada REST único: enrutamiento, validación JWT, logs estructurados con traceId | Spring Cloud Gateway · JWT |
| [UserService](https://github.com/UNO-POWER/UserService) | Registration, login, guest access, JWT issuance, BCrypt and player statistics | Registro, login, acceso como invitado, emisión de JWT, BCrypt y estadísticas del jugador | Spring Boot · PostgreSQL · JWT |
| [LobbyService](https://github.com/UNO-POWER/LobbyService) | Room creation and public matchmaking with pessimistic locking | Creación de salas y matchmaking público con bloqueo pesimista | Spring Boot · JPA · PostgreSQL |
| [ObservabilityStack](https://github.com/UNO-POWER/ObservabilityStack) | Prometheus scraping and Grafana dashboards provisioned as code, technical and business KPIs | Scraping con Prometheus y dashboards de Grafana como código, KPIs técnicos y de negocio | Prometheus · Grafana · Docker Compose |

### PATRICI.A · Winning project / Proyecto ganador (DOSW 2026)

| | EN | ES |
|---|---|---|
| [Feed & Search Service](https://github.com/PATRICI-A/mewtwocode-feed-search-service) | Top contributor to the feed, search, interactions and recommendations microservice: 5 REST endpoints secured with JWT (OAuth2 resource server), PostgreSQL, Redis cache and hexagonal architecture, with CI/CD and Docker. I also migrated the squad's message broker to a self-managed AWS EC2 instance. | Mayor contribuidor del microservicio de feed, búsqueda, interacciones y recomendaciones: 5 endpoints REST protegidos con JWT (OAuth2 resource server), PostgreSQL, caché con Redis y arquitectura hexagonal, con CI/CD y Docker. También migré el broker de mensajería del equipo a una instancia EC2 propia. |

### Data analysis & ML · Análisis de datos y ML

| Project | EN | ES | Stack |
|---|---|---|---|
| [Logistic Regression](https://github.com/DUCU844/AREP_Logistic-Regression-and-Classification) | Heart disease risk prediction with logistic regression implemented from scratch | Predicción de riesgo cardíaco con regresión logística implementada desde cero | Python · NumPy · Jupyter |
| [Stellar Luminosity Regression](https://github.com/DUCU844/AREP_stellar-luminosity-regression) | Linear and polynomial regression from first principles | Regresión lineal y polinomial desde cero | Python · NumPy · Jupyter |
| [Convolutional Layers](https://github.com/DUCU844/AREP_Exploring-Convolutional-Layers-Through-Data-and-Experiments) | MLP baseline vs CNN designed from scratch, compared through experiments | MLP base vs CNN diseñada desde cero, comparadas con experimentos | Python · Deep Learning |
| [RAG on Architecture Patterns](https://github.com/DUCU844/AREP_RAG-Gemini) | Retrieval-Augmented Generation over microservice architecture patterns | RAG sobre patrones de arquitectura de microservicios | Gemini · LangChain · Chroma |
| [Microservice Observability](https://github.com/DUCU844/ARSW_Observabilidad) | Metrics, dashboards and centralized logs for Spring Boot services | Métricas, dashboards y logs centralizados para servicios Spring Boot | Prometheus · Grafana · Loki |

### Cybersecurity · Ciberseguridad

| Project | EN | ES | Stack |
|---|---|---|---|
| [Secure Web System](https://github.com/DUCU844/AREP_Secure_Web_System_as_an_Enterprise_Risk_Control) | SPA and resource server secured with Auth0 (OAuth2/JWT, permission scopes), HTTPS reverse proxy, firewall hardening on AWS | SPA y API protegidas con Auth0 (OAuth2/JWT, permisos), proxy inverso HTTPS y firewall en AWS | React · Spring Boot · Auth0 · Apache |
| AI agent security (SPTI) | RBAC/JWT permission supervisor that blocks prompt injection and unauthorized tool use, with audit logs in PostgreSQL | Supervisor de permisos RBAC/JWT que bloquea prompt injection y uso no autorizado de herramientas, con audit logs en PostgreSQL | Python · FastAPI · LangChain · PostgreSQL |
| Security labs | Static binary analysis and debugging, GPG cryptography, DNS/NTP configuration on Linux and Windows Server | Análisis estático y depuración de binarios, criptografía con GPG, DNS/NTP en Linux y Windows Server | GDB · QEMU · GPG · Linux |

### Backend & cloud · Backend y nube

| Project | EN | ES | Stack |
|---|---|---|---|
| [Serverless Orders API](https://github.com/DUCU844/serverless-orders-api) | Contract-first REST API on AWS Lambda, deployed with two API Gateway integration styles (non-proxy with mapping templates, and Lambda proxy) and a uniform error model | API REST contract-first en AWS Lambda, desplegada con dos estilos de integración de API Gateway (non-proxy con mapping templates y Lambda proxy) y un modelo de errores uniforme | Java 17 · AWS Lambda · API Gateway |
| [TechCup Fútbol](https://github.com/Cove1946/TechCup-FRONTEND) | Web platform for the university's internal football tournaments; frontend contributor in a team with rotating leadership | Plataforma web para torneos internos de fútbol de la universidad; contribuidor del frontend en un equipo con liderazgo rotativo | Web frontend |
| [Java HTTP Server on AWS](https://github.com/DUCU844/AREP_From_a_Minimal_HTTP_Server_to_a_Web_Application_on_AWS) | Socket-based HTTP server extended to static resources and JSON services, deployed on EC2 | Servidor HTTP desde sockets con recursos estáticos y servicios JSON, desplegado en EC2 | Java · Sockets · AWS EC2 |
| [Testing Strategy](https://github.com/DUCU844/ARSW_PRUEBAS) | Unit, API and integration testing for web apps and microservices | Pruebas unitarias, de API y de integración | JUnit · Mockito · MockMvc |
| [AWS Lambda + API Gateway](https://github.com/DUCU844/hello_world_aws_lambda_api_gateway_java) | Java Lambda function exposed through API Gateway | Función Lambda en Java expuesta con API Gateway | Java · AWS Lambda |

---

## Tech stack

**Data & ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**Security**
![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![OAuth2 / JWT](https://img.shields.io/badge/OAuth2%20%2F%20JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![GnuPG](https://img.shields.io/badge/GPG-0093DD?style=flat-square&logo=gnuprivacyguard&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GDB / QEMU](https://img.shields.io/badge/GDB%20%2F%20QEMU-555555?style=flat-square&logo=qemu&logoColor=white)

**Backend & Cloud**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud Gateway](https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?style=flat-square&logo=spring&logoColor=white)
![WebSocket / STOMP](https://img.shields.io/badge/WebSocket%20%2F%20STOMP-010101?style=flat-square&logo=socketdotio&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
