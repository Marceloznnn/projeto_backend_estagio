# SUAP IFMA - Clone de Interface de Login

Repositório: [Marceloznnn/Suap](https://github.com/Marceloznnn/Suap.git)

Este projeto é um clone do design da página de login do SUAP IFMA ([original](https://suap.ifma.edu.br/accounts/login/?next=/)), desenvolvido com Flask (backend) e HTML/CSS (frontend). O objetivo é reproduzir fielmente a experiência visual e de navegação do SUAP, servindo como estudo de front-end e integração básica com back-end.

## Demonstração

Adicione aqui um print da tela de login para ilustrar o projeto.

---

## Estrutura do Projeto

```
projeto_flask_backend/
│
├── backend/
│   ├── run.py
│   └── app/
│       ├── __init__.py
│       ├── routes/
│       │   ├── __init__.py
│       │   ├── login.py
│       │   └── esqueci_senha.py
│       ├── templates/
│       │   ├── login.html
│       │   └── esqueci_senha.html
│       └── static/
│           └── style.css
│
├── frontend/ (não é mais usada, CSS foi movido para static)
│
└── README.md
```

---

## Como rodar o projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/Marceloznnn/Suap.git
   cd Suap/backend
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado):**

   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Instale as dependências:**

   ```bash
   pip install flask
   ```

4. **Inicie o servidor Flask:**

   ```bash
   python run.py
   ```

5. **Acesse no navegador:**
   ```
   http://127.0.0.1:5000/
   ```

---

## Login de Teste

Para acessar com sucesso, utilize as seguintes credenciais:

- **E-mail:** `estagio@gmail.com`
- **Senha:** `estagio2025`

Se usar outros dados, receberá a mensagem de erro "E-mail ou senha incorretos."

---

## Funcionalidades

- Interface de login fiel ao SUAP IFMA, responsiva e moderna.
- Mensagens de erro e sucesso no login.
- Página de "Esqueci minha senha" com validação de e-mail.
- Botão de login com Gov.br (apenas visual).
- Estrutura pronta para expansão de funcionalidades.

---

## Tecnologias Utilizadas

- Python 3.x
- Flask
- HTML5
- CSS3

---

## Observações

- O projeto é apenas para fins educacionais e não possui integração real com banco de dados ou autenticação Gov.br.
- O CSS foi cuidadosamente ajustado para se aproximar do visual do SUAP IFMA.
- Imagens e logos podem ser adicionados na pasta `static/img` para maior fidelidade visual.

---

## Autor

- [Marceloznnn](https://github.com/Marceloznnn)

---
# Suap
