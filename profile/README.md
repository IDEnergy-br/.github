# 🌞 ID Energy – Sistema de Gestão de Energia Fotovoltaica

Este é um sistema web desenvolvido para otimizar a gestão de dados de faturas de energia elétrica e substituir o uso de planilhas.  
A plataforma permite **cadastrar clientes, processar dados de consumo e geração, gerenciar créditos e tarifas**, além de gerar **relatórios e dashboards visuais** para tomada de decisão.

---

## 🚀 Objetivo do Projeto
Atualmente, a gestão é feita com planilhas extensas e suscetíveis a erros.  
Com este sistema buscamos:

- 📊 Centralizar e organizar os dados em uma única plataforma.  
- ⚡ Automatizar o lançamento e processamento de faturas.  
- 📈 Disponibilizar relatórios detalhados e dashboards.  
- 🔒 Oferecer controle de acessos por tipo de usuário.  
- ☀️ Apoiar clientes e equipe ID Energy no acompanhamento da geração e consumo de energia.  

---

## 🛠️ Tecnologias Utilizadas
- **Frontend** → React + Vite + CSS  
- **Backend** → Node.js + Prisma  
- **Banco de Dados** → PostgreSQL  

---

## 📂 Estrutura do Sistema
Módulos principais:  
- 👥 **Clientes**: divisões, uniões, associações, unidades, usinas e beneficiárias.  
- 📑 **Lançamentos**: consumo, geração, tarifas e bandeiras tarifárias.  
- 📊 **Relatórios**: exportação em PDF e dashboards dinâmicos.  
- 💡 **Faturas**: registros mensais detalhados.  
- 🔐 **Gestão de Acessos**: permissões para administradores e clientes.  

---

## 👩‍💻 Público-Alvo
- **Equipe da ID Energy** → operação, consultoria e manutenção.  
- **Clientes** → acompanhamento do desempenho energético.  

---

## 📌 Status do Projeto

### 🔧 Backend
- [x] Definição da stack (Node.js + Prisma + PostgreSQL)
- [x] Configuração inicial do projeto Node.js
- [x] Conexão com banco de dados via Prisma
- [x] Criação do schema inicial no Prisma
- [ ] Implementação das migrations completas
- [ ] Desenvolvimento dos endpoints REST (CRUD clientes, lançamentos, relatórios)
- [ ] Middleware de autenticação e controle de acessos
- [ ] Integração com geração de relatórios (PDF/Dashboard)

### 🎨 Frontend
- [x] Definição da stack (React + Vite + CSS puro)
- [x] Estrutura base de pastas e componentes
- [x] Layout inicial (Header, Sidebar, Layout padrão)
- [x] Tela de Login
- [ ] Módulo de Clientes (Divisão, União, Associação, Unidade, Usina, Beneficiária)
- [ ] Módulo de Lançamentos (Consumo, Geração, Tarifas, Bandeiras)
- [ ] Módulo de Relatórios (Dashboard + Exportação PDF)
- [ ] Tela de Faturas

### 🗄️ Banco de Dados
- [x] Modelagem inicial de usuários, permissões e cadastros hierárquicos
- [x] Modelagem das tabelas de consumo, geração, tarifas, créditos e bandeiras
- [ ] Modelagem avançada (dados técnicos, históricos e regras tarifárias complexas)
- [ ] Otimização de queries e índices
- [ ] Testes de consistência e integridade referencial

### 🔐 Segurança & Acessos
- [x] Sistema de login com JWT
- [ ] Controle de permissões por perfil (master admin, admin funcionário, cliente)
- [ ] Criptografia de senhas (bcrypt)
- [ ] Logs de auditoria (ações do usuário)

### 📊 Relatórios e Dashboards
- [ ] Definição de indicadores principais
- [ ] Protótipo de dashboard em React
- [ ] Exportação de relatórios em PDF
- [ ] Filtros avançados (período, unidade, distribuidora, etc.)

### 📦 Infraestrutura & Deploy
- [ ] Configuração de ambiente de desenvolvimento
- [ ] Configuração de ambiente de testes
- [ ] Preparação para deploy (Docker)
- [ ] CI/CD (GitHub Actions)

---

## 📄 Licença
Este projeto é de uso **interno** da **ID Energy br**.
