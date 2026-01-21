# 🚀 Grupo Netway – Time de Desenvolvimento

> 💡 Aqui é onde a infraestrutura do Grupo Netway encontra **código bem escrito**, **automação** e **dados em escala**.

<p align="center">
  <!-- Substitua por um gif/vídeo de demo interno se quiser -->
  <img src="https://media.giphy.com/media/Rkis28kMJd1aE/giphy.gif" alt="Tech animation" width="450">
</p>

---

## ✨ Propósito e Cultura

**Missão**  
Conectar pessoas e organizações com soluções digitais que **superam expectativas** e **eliminam barreiras**.

**Visão**  
Ser referência em **engenharia de software, dados e automação** no mercado de telecom e tecnologia.

**Valores**  
- Colaboração radical e **transparência por padrão**  
- Responsabilidade com dados e segurança  
- Aprendizado contínuo + feedback honesto  
- Autonomia com senso de dono  

---

## 🛠️ Stack Oficial do Time

<p align="center">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-38BDF8?style=for-the-badge&logo=react&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img alt="React Native" src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=white">
</p>

<p align="center">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-10AA50?style=for-the-badge&logo=mongodb&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
</p>

<p align="center">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img alt="GitLab" src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=white">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-1a1a1a?style=for-the-badge&logo=n8n&logoColor=white">
</p>

<p align="center">
  <img alt="Metabase" src="https://img.shields.io/badge/Metabase-1C3554?style=for-the-badge&logo=metabase&logoColor=white">
  <img alt="Power BI" src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img alt="Looker Studio" src="https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white">
  <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
  <img alt="VS Code" src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white">
</p>

---

## 📂 Ecossistema de Repositórios

| Repositório | Descrição                                      |
|------------|------------------------------------------------|
| `app-web`  | Portal web administrativo e de operação         |
| `api-core` | API principal do ecossistema Grupo Netway       |
| `infra`    | Infraestrutura como código (Terraform / IaC)    |
| `mobile`   | App mobile em React Native                      |
| `docs`     | Documentação central, padrões e playbooks       |

> 📌 Regra de ouro: **novo projeto = README claro + docs mínimas desde o dia 1**.

---

## 🔄 Workflow de Desenvolvimento

```mermaid
flowchart LR
  A[Issue / Demanda] --> B[Branch feature/...]
  B --> C[Dev & Testes locais]
  C --> D[Merge Request]
  D --> E[Code Review + CI/CD]
  E --> F[Merge em develop]
  F --> G[Release em main + Deploy]
```
1. Criar branch a partir de develop

```bash
git checkout develop
git pull origin develop
git checkout -b feature/minha-feature
```
2. Commits usando Conventional Commits
```text
feat(api): adiciona endpoint de contratos
fix(ui): corrige layout do dashboard financeiro
chore(ci): ajusta pipeline de testes e lint
```
3. Abrir MR/PR para develop

Incluir contexto da mudança

Prints/logs quando fizer sentido

Passos para teste manual

4. CI/CD

Lint, testes e build rodam automaticamente

5. Aprovação e merge

Aprovado → merge em develop

Releases gerenciadas a partir de main com versionamento semântico

👩‍💻 Onboarding de Devs
```bash
# 1. Clonar
git clone git@github.com:Grupo-Netway/<repo>.git
cd <repo>

# 2. Instalar dependências
npm install

# 3. Configurar variáveis de ambiente
cp .env.example .env

# 4. Subir ambiente local
npm run dev

# 5. Rodar testes
npm test
Se algo quebrar nesse fluxo, abra um issue ou fale no canal do time.
```
🧠 Recursos e Conhecimento
Wiki interna: http://kb.netway.inf.br/login

Padrão de commits: https://www.conventionalcommits.org/

Guia rápido de Markdown: https://www.markdownguide.org/basic-syntax/

👥 Time & Contato
Canais internos

Microsoft Teams: #Departamento de Tecnologia

E-mail: departamento.to@netway.inf.br

Responsáveis
Backend – [Alexandre Nogueira](https://github.com/Alxdelira)

FullStack – [Mateus de Moraes](https://github.com/MateussMoraes)

FullStack – [Aminah Makhoul](https://github.com/AminahMakhoul10)

Curte código limpo, automação até o limite e deploy sem drama? Você está no lugar certo.
