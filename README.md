Markdown

# ClickDesk

A **ClickDesk** é um sistema helpdesk multiplataforma (Web, Desktop e Mobile) desenvolvido com foco em simplicidade, acessibilidade e usabilidade. Inspirada em sistemas profissionais de suporte ao cliente, mas adaptada à realidade de empresas menores, ela funciona como um painel unificado de atendimento e gestão de solicitações.

O objetivo principal da ClickDesk é facilitar a gestão de chamados e processos internos, oferecendo às empresas:

- **Organização**: Centralizar pedidos, chamados e tarefas em um único sistema.
- **Eficiência**: Reduzir ruídos na comunicação e otimizar o tempo de resposta.
- **Controle**: Permitir acompanhamento em tempo real das demandas e relatórios para tomada de decisão.
- **Acessibilidade**: Garantir que tanto administradores quanto funcionários consigam utilizar a ferramenta sem complexidade.

---

## 🟢 Status do Projeto

[![Status](https://img.shields.io/badge/Status-Em%20Andamento-green)](https://www.youtube.com/shorts/bzwvZzVCDts)
[![Versão](https://img.shields.io/badge/Versão-1.0.0-blue)](https://www.youtube.com/watch?v=EwW-e9W8fwg)

O projeto ClickDesk está em fase de desenvolvimento ativo, com foco na implementação das funcionalidades principais e na integração entre as plataformas.

---

## 💡 O Desafio

A ClickDesk surgiu para resolver problemas comuns enfrentados por pequenas empresas e equipes que não possuem um sistema estruturado de helpdesk ou de comunicação interna, tais como:

- Desorganização dos chamados (solicitações se perdem em e-mails, WhatsApp ou bilhetes).
- Falta de rastreabilidade (dificuldade em acompanhar o andamento e histórico das solicitações).
- Baixa eficiência no atendimento (chamados repetidos, esquecidos ou mal priorizados).
- Carência de relatórios gerenciais (para avaliar desempenho, gargalos e melhorias).

---

## 🧑‍🤝‍🧑 Autores e Contribuidores

| Nome do Contribuidor | Função no Projeto | GitHub ou LinkedIn |
|----------------------|-------------------|--------------------|
| André Barbosa | Líder do Projeto/Product Owner | https://www.youtube.com/watch?v=vKY9N0tuz70 |
| Erika Cordeiro | Desenvolvedora Desktop/Scrum Master | https://www.facebook.com/public/Erica-Perfil/?locale=pt_BR |
| Vinicius Fagundes | Desenvolvedor Mobile/Web | https://www.transfermarkt.pt/vinicius-junior/profil/spieler/371998 |
| Kaique Uchoa | Desenvolvedor Desktop/Mobile | https://www.instagram.com/kaykysc10/?hl=en |

---

## 🗓️ Cronograma de Sprints

Acompanhe o planejamento e o andamento das nossas sprints, tarefas e objetivos em tempo real:
> **[Acesse nosso Cronograma de Sprints aqui](https://www.notion.com/pt/help/guides/sprints-simplified-notions-sprint-tracking-system)**

---

## 💻 Tecnologias

### Tecnologias Principais
- 🌐 **C#**: Linguagem principal para o backend da aplicação.
- 💾 **SQL Server**: Sistema de gerenciamento do banco de dados.
- 🌳 **Git**: Para controle de versão e colaboração.
- 📝 **HTML**, **CSS** e **JavaScript**: Linguagens fundamentais para o desenvolvimento web.

### Tecnologias por Plataforma
- **Web**:
  - ⚛️ **React**: Biblioteca para a interface da aplicação Web.
  - 🚀 **Next.js**: Framework para a aplicação Web.
  - 💅 **Tailwind CSS**: Framework CSS para estilização.
- **Desktop**:
  - 🖥️ **Electron**: Framework para construir aplicativos de desktop com tecnologias web.
- **Mobile**:
  - 📱 **React Native**: Framework para construir aplicativos mobile.

---

## 📁 Estrutura do Projeto

A arquitetura do projeto segue um modelo de monorepo, com cada plataforma em sua própria pasta, facilitando a gestão de código e dependências.

ClickDesk/
├── apps/
│   ├── web/        # Aplicação Web
│   ├── desktop/    # Aplicação Desktop
│   └── mobile/     # Aplicação Mobile
├── packages/       # Código compartilhado
│   ├── ui/
│   └── core/
├── .gitignore
├── package.json
└── README.md


---

## 🚀 Manual de Instalação e Execução

### Pré-requisitos
- **Node.js**: Versão mais recente.
- **Git**: Para clonar o repositório.
- **Yarn** ou **NPM**: Gerenciador de pacotes.

### Instalação
1. Clone o repositório do projeto:
   ```bash
   git clone [https://www.youtube.com/watch?v=GRf6so_sois](https://www.youtube.com/watch?v=GRf6so_sois)
Navegue até o diretório principal:

Bash

cd [nome-da-pasta-do-seu-projeto]
Instale as dependências:

Bash

npm install
Executando as Aplicações
Siga as instruções abaixo para iniciar cada versão da aplicação separadamente.

Versão Web

Bash

cd apps/web
npm run dev
Versão Desktop

Bash

cd apps/desktop
npm start
Versão Mobile

Bash

cd apps/mobile
npm run android # ou `npm run ios` para iOS
✨ Funcionalidades
Sistema completo de login e registro de usuários.

Sincronização de dados em tempo real entre todas as plataformas.

Painel de controle para criação, edição e exclusão de chamados.

Relatórios gerenciais e gráficos de desempenho.

Notificações em tempo real para novas solicitações.

📜 Backlog
[Este é o seu backlog de próximas funcionalidades e melhorias. Mantenha esta lista atualizada para que outros saibam o que está por vir.]

[ ] Sistema de priorização de chamados.

[ ] Módulo de chat em tempo real entre os usuários.

[ ] Funcionalidade de anexar arquivos aos chamados.

[ ] Criação de um dashboard administrativo com KPIs.

⚙️ Configuração
Para que a aplicação funcione corretamente, é necessário configurar as variáveis de ambiente.

Crie um arquivo .env na raiz do projeto.

Copie o conteúdo do .env.example e preencha as variáveis com suas informações:

Ini, TOML

# Variáveis de ambiente
API_URL=http://localhost:4000/api
DATABASE_CONNECTION_STRING=seu-sql-server-connection-string
📄 Licença
Este projeto está sob a licença [Nome da Licença, ex: MIT].


Aliás, para liberar as funcionalidades de todos os apps, ative a [Atividade nos apps do Gemini](https://myactivity.google.com/product/gemini).
