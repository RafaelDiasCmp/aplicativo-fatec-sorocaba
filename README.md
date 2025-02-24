#  Aplicativo Acadêmico - FATEC Sorocaba

###  Um projeto desenvolvido por alunos da FATEC Sorocaba para facilitar o acesso a informações acadêmicas, comunicação e organização dentro da instituição.

## 📖 Sobre o Projeto

O Aplicativo Acadêmico da FATEC Sorocaba** é uma plataforma web e mobile desenvolvida para facilitar a vida dos estudantes, professores e administrativos, centralizando serviços essenciais em um único ambiente.

## Resumo: Aplicativo Acadêmico - FATEC Sorocaba.

O Aplicativo FATEC Sorocaba centraliza a gestão acadêmica, oferecendo funcionalidades essenciais: acesso a notas e horários (via SIGA), chatbot para dúvidas frequentes, notificações push e painel administrativo para comunicação institucional. Alunos acessam estágios, cardápio da cantina e monitoria. A versão inicial prioriza integração com sistemas existentes (SIGA) e responsividade.


##  Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Chatbot (Rasa)](https://img.shields.io/badge/Chatbot-Rasa-5C2D91?style=for-the-badge)

---

###  Objetivos do Projeto
- Fornecer acesso fácil às notas, horários de aula e comunicados acadêmicos.
- Criar um chatbot inteligente para responder dúvidas frequentes.
- Permitir que professores gerenciem turmas, lancem notas e disponibilizem materiais.
- Oferecer um painel administrativo para comunicação eficiente entre a instituição e os alunos.
- Disponibilizar um sistema de monitoria para alunos, organizando datas, matérias e monitores.
- Criar um espaço para a cantina, com acesso ao cardápio e valores.
- Implementar três tipos de perfil: Aluno, Professor e Administrador, com permissões específicas.
- Desenvolver um sistema organizado de vagas de estágio, permitindo que professores publiquem oportunidades de forma estruturada.

---

##  Funcionalidades Principais

- Consulta de notas e frequência (Integração com SIGA/FATEC)
- Horário de aulas e agenda acadêmica
- Download de materiais de aula (apostilas, slides, exercícios)
- Envio de notificações push para avisos importantes
- Painel para professores com lançamento de notas e envio de materiais
- Chatbot acadêmico para dúvidas frequentes
- Publicação de eventos e comunicados pela administração
- Sistema responsivo para acesso via mobile e desktop
- Cardápio da cantina atualizado diariamente
- Sistema de monitoria com horários, matérias e responsáveis
- Gestão de vagas de estágio, organizadas por professores
- Três tipos de perfil: Aluno, Professor e Administrador
---
##  Perfil: Aluno 
Para estudantes da FATEC Sorocaba  
 Funcionalidades: 
- Visualizar notas, frequência e histórico acadêmico (integração com SIGA).  
- Acessar horários de aula atualizados e calendário de provas.  
- Baixar materiais de estudo.  
- Receber notificações sobre prazos, eventos e comunicados.  
- Consultar o cardápio da cantina.  
- Buscar vagas de estágio publicadas por professores.  
- Interagir com o *Chatbot* para tirar dúvidas sobre:  

---

##  Perfil: Professor
Para docentes e coordenadores  
 Funcionalidades: 
- Lançar notas e registrar frequência das turmas.  
- Disponibilizar materiais de aula.  
- Gerenciar avisos e tarefas para cada disciplina.  
- Publicar vagas de estágio em parceria com empresas.  
- Visualizar agenda de aulas e eventos institucionais.    

---

##  Perfil: Administrador
Para equipe técnica e gestão da FATEC  
 Funcionalidades:
- Gerenciar usuários (ativar/desativar contas, redefinir senhas).  
- Publicar eventos acadêmicos, editais e comunicados oficiais.  
- Configurar integração com sistemas internos (SIGA, servidores). 
- Moderar conteúdo publicado no mural do aplicativo.  
- Gerenciar permissões de acesso para professores

## Estrutura do Projeto

```
📂 fatec-academico-app
│── 📁 backend          # Código da API em Python (Flask/Django)
│── 📁 frontend         # Aplicação Web (HTML, CSS, TypeScript, Bootstrap)
│── 📁 chatbot         # Implementação do chatbot (Rasa/Dialogflow)
│── 📁 database        # Scripts SQL para criação do banco de dados MySQL
│── 📁 docs            # Documentação do projeto
│── 📄 README.md       # Documentação inicial
```

---

##  Como Executar o Projeto

###  Configuração do Backend (API em Python)
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/fatec-academico-app.git
cd fatec-academico-app/backend

# Crie um ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute a API
python app.py
```

###  Configuração do Frontend (Web App)
```bash
cd fatec-academico-app/frontend

# Instale as dependências
npm install

# Inicie o servidor
npm start
```

###  Configuração do Chatbot
```bash
cd fatec-academico-app/chatbot

# Instale as dependências do Rasa
pip install rasa

# Treine o modelo
rasa train

# Inicie o chatbot
rasa shell
```

---
##  Diagramas: 
  Caso de uso:

![image](https://github.com/user-attachments/assets/0217b599-b86c-499f-89df-2e01139d5f06)

![image](https://github.com/user-attachments/assets/35f02134-da5e-450c-90e1-383ff70ab203)

![image](https://github.com/user-attachments/assets/790c49ad-384b-429b-b1a3-29c8b56ccacd)


## 📜 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

📌 Feito com ❤️ por alunos da **FATEC Sorocaba**
