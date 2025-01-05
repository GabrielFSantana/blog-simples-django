# Blog Simples com Django

Este é um projeto básico de blog desenvolvido em Python usando o framework Django. O blog permite criar, visualizar, editar e excluir postagens.

## Funcionalidades

- Listar postagens.
- Visualizar o conteúdo de uma postagem específica.
- Criar novas postagens.
- Editar postagens existentes.
- Excluir postagens.

## Tecnologias Utilizadas

- Python 3.10+
- Django 5.1
- Banco de dados SQLite

## Como Configurar e Executar o Projeto

### Pré-requisitos

Certifique-se de ter o seguinte instalado:

- Python 3.10 ou superior
- Gerenciador de pacotes `pip`
- Virtualenv (opcional)

### Passo a Passo

1. **Clone este repositório:**

   ```bash
   git clone https://github.com/seuusuario/blog-simples.git](https://github.com/GabrielFSantana/blog-simples-django
   cd blog-simples
   
2. **Crie e ative um ambiente virtual (opcional):**


python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

3. **Instale as dependências:**

pip install -r requirements.txt

4. **Aplique as migrações ao banco de dados:**

python manage.py migrate

5. **Inicie o servidor de desenvolvimento:**

python manage.py runserver

6. **Acesse no navegador:**

Vá para http://127.0.0.1:8000/
