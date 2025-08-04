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

## 📸 Demonstrações da Aplicação

### ▶️ Vídeos de Funcionamento

- [Vídeo 1 de funcionamento](https://github.com/user-attachments/assets/28445754-05c7-4e50-ae46-b0d36d437d40)
- [Vídeo 2 de funcionamento](https://github.com/user-attachments/assets/8339c812-5f1d-410e-9197-7f76982645f8)

---

### 📷 Capturas de Tela

**Cadastro de Usuários**  
![Cadastro de usuários](https://github.com/user-attachments/assets/3416dcfa-b01d-44af-a406-693b23530278)

**Login Realizado com Sucesso**  
![Login realizado](https://github.com/user-attachments/assets/bd2f399b-c1a0-432c-b492-eaeb5994b96d)

**Tela Inicial da Aplicação**  
![Tela inicial](https://github.com/user-attachments/assets/88feb430-eeed-4c59-b91f-7c99c30fa357)

**Perfil de Usuário**  
![Usuário](https://github.com/user-attachments/assets/5adaa6a0-44fb-4a47-b24f-57bcb7335605)

**Usuário com Imagem**  
![Usuário com imagem](https://github.com/user-attachments/assets/dde86cc2-cb47-4660-bca2-a3b58a32416e)


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



