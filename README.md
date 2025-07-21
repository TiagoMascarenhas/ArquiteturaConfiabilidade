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

🧩 5. Conclusão da Arquitetura
A arquitetura proposta é composta por uma combinação de serviços AWS integrados que formam um ecossistema robusto de alta disponibilidade e recuperação de desastres. Ela garante:
🔧 Tolerância a Falhas:

Amazon RDS Multi-AZ: Proporciona failover automático com RPO próximo a zero através de replicação síncrona entre zonas de disponibilidade
AWS Elastic Load Balancer: Implementa health checks automáticos e redistribui tráfego apenas para instâncias saudáveis, eliminando pontos únicos de falha
Amazon Route 53: Oferece roteamento baseado em saúde com failover DNS automático, direcionando tráfego para recursos disponíveis

⚡ Recuperação Automática:

AWS Auto Scaling Groups: Detecta falhas de instâncias EC2 e automaticamente substitui recursos indisponíveis, mantendo a capacidade desejada
AWS CloudFormation: Permite recriação rápida e consistente da infraestrutura através de templates versionados (Infrastructure as Code)
AWS Backup: Executa backups automatizados cross-region com políticas de retenção configuráveis e restauração point-in-time

🛡️ Proteção contra Ameaças:

AWS WAF: Filtra tráfego malicioso através de regras personalizáveis, protegendo contra OWASP Top 10 e ataques DDoS de camada de aplicação
Amazon S3: Garante durabilidade de 99.999999999% (11 9's) através de replicação automática em múltiplas facilities
AWS CloudWatch: Monitora métricas em tempo real e dispara alarmes para detecção proativa de anomalias e incidentes

🔄 Operação Contínua:

Multi-AZ Deployment: Distribui recursos em pelo menos 3 zonas de disponibilidade, garantindo continuidade mesmo com falhas de datacenter
Cross-Region Replication: Amazon S3 e RDS permitem replicação geográfica para cenários de disaster recovery
Elastic Load Balancing: Suporta health checks avançados com failover em segundos, mantendo SLA de 99.99% de uptime

Esta arquitetura implementa os padrões de Well-Architected Framework da AWS, especificamente os pilares de Reliability e Security, proporcionando RTO (Recovery Time Objective) de minutos e RPO (Recovery Point Objective) próximo a zero, essenciais para operações críticas de negócio.

---

## 📎 Apresentação

Você pode visualizar a apresentação [clicando aqui](https://github.com/TiagoMascarenhas/ArquiteturaConfiabilidade/blob/main/Apresenta%C3%A7%C3%A3o%20-%20Confiabilidade.pdf).

---

## 👥 Integrantes

- Camila Moreira
- Gisele Lais Aparecida
- Tiago Mascarenhas (responsável pelas partes listadas acima)
