# Bootcamp QA


img src ="![alt text](<Imagens/Logo tripleten.jpeg>)"



# 🟢 Sprint 1 – Fundamentos de QA

## 🎯 Objetivo do Projeto
Introduzir os conceitos de QA, entender o papel do analista de testes, as etapas do desenvolvimento de software e como realizar os primeiros testes manuais.

## ⚙️ Funcionalidades
- Explicação sobre testes de software  
- Diferença entre hard skills e soft skills em QA  
- Ciclo de desenvolvimento de software  
- Testes em pequenas tarefas  

## 🛠️ Tecnologias Utilizadas
- Documentação (Google Docs, Notion ou Trello)  
- Fluxogramas para etapas do processo  
- Ferramentas de organização de tarefas (Trello/Jira)  

## ▶️ Instruções de Execução
Este sprint é teórico/prático, não há execução em código.  
Para praticar:  
1. Crie um checklist de validação de uma funcionalidade simples.  
2. Documente erros encontrados em planilha ou ferramenta de gerenciamento.  

### Sprint 2
# 🟢 Sprint 2 – Requisitos e Projeto de Teste

## 🎯 Objetivo do Projeto
Aprender a analisar requisitos de software, criar casos de teste/documentação e entender a diferença entre testes funcionais e não funcionais.

## ⚙️ Funcionalidades
- Análise de requisitos de um sistema  
- Criação de casos de teste e cenários  
- Documentação de teste em planilhas  
- Identificação de áreas cinzentas  

## 🛠️ Tecnologias Utilizadas
- Google Docs/Excel  
- TestRail (ou ferramenta similar)  
- Jira ou Trello para requisitos  

## ▶️ Instruções de Execução
1. Analise requisitos de um sistema fictício (ex.: cadastro de usuário).  
2. Documente casos de teste (positivo, negativo, campos obrigatórios).  
3. Registre cenários em planilha ou no Jira.  

# 🟢 Sprint 3 – Testes em Aplicações Web

## 🎯 Objetivo do Projeto
Realizar testes em aplicações web, validar interfaces, compatibilidade entre navegadores e design responsivo.

## ⚙️ Funcionalidades
- Testes de UI em navegadores  
- Testes cross-browser (Chrome/Firefox/Edge)  
- Testes de design responsivo (desktop, tablet, mobile)  

## 🛠️ Tecnologias Utilizadas
- Chrome DevTools  
- Firefox Developer Tools  
- Responsively App  

## ▶️ Instruções de Execução
1. Escolha uma aplicação web para teste (ex.: formulário de cadastro).  
2. Valide layout e campos em diferentes navegadores.  
3. Use a ferramenta Responsively para verificar o design responsivo.  

# 🟢 Sprint 4 – Testes de API

## 🎯 Objetivo do Projeto
Aprender a criar, enviar e validar requisições em APIs REST usando diferentes ferramentas.

## ⚙️ Funcionalidades
- Criação de coleções no Postman  
- Testes GET, POST, PUT e DELETE  
- Documentação de API com Swagger/Apidoc  
- Uso de cURL para requisições  

## 🛠️ Tecnologias Utilizadas
- Postman  
- Swagger  
- Apidoc  
- cURL  

## ▶️ Instruções de Execução
1. Importe a coleção no Postman.  
2. Execute as requisições e valide respostas (status code, body, headers).  
3. Documente os testes no Swagger.  

# 🟢 Sprint 5 – Testes Mobile

## 🎯 Objetivo do Projeto
Executar testes em aplicativos móveis, tanto em emuladores quanto em dispositivos reais.

## ⚙️ Funcionalidades
- Teste de interface mobile  
- Validação de desempenho em diferentes dispositivos  
- Testes em emulador e celular físico  

## 🛠️ Tecnologias Utilizadas
- Android Studio (emulador)  
- Genymotion  
- Appium (se aplicável)  

## ▶️ Instruções de Execução
1. Configure um emulador Android no Android Studio.  
2. Execute o app fictício e realize testes manuais.  
3. Valide a execução em um dispositivo físico.  


# 🟢 Sprint 6 – Banco de Dados e SQL

## 🎯 Objetivo do Projeto
Aprender conceitos básicos de banco de dados e realizar consultas SQL para validar informações do sistema.

## ⚙️ Funcionalidades
- Criação de tabelas  
- Inserção e consulta de dados  
- Relações entre tabelas  

## 🛠️ Tecnologias Utilizadas
- MySQL ou PostgreSQL  
- SQLite  
- DBeaver  

## ▶️ Instruções de Execução
1. Crie um banco de dados com tabela de usuários.  
2. Insira dados fictícios.  
3. Faça consultas para validar informações de cadastro.  

# 🟢 Sprint 7 – Fundamentos de Automação

## 🎯 Objetivo do Projeto
Introduzir automação de testes utilizando Python, conceitos básicos de programação e versionamento de código.

## ⚙️ Funcionalidades
- Estruturas básicas em Python  
- Criação de scripts simples  
- Uso do Pytest para testes automatizados  
- Versionamento com GitHub  

## 🛠️ Tecnologias Utilizadas
- Python  
- PyCharm  
- Pytest  
- Git e GitHub  

# 🟢 Sprint 8 – Automação de Testes Web

## 🎯 Objetivo do Projeto
Desenvolver scripts de automação para aplicações web utilizando **Selenium WebDriver** em conjunto com **Python e Pytest**.  
O projeto foca em aplicar o padrão **Page Object Model (POM)** para estruturar os testes de forma clara e escalável.

## ⚙️ Funcionalidades
- ✅ Abertura e fechamento automático do navegador  
- ✅ Automação do fluxo de login (válido e inválido)  
- ✅ Localização de elementos por ID, XPATH e CSS Selector  
- ✅ Estrutura baseada no padrão Page Object Model (POM)  
- ✅ Geração de relatórios em HTML após execução dos testes  

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3.10  
- **Automação Web:** Selenium WebDriver  
- **Framework de Teste:** Pytest  
- **Relatórios:** pytest-html  
- **Controle de Versão:** Git e GitHub  

## 📂 Estrutura do Projeto
```bash
├── tests/                  # Casos de teste
│   ├── test_login.py       # Testes de login
│   └── conftest.py         # Configurações globais
├── pages/                  # Page Objects (POM)
│   └── login_page.py       # Classe com elementos e ações da tela de login
├── reports/                # Relatórios de execução
├── requirements.txt        # Dependências do projeto
└── README.md               # Documentação


### Conclusão
O bootcamp me trouxe uma opção bem estruturada para iniciar na carreira de Quality Assurce,todos os recursos são voltados para testes de mercados reais com construção em um bom perfil profissional,assim como a abordagem de soft skill essesciais como gerenciamento de tempo, trabalho em equipe e comunicação, que são cruciais para poder atuar nessa área.




