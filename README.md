# Santiago Valenzuela López

**Ingeniero Mecatrónico · Backend e IA aplicada** — Cali, Colombia

Diseño servicios en la nube que se pueden **operar, auditar y explicar**: IA generativa con RAG, plataformas sobre Cloud Run y gobernanza como código.

[**Portafolio**](https://santiagovalenzuelalopez-gif.github.io) · [LinkedIn](https://www.linkedin.com/in/santiagovalenzuelal/) · [Contacto](https://santiagovalenzuelalopez-gif.github.io/#contacto)

---

## En qué trabajo

- **IA aplicada** — RAG sobre Gemini con File Search, *function calling* con allow-list y agentes especialistas con presupuesto de tiempo.
- **Plataforma cloud** — Cloud Run, API Gateway, VPC, IAM y Secret Manager; CI/CD sin llaves con Workload Identity Federation.
- **Gobernanza como código** — estándares que se ejecutan y se verifican, con excepciones justificadas y observabilidad generada.

Vengo de los sistemas de control: pienso una arquitectura como un sistema con entradas, estados y realimentación. Me importa que un servicio falle de forma predecible, que se pueda verificar y que otra persona pueda reproducirlo.

## Proyectos

Cada uno tiene un caso de estudio con el problema, la arquitectura, las decisiones de diseño y **lo que se verificó y lo que no**.

| Proyecto | De qué trata | Tests |
|---|---|---|
| [**multitenant-rag-chatbot**](https://github.com/santiagovalenzuelalopez-gif/multitenant-rag-chatbot) | Chatbot RAG multitenant: tenants aislados, respuestas por el camino más barato, herramientas con allow-list | 19 |
| [**rag-ingest-eventarc**](https://github.com/santiagovalenzuelalopez-gif/rag-ingest-eventarc) | Ingesta event-driven idempotente: eventos duplicados y desordenados sin duplicar conocimiento | 27 |
| [**file-service-fastapi**](https://github.com/santiagovalenzuelalopez-gif/file-service-fastapi) | Descargas seguras: enlaces de un solo uso, reclamación atómica y auditoría por cliente | 41 |
| [**excel-reports-service**](https://github.com/santiagovalenzuelalopez-gif/excel-reports-service) | Reportes Excel en streaming con memoria acotada y protección contra inyección de fórmulas | 28 |
| [**ai-ticket-triage-agents**](https://github.com/santiagovalenzuelalopez-gif/ai-ticket-triage-agents) | Orquestador y agentes especialistas de IA; un código, tres desplegables; entradas hostiles | 76 |
| [**cloudrun-wif-cicd-kit**](https://github.com/santiagovalenzuelalopez-gif/cloudrun-wif-cicd-kit) | CI/CD sin llaves hacia Cloud Run, con verificación de mínimo privilegio | 84 |
| [**gcp-governance-toolkit**](https://github.com/santiagovalenzuelalopez-gif/gcp-governance-toolkit) | Estándar de servicio ejecutable (35 reglas) y observabilidad como código | 102 |

> Son **reimplementaciones desde cero, con datos sintéticos**, de patrones y problemas reales que resolví trabajando en plataformas de microservicios. No contienen código, datos ni infraestructura de ningún empleador o cliente. Se desarrollaron con Claude Code como asistente.

## Stack

**Backend** Python · FastAPI · SQLAlchemy · pytest  
**Cloud (GCP)** Cloud Run · API Gateway · VPC · IAM · Secret Manager · Firestore · Eventarc · Cloud Build  
**IA** Gemini API · Gemini File Search (RAG) · Function calling · Claude Code  
**Datos** MongoDB · MySQL · Firestore  
**DevOps** Docker · Azure DevOps · GitHub Actions · Workload Identity Federation · Bash

## Formación

Ingeniería Mecatrónica — UAO (título en trámite) · Especialización en Inteligencia Artificial — UAO (1 de 2 semestres cursados) · Google Professional Cloud Architect (en preparación)
