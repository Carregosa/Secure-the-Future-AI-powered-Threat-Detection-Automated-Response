# 🛡️ SentinelIA – Plataforma Inteligente de Detecção e Resposta a Ameaças com Azure + IA

## 🔍 Visão Geral
O **SentinelIA** é uma solução avançada de segurança que usa **Microsoft Azure**, **IA Generativa** e **Machine Learning** para detectar, priorizar e responder automaticamente a ameaças cibernéticas.

Criado para o **Innovation Challenge Hackathon**, o projeto demonstra como utilizar o ecossistema Microsoft para construir uma plataforma moderna de segurança inteligente com **IA Responsável**.

## 🎯 Challenge Escolhido
**Challenge:** *Secure the Future – AI-powered Threat Detection & Automated Response*

Caso de uso: Criar uma solução que utilize IA para melhorar a segurança, automatizar investigações e prevenir ataques antes que causem impacto.

## 🧠 Objetivos da Solução
- Reduzir MTTD e MTTR com IA e automação.
- Detectar anomalias e prever possíveis ataques.
- Explicar decisões de IA usando Azure OpenAI.
- Unificar dados de segurança em um pipeline automatizado.
- Criar automações de resposta via Azure Functions e Playbooks.
- Oferecer dashboards de risco em tempo real via Power BI.

# 🏗️ Arquitetura da Solução

### 🔹 Componentes Azure Utilizados
- Microsoft Sentinel
- Azure Log Analytics
- Defender for Cloud / M365 Defender
- Azure OpenAI Service
- Azure Machine Learning
- Azure Key Vault
- Azure Functions
- Azure Storage
- Power BI Embedded
- Azure Monitor

## 🔁 Fluxo Arquitetural
1. Coleta de logs → Log Analytics.
2. Sentinel correlaciona eventos e dispara alertas.
3. Azure OpenAI explica alertas e sugere ações.
4. Azure ML detecta anomalias e prevê ataques.
5. Azure Functions executa respostas automáticas.
6. Power BI exibe insights em tempo real.
7. Key Vault protege segredos.

# 🤖 IA Responsável
- Transparência
- Segurança com Key Vault
- Privacidade de dados
- Equidade de modelos
- Supervisão humana nas automações

# 🧪 Demonstração
Inclui:
- arquitetura
- fluxo de dados
- modelos de IA
- automação
- dashboard
- aprendizados

Link do vídeo: *adicionar quando disponível*

# 📁 Estrutura do Repositório
/sentinelia/
│ README.md  
│ LICENSE  
│ architecture.png  
│  
├── notebooks/  
│   └── threat-model-training.ipynb  
│  
├── functions/  
│   └── auto-response/index.js  
│  
├── sentinel/  
│   ├── analytic-rules.json  
│   ├── hunting-queries.kql  
│   └── watchlists.csv  
│  
├── ai/  
│   ├── risk-classification-prompt.txt  
│   └── openai-handler.py  
│  
└── dashboards/  
    └── sentinelia_powerbi.pbix  

# 👤 Desenvolvedor
Projeto desenvolvido individualmente por:

**Paulo Roberto Carregosa Luiz**  
(Security, Cloud & AI Enthusiast)

# 📅 Linha do Tempo
Dia 1 — Arquitetura  
Dia 2 — Conexão Sentinel  
Dia 3 — ML  
Dia 4 — IA Generativa  
Dia 5 — Automação  
Dia 6 — Dashboard  
Dia 7 — Testes  
Dia 8 — Vídeo  
Dia 9 — Revisão  
Dia 10 — Submissão  
