<div align="center">

<img src="./img/logo.png" width="30">  

# 🔐 Roadmap DevSecOps: do zero à prática

Um guia para quem quer entrar em **DevSecOps**, mas não sabe em que ordem estudar programação, segurança, Linux, cloud, containers, CI/CD e as principais ferramentas da área.  
**Roadmap não é checklist. Roadmap é direção. 🗺️**

</div>

---

## 📑 Sumário

- [Visão Geral](#️-visão-geral)
- [Antes de começar: o que é DevSecOps?](#-antes-de-começar-o-que-é-devsecops)
- [Etapa 0 — Desenvolvimento e programação](#-etapa-0--desenvolvimento-e-programação)
- [Etapa 1 — Linux e redes](#-etapa-1--linux-e-redes)
- [Etapa 2 — Fundamentos de segurança](#-etapa-2--fundamentos-de-segurança)
- [Etapa 3 — DevOps, Git e CI/CD](#-etapa-3--devops-git-e-cicd)
- [Etapa 4 — Segurança no CI/CD](#-etapa-4--segurança-no-cicd)
- [Etapa 5 — Containers e Infrastructure as Code](#-etapa-5--containers-e-infrastructure-as-code)
- [Etapa 6 — Cloud e IAM](#-etapa-6--cloud-e-iam)
- [Etapa 7 — DevSecOps avançado](#-etapa-7--devsecops-avançado)
- [Etapa 8 — Frameworks e maturidade](#-etapa-8--frameworks-e-maturidade)
- [Bônus — IA e DevSecOps](#-bônus--ia-e-devsecops)
- [Projeto prático — Do código à segurança](#-projeto-prático--do-código-à-segurança)
- [Sequência sugerida de estudos](#-sequência-sugerida-de-estudos)
- [O verdadeiro roadmap](#-o-verdadeiro-roadmap)
- [Sobre este material](#-sobre-este-material)
- [Autora](#-autora)

---

## 🗺️ Visão geral

```text
💻 0. Desenvolvimento e programação
            ↓
🐧 1. Linux e redes
            ↓
🔐 2. Fundamentos de segurança
            ↓
⚙️ 3. DevOps, Git e CI/CD
            ↓
🔎 4. Segurança no CI/CD
            ↓
🐳 5. Containers e Infrastructure as Code
            ↓
☁️ 6. Cloud e IAM
            ↓
🛡️ 7. DevSecOps avançado
            ↓
🔁 Aprender → Praticar → Automatizar → Monitorar → Melhorar
```

> **Importante:** as etapas não são totalmente lineares. Você não precisa dominar 100% de uma etapa antes de iniciar a seguinte. É normal avançar e voltar aos fundamentos.

---

## 💜 Antes de começar: o que é DevSecOps?

DevSecOps combina:

- **DEV — Development:** desenvolvimento de software;
- **SEC — Security:** segurança;
- **OPS — Operations:** operações.

DevSecOps não significa apenas instalar ferramentas de segurança em uma pipeline. A proposta é integrar segurança ao ciclo de vida do software, do planejamento à operação.

Isso envolve:

- pessoas e cultura;
- processos;
- desenvolvimento seguro;
- automação;
- tecnologia;
- governança;
- monitoramento e melhoria contínua.

> 🔐 **Segurança não deve ser apenas uma validação no final. Ela precisa fazer parte do processo.**

---

# 💻 Etapa 0 — Desenvolvimento e programação

## Objetivo

Entender como aplicações são construídas antes de aprender a protegê-las.

## Estude

- [ ] Lógica de programação
- [ ] Algoritmos
- [ ] Estruturas de dados básicas
- [ ] Uma linguagem de programação
- [ ] Git e GitHub
- [ ] APIs REST
- [ ] HTTP e HTTPS
- [ ] JSON
- [ ] Banco de dados e SQL
- [ ] Testes automatizados

## Qual linguagem escolher?

Você não precisa aprender várias linguagens ao mesmo tempo. Escolha uma:

- **Python:** scripts e automação;
- **JavaScript/TypeScript:** aplicações web e APIs;
- **Java:** sistemas corporativos e APIs;
- **C#:** aplicações .NET e ecossistema Microsoft;
- **Go:** automação, cloud e ferramentas de infraestrutura.

O mais importante é aprender a programar, ler código e compreender o funcionamento de uma aplicação.

## Projeto prático

Crie uma API simples de tarefas:

```text
POST   /tasks
GET    /tasks
GET    /tasks/{id}
PUT    /tasks/{id}
DELETE /tasks/{id}
```

Use o mesmo projeto durante todo o roadmap.

---

# 🐧 Etapa 1 — Linux e redes

## Linux

- [ ] Terminal e shell
- [ ] Arquivos e diretórios
- [ ] Usuários e grupos
- [ ] Permissões
- [ ] Processos e serviços
- [ ] Variáveis de ambiente
- [ ] SSH
- [ ] Logs
- [ ] Bash básico

Comandos iniciais:

```bash
ls
cd
pwd
cat
grep
find
ps
chmod
chown
curl
ssh
```

## Redes

- [ ] IP
- [ ] Portas
- [ ] DNS
- [ ] TCP/IP
- [ ] HTTP e HTTPS
- [ ] TLS
- [ ] Proxy
- [ ] Firewall
- [ ] Requisições e respostas

Fluxo para compreender:

```text
Cliente
   ↓
DNS
   ↓
HTTPS
   ↓
Servidor
   ↓
Aplicação
   ↓
Banco de dados
```

---

# 🔐 Etapa 2 — Fundamentos de segurança

## Conceitos fundamentais

- [ ] Confidencialidade, integridade e disponibilidade
- [ ] Autenticação e autorização
- [ ] Princípio do menor privilégio
- [ ] Criptografia básica
- [ ] Hashing
- [ ] Gestão de secrets
- [ ] Gestão de vulnerabilidades
- [ ] Secure Coding
- [ ] Threat Modeling
- [ ] Gestão de riscos

## Segurança de aplicações

Estude materiais da **OWASP**, com foco inicial em:

- [ ] Broken Access Control
- [ ] Injection
- [ ] Cryptographic Failures
- [ ] Security Misconfiguration
- [ ] Identification and Authentication Failures
- [ ] Vulnerable and Outdated Components

Troque a pergunta:

> “Meu código funciona?”

por:

> 🔐 **“Meu código funciona de maneira segura?”**

---

# ⚙️ Etapa 3 — DevOps, Git e CI/CD

## Objetivo

Entender como o código sai da máquina de desenvolvimento e chega a um ambiente.

## Estude

- [ ] Branches
- [ ] Pull Requests
- [ ] Code Review
- [ ] Build
- [ ] Testes automatizados
- [ ] Artefatos
- [ ] Deploy
- [ ] Continuous Integration
- [ ] Continuous Delivery
- [ ] Continuous Deployment
- [ ] Pipelines
- [ ] Logs e observabilidade básica

## Escolha uma ferramenta de CI/CD

- GitHub Actions
- GitLab CI/CD
- Azure Pipelines
- Jenkins

Não tente aprender todas. Escolha uma e entenda os conceitos.

## Projeto prático

```text
Push ou Pull Request
        ↓
       Build
        ↓
 Testes automatizados
        ↓
      Artefato
        ↓
       Deploy
```

Quando isso estiver funcionando, pergunte:

> **Como adicionamos segurança a esse fluxo? 🔐**

---

# 🔎 Etapa 4 — Segurança no CI/CD

## Secret Scanning

Procura credenciais expostas, como:

- tokens;
- senhas;
- API keys;
- certificados;
- chaves privadas;
- connection strings.

> Nunca use credenciais reais em laboratórios. Crie dados fictícios exclusivamente para testes.

## SAST

**Static Application Security Testing** analisa código ou artefatos sem executar ataques contra a aplicação.

- [ ] Regras
- [ ] Findings
- [ ] Severidade
- [ ] Falsos positivos
- [ ] Integração com CI/CD

## SCA

**Software Composition Analysis** identifica riscos em dependências e componentes de terceiros.

- [ ] Dependências diretas e transitivas
- [ ] Versões vulneráveis
- [ ] Licenças
- [ ] Remediação
- [ ] CVE, CWE e CVSS

## DAST

**Dynamic Application Security Testing** testa uma aplicação em execução.

- [ ] Endpoints
- [ ] Autenticação
- [ ] Ambientes de teste
- [ ] Falsos positivos
- [ ] Integração com pipeline

## IaC Scanning

Analisa infraestrutura definida como código, incluindo:

- Terraform;
- manifests Kubernetes;
- Helm Charts;
- templates de cloud.

## Pipeline didática

```text
Código
  ↓
Secret Scanning
  ↓
SAST
  ↓
SCA
  ↓
Build e testes
  ↓
Container e IaC Scanning
  ↓
DAST
  ↓
Security Gates
  ↓
Deploy
```

> A ordem não é universal. Os controles e critérios devem ser adaptados à arquitetura, ao risco e ao ciclo de desenvolvimento de cada projeto.

---

# 🐳 Etapa 5 — Containers e Infrastructure as Code

## Docker

- [ ] Images
- [ ] Containers
- [ ] Dockerfile
- [ ] Registries
- [ ] Volumes
- [ ] Networking
- [ ] Variáveis de ambiente
- [ ] Usuários e permissões

## Segurança de containers

- [ ] Container Scanning
- [ ] Vulnerabilidades em imagens
- [ ] Imagens base confiáveis e mínimas
- [ ] Gestão de secrets
- [ ] Execução sem root
- [ ] Hardening

## Infrastructure as Code

Comece com **Terraform**:

- [ ] Providers
- [ ] Resources
- [ ] Variables
- [ ] State
- [ ] Modules
- [ ] Configurações seguras
- [ ] IaC Scanning

## Kubernetes

Não comece por Kubernetes. Uma ordem mais segura é:

```text
Linux → Redes → Docker → CI/CD → Cloud → Kubernetes
```

Depois aprofunde:

- [ ] RBAC
- [ ] Network Policies
- [ ] Secrets
- [ ] Security Context
- [ ] Admission Controls
- [ ] Segurança de clusters e workloads

---

# ☁️ Etapa 6 — Cloud e IAM

Escolha inicialmente uma plataforma:

- Microsoft Azure;
- Amazon Web Services;
- Google Cloud Platform.

## Fundamentos

- [ ] IAM
- [ ] Identidades e permissões
- [ ] RBAC
- [ ] Compute
- [ ] Storage
- [ ] Networking
- [ ] Secrets
- [ ] Logging
- [ ] Monitoring
- [ ] Princípio do menor privilégio

Pergunta central:

> **Quem tem permissão para fazer o quê?**

---

# 🛡️ Etapa 7 — DevSecOps avançado

## Software Supply Chain Security

- [ ] Software Supply Chain
- [ ] SBOM
- [ ] Provenance
- [ ] Assinatura de artefatos
- [ ] Segurança de dependências
- [ ] Proteção de pipelines

## Segurança e governança

- [ ] Policy as Code
- [ ] Security Gates
- [ ] Compliance
- [ ] Vulnerability Management
- [ ] Risk Management
- [ ] Exceções e aceite de risco

## Operação

- [ ] Logging
- [ ] Monitoring
- [ ] Observability
- [ ] Incident Response
- [ ] Gestão contínua de vulnerabilidades

Segurança não termina no deploy. Uma dependência considerada segura hoje pode receber uma vulnerabilidade crítica no futuro.

---

# 📚 Etapa 8 — Frameworks e maturidade

Conheça gradualmente:

- **NIST SSDF:** práticas para desenvolvimento seguro;
- **OWASP SAMM:** maturidade em segurança de software;
- **OWASP DSOMM:** maturidade em DevSecOps;
- **SLSA:** integridade da cadeia de fornecimento de software.

Não tente decorar os frameworks. Entenda qual problema cada um resolve e como pode orientar melhorias reais.

---

# 🤖 Bônus — IA e DevSecOps

Depois de consolidar a base, explore:

- [ ] Revisão de código gerado por IA
- [ ] Riscos de código sugerido por GitHub Copilot e outros LLMs
- [ ] Análise de vulnerabilidades assistida por IA
- [ ] Segurança de aplicações com LLMs
- [ ] Prompt Injection
- [ ] Proteção de secrets e dados sensíveis
- [ ] AI Governance

---

# 🧪 Projeto prático — Do código à segurança

A prática deve acompanhar todo o roadmap.

## Fase 1 — Aplicação

```text
API simples → GitHub → Testes
```

## Fase 2 — CI/CD

```text
GitHub Actions → Build → Testes automatizados
```

## Fase 3 — Segurança de código e dependências

```text
Secret Scanning → SAST → SCA
```

## Fase 4 — Containers

```text
Docker → Container Scanning
```

## Fase 5 — Infraestrutura

```text
Terraform → IaC Scanning
```

## Fase 6 — Operação

```text
Cloud → Deploy → Logs → Monitoring
```

Ao final, você poderá explicar:

> **“Construí uma aplicação e adicionei controles de segurança ao ciclo de desenvolvimento, entrega e operação.”**

---

# 📅 Sequência sugerida de estudos

| Período | Foco |
|---|---|
| 1 | Programação e Git |
| 2 | Linux e redes |
| 3 | Segurança e OWASP |
| 4 | DevOps e CI/CD |
| 5 | SAST, SCA e Secret Scanning |
| 6 | DAST e IaC Security |
| 7 | Docker e containers |
| 8 | Cloud e IAM |
| 9 | Terraform e IaC |
| 10 | Kubernetes |
| 11 | Supply Chain Security e SBOM |
| 12 | Projeto DevSecOps completo |

“Período” pode representar uma semana, quinzena ou mês, dependendo da experiência e do tempo disponível. Evite promessas como “dominar DevSecOps em três meses”.

---

# 🔁 O verdadeiro roadmap

```text
APRENDER
   ↓
PRATICAR
   ↓
AUTOMATIZAR
   ↓
MONITORAR
   ↓
MELHORAR
   ↓
  🔁
```

> ## 💜 Roadmap não é checklist. Roadmap é direção.
>
> Você não precisa saber tudo para começar. Construa uma base, faça projetos, entenda os problemas, pratique a análise de vulnerabilidades e automatize o que fizer sentido.
>
> **Do código à segurança. 💻🔐**

---

## ✍️ Sobre este material

**Criado por Rha Kramer 💜**  
Desenvolvimento • DevSecOps • Carreira Tech

Material educacional para ajudar iniciantes a organizar os estudos em DevSecOps.

**Do código à segurança. 💻🔐**

---

## 👩🏼‍💻 Autora

<table>
  <tr>
    <td align="left">
      <a href="https://github.com/rhayssakramer">
        <strong>Rhayssa Kramer</strong>
      </a>
      <br>
      <span>Assoc, Full-Stack Development</span>
      <br>
      <small>Avanade | Tech Content Creator | Community Speaker</small>
    </td>
  </tr>
</table>

---

<div align="center">

### ⭐ Se este projeto foi útil, considere deixar uma estrela no GitHub!

© 2026 Rhayssa Kramer. Todos os direitos reservados.
