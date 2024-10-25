Jogoteca

Este é um projeto de aplicação web chamado Jogoteca que gerencia jogos e usuários, permitindo o cadastro, a edição e a visualização de informações sobre diferentes jogos. A aplicação foi desenvolvida usando o framework Flask e utiliza uma combinação de bibliotecas para gerenciamento de banco de dados, autenticação de usuário, e interface web.

Tecnologias Utilizadas:

Backend:

Flask 3.0.2: Um micro-framework para Python, utilizado para construir aplicações web rápidas e escaláveis.
Flask-SQLAlchemy 3.0.3: Integração do SQLAlchemy com Flask para facilitar a manipulação de bancos de dados relacionais.
Flask-Bcrypt 1.0.1: Usado para hash de senhas, proporcionando maior segurança para dados de login de usuários.
Flask-Login 0.6.3: Gerenciamento de autenticação de usuários, permitindo sessões seguras e protegendo rotas da aplicação.
Flask-WTF 1.2.1: Extensão que facilita a criação e validação de formulários no Flask.

Banco de Dados:

MySQL Connector/Python 8.0.28: Conector utilizado para interagir com o banco de dados MySQL.
MySQLclient 2.2.4: Biblioteca cliente para conexão com o MySQL.
SQLAlchemy 2.0.27: Ferramenta de ORM (Object-Relational Mapping) que facilita as operações de banco de dados sem a necessidade de usar SQL diretamente.
Segurança e Formulários
bcrypt 4.1.2: Biblioteca para criptografia de senhas.
WTForms 3.1.2: Biblioteca usada para criação de formulários seguros e com validação simplificada.

Outras Dependências:

Werkzeug 3.0.4: Biblioteca WSGI utilizada internamente pelo Flask para manipulação de requisições HTTP.
Jinja2 3.1.2: Usado para renderizar templates HTML de forma dinâmica.
itsdangerous 2.1.2: Ferramenta para assinatura segura de dados, garantindo que informações de sessão e cookies estejam protegidos.
typing_extensions 4.9.0 e zipp 3.20.2: Dependências adicionais para compatibilidade com versões específicas de Python.

Outras Ferramentas de Desenvolvimento:

click 8.1.7: Ferramenta que auxilia na criação de interfaces de linha de comando.
colorama 0.4.6: Utilizada para formatação de texto com cores na linha de comando em ambientes Windows.

Instalação e Configuração
Clone este repositório:


git clone https://github.com/seu-usuario/jogoteca.git
cd jogoteca

Crie e ative o ambiente virtual:

python -m venv .venv
source .venv/bin/activate  # Para Linux e macOS
.venv\Scripts\activate     # Para Windows

Instale as dependências:

pip install -r requirements.txt
Configure o banco de dados MySQL e ajuste as configurações de conexão no arquivo de configuração da aplicação.

Execute o script de criação de banco de dados para configurar as tabelas iniciais.

Inicie a aplicação:

flask run
