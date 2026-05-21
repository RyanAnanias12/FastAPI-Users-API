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

📚 Documentação Automática

O FastAPI gera documentação automática.

Swagger UI
http://127.0.0.1:3001/docs
ReDoc
http://127.0.0.1:3001/redoc
