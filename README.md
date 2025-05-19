# 📅 Agenda Django

Este é um projeto de agenda desenvolvido com Django, permitindo o gerenciamento de contatos de forma simples e eficiente.

## 📋 Funcionalidades

- Cadastro de contatos com nome, e-mail e telefone
- Edição e exclusão de contatos
- Listagem de todos os contatos
- Interface amigável utilizando templates personalizados

## 🚀 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- HTML e CSS

## 📁 Estrutura do Projeto
```bash
agenda_django/
├── base_static/
│ └── global/
│ └── css/
├── base_templates/
│ └── global/
├── contact/
├── core/
├── utils/
├── manage.py
└── .gitignore
```
- `base_static/`: arquivos estáticos como CSS
- `base_templates/`: templates base do projeto
- `contact/`: app responsável pelo gerenciamento de contatos
- `core/`: configurações principais do projeto
- `utils/`: funções utilitárias usadas no projeto

  ## Demonstrações da Aplicação

| Vídeos de pesquisa | Vídeo de cadastro |
|:--:|:--:|
| https://github.com/user-attachments/assets/f3bf359f-1b2b-4e8e-b2d1-25b3a4399727 | 

✅ Cadastro e Autenticação

| Cadastro de usuários | Login com erro de autenticação |
|:--:|:--:|
|![cadastro_usuarios](https://github.com/user-attachments/assets/4ad50d6f-aa82-4000-a74a-ea6392879aa2) |![login_incorreto](https://github.com/user-attachments/assets/d7d8789f-2e86-4d6d-be83-6433e38a9b40)

| Autenticação bem-sucedida e acesso aos mentorados |
|:--:|
|![mentorados_auth](https://github.com/user-attachments/assets/e1d08469-6a1f-4258-a5f1-90ae2d0e40ba)

👨‍🏫 Gerenciamento de Mentorados
| Cadastro de mentorados | Tarefa - Mentor |
|:--:|:--:|
| ![cadastro_mentorados](https://github.com/user-attachments/assets/6d68dc8e-7a33-4141-88e5-0be8f05a69cf) |![tarefa_mentor](https://github.com/user-attachments/assets/403a3db1-8c42-4b49-b7ea-1f2bad5732ad)

| Tarefa - Mentorado |
|:--:|
|![tarefa_mentorado](https://github.com/user-attachments/assets/b9be1d5b-7f16-4f4e-afae-cf52887b6f09)

📅 Reuniões
| Escolher dia | Agendar reunião |
|:--:|:--:|
| ![escolher_dia](https://github.com/user-attachments/assets/f14d1e61-739a-4ce1-88ad-74b7a838c368) |![agendar_reuniao](https://github.com/user-attachments/assets/17fd8c68-fba8-450a-8f4b-94e357a13c2e)

| Reunião marcada |
|:--:|
| ![abrir_reuniao](https://github.com/user-attachments/assets/ed633973-5240-4a04-a265-b6fe619e2eeb)


## ⚙️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/brunabbelini/agenda_django.git
```

2. Acesse o diretório do projeto:
  ```bash
 cd agenda_django
```

3. Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

4. Instale as dependências:
```bash   
pip install -r requirements.txt
```

5. Aplique as migrações:
```bash   
python manage.py migrate
```

6. Execute o servidor de desenvolvimento:
```bash   
python manage.py runserver
```

7. Acesse no navegador:
```bash   
http://localhost:8000
```

## 📝 Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.



