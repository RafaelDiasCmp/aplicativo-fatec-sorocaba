# 📌 Aplicativo Acadêmico - FATEC Sorocaba

### 📚 Um projeto desenvolvido por alunos da FATEC Sorocaba para facilitar o acesso a informações acadêmicas, comunicação e organização dentro da instituição.

---

## 🚀 Tecnologias Utilizadas

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

## 📖 Sobre o Projeto

O **Aplicativo Acadêmico da FATEC Sorocaba** é uma plataforma web e mobile desenvolvida para facilitar a vida dos estudantes, professores e administrativos, centralizando serviços essenciais em um único ambiente.

### 🎯 Objetivos do Projeto
Fornecer acesso fácil às notas, horários de aula e comunicados acadêmicos.
Criar um chatbot inteligente para responder dúvidas frequentes.
Permitir que professores gerenciem turmas, lancem notas e disponibilizem materiais.
Oferecer um painel administrativo para comunicação eficiente entre a instituição e os alunos.
Disponibilizar um sistema de monitoria para alunos, organizando datas, matérias e monitores.
Criar um espaço para a cantina, com acesso ao cardápio e valores.
Implementar três tipos de perfil: Aluno, Professor e Administrador, com permissões específicas.
Desenvolver um sistema organizado de vagas de estágio, permitindo que professores publiquem oportunidades de forma estruturada.

---

## 📌 Funcionalidades Principais

✅ Consulta de **notas e frequência** (Integração com SIGA/FATEC)  
✅ **Horário de aulas** e agenda acadêmica  
✅ Download de **materiais de aula** (apostilas, slides, exercícios)  
✅ Envio de **notificações push** para avisos importantes  
✅ **Painel para professores** com lançamento de notas e envio de materiais  
✅ **Chatbot acadêmico** para dúvidas frequentes  
✅ **Publicação de eventos** e comunicados pela administração  
✅ **Sistema responsivo** para acesso via mobile e desktop  

---

## 🛠️ Estrutura do Projeto

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

## 🎯 Como Contribuir

1. **Faça um fork** deste repositório.
2. **Crie uma branch** com sua feature: `git checkout -b minha-feature`
3. **Commit suas alterações**: `git commit -m 'Adicionando nova funcionalidade'`
4. **Faça um push** para a branch: `git push origin minha-feature`
5. **Abra um Pull Request**

---

## 📥 Como Executar o Projeto

### 1️⃣ Configuração do Backend (API em Python)
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

### 2️⃣ Configuração do Frontend (Web App)
```bash
cd fatec-academico-app/frontend

# Instale as dependências
npm install

# Inicie o servidor
npm start
```

### 3️⃣ Configuração do Chatbot
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

## 📜 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

📌 Feito com ❤️ por alunos da **FATEC Sorocaba**
