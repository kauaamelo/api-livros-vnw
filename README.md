<h1>📚 API de Doação de Livros</h1>

<p>
  Uma API simples com <strong>Flask</strong> e <strong>SQLite</strong> para cadastro e listagem de livros doados. <br/>
  Projeto desenvolvido para fins educativos na <strong>Vai Na Web</strong>.
</p>

<p>
  <img src="https://img.shields.io/badge/python-3.10-blue?style=flat&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/flask-black?style=flat&logo=flask" alt="Flask">
  <img src="https://img.shields.io/badge/sqlite-003B57?style=flat&logo=sqlite" alt="SQLite">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-yellow" alt="Status">
</p>

---

## ✨ Preview

> Uma visão geral da API em ação:

<p align="center">
  [IMAGEM]
</p>

---

## 🚀 Como rodar o projeto

```bash
# 1. Clone o repositório
git clone <URL_DO_REPOSITORIO>
cd nome-do-projeto

# 2. Crie e ative o ambiente virtual
python -m venv venv
source venv/Scripts/activate     # Windows
# ou
source venv/bin/activate         # Linux/Mac

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Execute o app
python app.py
```

<h2>🔁 Endpoints</h2>
<p>📥 POST /doar
Cria um novo registro de livro doado.

📤 Exemplo de requisição:</p>
```json
{
  "titulo": "Codigo Limpo: Habilidades Praticas do Agile Software",
  "categoria": "Tecnologia",
  "autor": "Robert C. Martin",
  "image_url": "https://exemplo.com/livro.jpg"
}
```
<p>✅ Resposta (201):</p>

```json
{
  "mensagem": "Livro cadastrado com sucesso"
}
```

<p>📚 GET /livros
Retorna todos os livros cadastrados.

📥 Resposta (200):</p>
```json
[
  {
    "autor": "Aditya Y. Bhargava",
    "categoria": "Tecnologia",
    "id": 1,
    "image_url": "https://m.media-amazon.com/images/I/517I6z9QK4L._SY445_SX342_.jpg",
    "titulo": "Entendendo Algoritmos: Um Guia Ilustrado Para Programadores"
  }
]
```

<h2>⚙️ Tecnologias Usadas:</h2>

<p>Ferramenta	Descrição</p>
🐍 Python	Linguagem principal<br>
🌐 Flask	Microframework web<br>
💾 SQLite	Banco de dados local<br>
🔄 Flask-CORS	Middleware para CORS<br>
<br>

<p> Feito com ❤️ pela comunidade Vai Na Web </p>
