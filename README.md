\# Pedidos360



Preparación del proyecto FullStack Pedidos360: Angular + Spring Boot

\*\*Asignatura:\*\* DSY1107 - Desarrollo Cloud Native I

\*\*Evaluación:\*\* Evaluación Parcial N°1 (Encargo, en parejas)



\## Descripción

Sistema Pedidos360: arquitectura base con frontend Angular (autenticación Azure AD / MSAL) y backend Spring Boot (microservicios) desplegado en EC2, protegido mediante AWS API Gateway.



\## Tecnologías

\- \*\*Frontend:\*\* Angular, MSAL (Microsoft Authentication Library)

\- \*\*Backend:\*\* Java, Spring Boot (microservicios)

\- \*\*Identity as a Service (IDaaS):\*\* Microsoft Entra ID

\- \*\*API Management:\*\* AWS API Gateway

\- \*\*Base de datos:\*\* Cloud (por definir)



\## Estructura del repositorio

```

pedidos360/

├── frontend/       # Componente Angular

├── backend/        # Microservicios Spring Boot

└── README.md

```



\## Estado actual

\- \[x] Repositorio creado

\- \[x] Guía de Clase 3 - Parte 1 completada (preparación del proyecto)

\- \[ ] Configuración de cuenta y app registration en Microsoft Entra ID

\- \[ ] Integración MSAL en Angular

\- \[ ] Backend: microservicios + validación JWT (filtros)

\- \[ ] BFF: validación de issuer/audience/firma del token

\- \[ ] Despliegue en EC2 + configuración AWS API Gateway



\## Requisitos previos

\- Node.js y Angular CLI

\- JDK y Maven/Gradle

\- Cuenta Azure con Microsoft Entra ID configurado

\- Cuenta AWS (EC2, API Gateway)



\## Cómo ejecutar



\### Frontend

```bash

cd frontend

npm install

ng serve

```



\### Backend

```bash

cd backend

mvn spring-boot:run

```



\- Alexander Mercado



\## Asignatura

DSY1107 - Desarrollo Cloud Native I, DuocUC

