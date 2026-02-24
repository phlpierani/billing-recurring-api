# 💳 Recurring Billing SaaS

SaaS de cobrança recorrente para prestadores de serviço, com arquitetura baseada em eventos, integração com gateway de pagamento e foco em escalabilidade.

Projeto desenvolvido com foco em arquitetura moderna, boas práticas de backend e observabilidade.

---

## 🚀 Tecnologias Utilizadas

### Backend
- Java 21
- Spring Boot 4
- Spring Security + OAuth2 Resource Server
- Spring Data JPA
- PostgreSQL
- Flyway (versionamento de banco)
- RabbitMQ (mensageria)
- OpenFeign (integração com APIs externas)
- Spring Boot Actuator
- Micrometer + Datadog
- Testcontainers

### DevOps
- Docker
- Docker Compose
- GitHub Actions (CI/CD)

---

## 🏗 Arquitetura

O sistema foi projetado seguindo princípios de:

- Arquitetura em camadas
- Event-driven (mensageria com RabbitMQ)
- Separação de responsabilidades
- Integração externa desacoplada via Feign Client
- Observabilidade e métricas desde o início

### Componentes principais

- API REST (Spring Boot)
- Banco de dados PostgreSQL
- Mensageria RabbitMQ
- Integração com gateway de pagamento
- Serviço de notificação

---

## 📌 Funcionalidades Planejadas (MVP)

- Cadastro de prestadores de serviço (multi-tenant)
- Criação de planos de cobrança
- Criação de assinaturas
- Processamento de cobranças recorrentes
- Registro de pagamentos
- Geração de eventos de renovação
- Notificação de falha/sucesso
- Integração com gateway de pagamento

---

## 🗂 Estrutura do Projeto
