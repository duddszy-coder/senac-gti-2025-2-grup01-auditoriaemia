# Sistema de Auditoria Contínua para IA

## Microsserviço de Validação

Projeto acadêmico desenvolvido para a disciplina de Microsserviços em TI do Centro Universitário Senac Santo Amaro.

###  Tecnologias
- **Python** + Flask
- **Docker** + Docker Compose
- **Git** + GitHub

###  Como executar

#### Com Docker Compose (Recomendado):
\\\ash
docker-compose up -d
docker-compose ps
\\\

#### Com Docker individual:
\\\ash
docker build -t duddszyy/validacao:1.0.0 .
docker run -p 5000:5000 duddszyy/validacao:1.0.0
\\\

### Endpoints
- \GET /health\ - Status do serviço
- \POST /api/validacao/fairness\ - Teste de fairness

### Integrantes
- Carlos Henrique Silva dos Santos
- Jackeline Pessoa Gomes  
- Thalita Silva Ferreira
- Sara Alcantara
- Leonardo Fernandez de Souza Sales
- Maria Eduarda Rodrigues dos Santos

### 📄 Documentação
- Proposta técnica completa disponível no DocHub
