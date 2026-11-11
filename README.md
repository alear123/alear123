# Hola, soy Alejandro Arce 

**Ingeniero en Sistemas de Información (UTN-FRM)** · Desarrollador Backend Junior · Mendoza, Argentina

Me enfoco en el desarrollo **backend** con **Java/Spring Boot** y **Python/FastAPI**: APIs REST, seguridad con JWT, persistencia relacional y NoSQL y procesamiento asíncrono con colas de mensajes. También trabajo con React del lado del frontend.

 [LinkedIn](https://www.linkedin.com/in/alejandro-arce-448a29208) · alear12373@gmail.com

---

## Stack

**Backend**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)

**Bases de datos**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Herramientas**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

---

##  Proyectos destacados

###  Wevently — Proyecto Final de Carrera (aprobado)
**[Backend](https://github.com/alear123/wevently-backend) · [Frontend](https://github.com/alear123/wevently-frontend)**

Plataforma web para gestionar eventos de punta a punta: reservas de salones, contratación de prestadores, presupuestos y pagos en línea, con perfiles para organizadores, propietarios, prestadores y administradores. Desarrollada en equipo con flujo Gitflow.
- Backend monolítico organizado por **dominios (DDD)** y capas Controller / Service / Repository.
- Autenticación y autorización con **Spring Security + JWT** y roles.
- Integración de pagos con la **API de Mercado Pago**.

`Java` `Spring Boot` `Spring Data JPA` `Hibernate` `MySQL` `React` `Tailwind`

###  [pricing-service-py](https://github.com/alear123/pricing-service-py) — Arquitectura de Microservicios
Microservicio de cupones de descuento que se integra al ecosistema e-commerce de la cátedra (servicios de Auth, Carrito, Catálogo y Órdenes en Go).
- Registro de canjes **asíncrono con RabbitMQ (Pub/Sub)** para no bloquear el flujo de compra.
- Acceso **asíncrono a MongoDB** con Motor y gestión del ciclo de vida de la conexión.
- DTOs estrictos con **Pydantic v2**, configuración por variables de entorno y autenticación delegada al servicio de Auth con **JWT**.

`Python` `FastAPI` `MongoDB` `RabbitMQ` `Pydantic` `Docker`

###  [Energy Demand Predictor](https://github.com/alear123/CCDD_Streamlit_G20) — Ciencia de Datos · [Demo](https://ccddappg20-cypow9vvrx6zvcadssbjmk.streamlit.app/)
Predicción de la demanda energética horaria de Edenor, Edesur y Edelap a partir de datos de CAMMESA y variables climáticas de Open-Meteo.
- Pipeline ETL orquestado con **Apache Airflow**.
- Comparación de modelos lineales y de ensamble con **GridSearchCV**, con **R² de 0,93 a 0,94** según la región.
- Interfaz interactiva en **Streamlit**.

`Python` `Scikit-Learn` `Pandas` `Airflow` `Streamlit`

###  Plataforma de gestión de incendios forestales — PPS en IronFire
Desarrollé dos módulos dentro de una plataforma existente:
- **Despacho de brigadas:** motor de sugerencias geográficas con la fórmula de **Haversine** para calcular distancias y ETA, con mapas interactivos en Leaflet.
- **Análisis de datos con IA:** asistente que consulta la base mediante **Text-to-SQL** con un pipeline de dos pasos con LLM, aislamiento **multi-tenant** en cuatro capas y un validador de SQL con lista permitida de instrucciones.

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `React` `LLM`

---

##  Formación
**Ingeniería en Sistemas de Información** — UTN Facultad Regional Mendoza (2026)
