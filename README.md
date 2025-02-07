# Restaurante API

## Descrição
Este é um projeto de API para gestão de um restaurante, desenvolvido com **FastAPI** e executado com **Uvicorn**. A API permite a gestão de cardápio, pedidos e usuários, oferecendo um sistema rápido e eficiente para o gerenciamento de um restaurante.

## Tecnologias Utilizadas
- **FastAPI** - Framework web para construir APIs de alto desempenho.
- **Uvicorn** - Servidor ASGI para executar a aplicação FastAPI.
- **SQLite/PostgreSQL** - Banco de dados para armazenar informações.
- **SQLAlchemy** - ORM para interagir com o banco de dados.
- **Pydantic** - Validação e serialização de dados.

## Instalação
### 1. Clonar o repositório
```bash
git clone https://github.com/seu-usuario/restaurante-api.git
cd restaurante-api
```

### 2. Criar um ambiente virtual
```bash
python -m venv venv
source venv/bin/activate  # Para Linux/macOS
venv\Scripts\activate  # Para Windows
```

### 3. Instalar dependências
```bash
pip install -r requirements.txt
```

## Executando a API
### Modo de desenvolvimento
```bash
uvicorn main:app --reload
```
A API será iniciada em `http://127.0.0.1:8000`.



## Documentação Automática
A documentação interativa pode ser acessada via Swagger UI:
- `http://127.0.0.1:8000/docs`
- `http://127.0.0.1:8000/redoc`

## Contribuição
1. Fork o repositório
2. Crie um branch com sua feature (`git checkout -b minha-feature`)
3. Commit suas mudanças (`git commit -m 'Adicionando minha feature'`)
4. Push para o branch (`git push origin minha-feature`)
5. Abra um Pull Request


