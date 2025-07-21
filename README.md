# Projeto Alcance Global - Infraestrutura Resiliente com AWS

Este repositório contém o trabalho desenvolvido em grupo com foco em uma arquitetura resiliente e de alta disponibilidade utilizando serviços da AWS.

## 🧠 Objetivo

Demonstrar como os serviços da AWS fortalecem a confiabilidade e a recuperação de desastres da infraestrutura, garantindo:
- Alta disponibilidade
- Resiliência
- Proteção contínua dos dados

---

## 🔧 Tecnologias e Serviços AWS Utilizados

- **Amazon S3** – Armazenamento escalável de objetos
- **AWS Backup** – Backup automatizado
- **Amazon RDS** – Banco de dados relacional gerenciado
- **Elastic Load Balancer (ELB)** – Balanceamento de carga
- **Amazon Route 53** – Gerenciador de DNS
- **AWS CloudFormation** – Infraestrutura como código
- **AWS CloudWatch** – Monitoramento de métricas e logs
- **AWS WAF** – Proteção contra ataques na camada de aplicação

---

## ⚙️ Contribuições Individuais

### Tiago Mascarenhas

#### ✅ 1. Calculadora (Simulação)

Implementei uma estimativa de custos utilizando a [AWS Pricing Calculator](https://calculator.aws/#/estimate?id=95ae99b87db165a43063586d83df89bbc26f6406), baseada nos serviços utilizados na arquitetura. A simulação ajuda a prever os custos mensais e a analisar a viabilidade da solução.

**Serviços incluídos:**
- EC2
- RDS
- S3
- Load Balancer
- Backup
- CloudWatch
- WAF

🔗 **Acesse aqui a estimativa:** [AWS Calculator](https://calculator.aws/#/estimate?id=95ae99b87db165a43063586d83df89bbc26f6406)

#### 🛡️ 2. Explicação do AWS WAF

O **AWS WAF** protege aplicações web contra ataques comuns, como injeção de SQL, XSS e bots automatizados. Foi utilizado na arquitetura para reforçar a segurança na borda, filtrando tráfego malicioso antes de atingir as aplicações.

#### 📦 3. AWS CloudFormation

O **CloudFormation** permite criar e gerenciar toda a infraestrutura como código (IaC). Isso garante padronização, reprodutibilidade e facilidade de manutenção, mesmo em ambientes complexos.

#### 📊 4. AWS CloudWatch

O **CloudWatch** é essencial para monitoramento contínuo, coleta de métricas e geração de alarmes. Ele permite observar o desempenho dos serviços em tempo real e agir rapidamente em caso de falhas.

#### 🧩 5. Conclusão da Arquitetura

A arquitetura proposta integra múltiplos serviços da AWS de forma orquestrada, garantindo:
- Alta disponibilidade
- Tolerância a falhas
- Monitoramento e segurança constantes

Essa composição assegura a continuidade das operações mesmo diante de imprevistos, sendo ideal para empresas que precisam de confiabilidade no ambiente em nuvem.

---

## 📎 Apresentação

Você pode visualizar a apresentação em PDF na pasta [docs/apresentacao.pdf](./docs/apresentacao.pdf)

---

## 👥 Integrantes

- Camila Moreira
- Gisele Lais Aparecida
- Tiago Mascarenhas (responsável pelas partes listadas acima)
