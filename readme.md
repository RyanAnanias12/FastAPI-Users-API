# 🚀 FastAPI Project

Projeto backend utilizando **FastAPI** com arquitetura modular organizada por:

- Rotas
- Validações
- Servidor
- Ambiente virtual

---

# 📁 Estrutura do Projeto

```bash
project/
│
├── .vscode/
│   └── settings.json
│
├── src/
│   ├── __init__.py
│   │
│   └── main/
│       ├── __init__.py
│       │
│       ├── routes/
│       │   ├── __init__.py
│       │   └── users_routes.py
│       │
│       ├── server/
│       │   ├── __init__.py
│       │   └── server.py
│       │
│       ├── validators/
│       │   ├── __init__.py
│       │   └── user_register_validator.py
│       │
│       ├── __init__.py
│       └── __init__.py
│
├── venv/
│
├── requirements.txt
├── run.py
└── README.md
🛠 Tecnologias Utilizadas
Python 3.13
FastAPI
Uvicorn
Pydantic
⚙️ Configuração do Ambiente
1️⃣ Clonar o repositório
git clone <URL_DO_REPOSITORIO>
2️⃣ Entrar na pasta do projeto
cd project
3️⃣ Criar ambiente virtual
Windows
python -m venv venv
Linux / Mac
python3 -m venv venv
4️⃣ Ativar ambiente virtual
Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
5️⃣ Instalar dependências
pip install -r requirements.txt
▶️ Executando a Aplicação
python run.py

A API iniciará em:

http://0.0.0.0:3001
📚 Documentação Automática

O FastAPI gera documentação automática.

Swagger UI
http://127.0.0.1:3001/docs
ReDoc
http://127.0.0.1:3001/redoc
📌 Rotas da API
🔹 Health Check
Endpoint
GET /
Resposta
{
  "message": "API Running"
}
👤 Usuários
🔹 Registrar Usuário
Endpoint
POST /users/register
Body da Requisição
{
  "name": "João",
  "email": "joao@email.com",
  "password": "123456"
}
Resposta Esperada
{
  "message": "Usuário registrado com sucesso"
}