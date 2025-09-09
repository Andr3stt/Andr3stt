# ClickDesk - Sistema de Helpdesk Multiplataforma

**ClickDesk** é uma solução de **helpdesk** desenvolvida para empresas de pequeno e médio porte. Com foco em **simplicidade**, **acessibilidade** e **usabilidade**, o ClickDesk é um sistema centralizado para gerenciamento de solicitações, organização de chamados, e otimização do atendimento ao cliente.

---

## 🎯 **Desafio**

O **ClickDesk** surgiu para resolver problemas comuns enfrentados por empresas que não têm um sistema de helpdesk estruturado ou estão sobrecarregadas com múltiplos canais de comunicação (e-mails, WhatsApp, etc.), tais como:

- **Desorganização dos chamados**: Solicitações se perdem em múltiplos canais.
- **Falta de rastreabilidade**: Dificuldade em acompanhar o andamento dos chamados e histórico.
- **Baixa eficiência no atendimento**: Chamados repetidos, esquecidos ou mal priorizados.
- **Ausência de relatórios gerenciais**: Falta de dados para avaliar desempenho e gargalos.

---

## 💡 **Solução**

O **ClickDesk** oferece uma plataforma única e intuitiva para empresas gerenciarem todos os seus chamados em um só lugar. A solução inclui:

- **Centralização de Chamados**: Organiza todas as solicitações em um único painel.
- **Eficiência no Atendimento**: Otimiza o tempo de resposta e evita chamados duplicados.
- **Acompanhamento em Tempo Real**: Monitora o andamento de todos os chamados e tarefas.
- **Relatórios Gerenciais**: Oferece gráficos e relatórios de desempenho do time.
- **Acessibilidade**: Fácil de usar tanto para administradores quanto para funcionários.

---

## 📋 **Backlog do Produto**

### **Funcionalidades Principais**

| **Funcionalidade**                                | **Status**          | **Prioridade** | **Descrição** |
|---------------------------------------------------|---------------------|----------------|---------------|
| Sistema de login e registro de usuários           | Em Desenvolvimento  | Alta           | Permite a autenticação dos usuários para garantir segurança. |
| Sistema de rastreabilidade de chamados            | Pendente            | Alta           | Organiza chamados em tempo real e mantém um histórico detalhado. |
| Notificações em tempo real                        | Pendente            | Alta           | Alerta os usuários sobre novos chamados e atualizações. |
| Relatórios de desempenho                          | Pendente            | Média          | Oferece gráficos e relatórios de desempenho do time. |

---

## 🏃‍ **Cronograma de Sprints**

O cronograma das sprints será acompanhado através dos seguintes links. Clique nos links abaixo para acompanhar o progresso de cada sprint:

- **[Sprint 1 - 01/10 a 15/10](https://link-do-sprint-1)**: Implementação da interface de login e sistema de autenticação.
- **[Sprint 2 - 16/10 a 30/10](https://link-do-sprint-2)**: Desenvolvimento do sistema de rastreabilidade e painel de chamados.
- **[Sprint 3 - 01/11 a 15/11](https://link-do-sprint-3)**: Implementação das notificações em tempo real e funcionalidades de relatórios.

---

## 💻 **Tecnologias**

### **Backend**:

- **C#**: Linguagem principal para o desenvolvimento da API.
- **SQL Server**: Sistema de gerenciamento do banco de dados.
- **ASP.NET Core**: Framework para o desenvolvimento da API.
- **SignalR**: Para notificações em tempo real.

### **Frontend**:

- **React**: Biblioteca JavaScript para construção da interface web.
- **Next.js**: Framework React para construção da aplicação web.
- **Tailwind CSS**: Framework CSS para estilização da interface.

### **Desktop**:

- **Electron**: Framework para construção de aplicações desktop com tecnologias web.

### **Mobile**:

- **React Native**: Framework para criação de aplicativos móveis.

---

## 📖 **Manual de Instalação e Execução**

### **Pré-requisitos**

Antes de iniciar, certifique-se de ter os seguintes requisitos instalados:

- **Node.js** (versão 16+): Para execução do código frontend.
- **Git**: Para clonar o repositório.
- **SQL Server**: Para rodar o banco de dados local.
- **Yarn ou NPM**: Gerenciador de pacotes.

### **Instalação**

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/ClickDesk.git
   cd ClickDesk
Instale as dependências:

Para o frontend:

bash
Copiar código
cd apps/web
npm install
Para o backend:

bash
Copiar código
cd backend
dotnet restore
dotnet build
Configuração do Banco de Dados:

Crie um banco de dados no SQL Server e configure a string de conexão no arquivo .env.

Executando a Aplicação:

Para Web:

bash
Copiar código
cd apps/web
npm run dev
Para Desktop:

bash
Copiar código
cd apps/desktop
npm start
Para Mobile:

bash
Copiar código
cd apps/mobile
npm run android  # ou npm run ios para iOS
🧑‍🤝‍🧑 Equipe
Membro	Função	GitHub/LinkedIn
André Barbosa	Líder do Projeto / Product Owner	GitHub
Erika Cordeiro	Desenvolvedora Desktop / Scrum Master	LinkedIn
Vinicius Fagundes	Desenvolvedor Mobile/Web	GitHub
Kaique Uchoa	Desenvolvedor Desktop/Mobile	LinkedIn

📝 Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

🔧 Como Contribuir
Fork o repositório.

Crie sua branch de feature (git checkout -b feature/nova-feature).

Commit suas mudanças (git commit -m 'Adiciona nova feature').

Push para a branch (git push origin feature/nova-feature).

Abra uma pull request.

🎓 Documentação Completa
Para mais detalhes sobre a arquitetura, funcionamento e implementação do sistema, consulte a documentação completa do projeto no Wiki do GitHub.

