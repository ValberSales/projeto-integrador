
# 🗳️ TechVotos - Infraestrutura DevOps & Observabilidade

Este repositório contém a infraestrutura de containerização, orquestração e monitoramento para a API de Votação da startup **TechVotos**. O objetivo deste projeto é garantir que a aplicação seja versionada, execute isolada em containers e possua monitoramento em tempo real.

## 👨‍💻 Equipe de Engenharia

* **Allan** - Containerização (Docker)
* **Humberto** - Orquestração e Monitoramento
* **Valber** - CI/CD e Configuração do Projeto

## 🚀 Tecnologias Utilizadas
* **Aplicação:** Python 3.9 / Flask
* **Containerização:** Docker
* **Orquestração:** Docker Compose
* **Monitoramento:** Prometheus (Coleta de métricas)
* **Visualização:** Grafana (Dashboard) 
* **CI:** GitLab CI (Sintaxe de Pipeline)

## 📂 Estrutura do Projeto

O projeto segue a estrutura solicitada para o ambiente Linux (Debian 12):

```text
.
├── app.py                # Aplicação API de Votação
├── Dockerfile            # Definição da imagem do container
├── docker-compose.yml    # Orquestração dos serviços (App, Prometheus, Grafana)
├── prometheus.yml        # Configuração de coleta de métricas
├── requirements.txt      # Dependências Python
├── .gitlab-ci.yml        # Pipeline de Automação
└── .gitignore            # Arquivos ignorados pelo Git
