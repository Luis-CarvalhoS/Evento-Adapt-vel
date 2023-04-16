Projeto de Criação e Cadastro de Eventos 🎉📅
Este projeto consiste em um site para criação e cadastro de eventos. Foi desenvolvido utilizando  Python 🐍(Django), HTML e css.

_Funcionalidades_ 🚀

O projeto possui as seguintes funcionalidades:

Cadastro de usuários 👤

Login e autenticação de usuários 🔐

Criação de eventos 📝

Edição de eventos ✏️

Listagem de eventos 📋

Visualização de detalhes dos eventos 🤔

Busca por eventos 🔍

Como utilizar o projeto 🛠️

Para utilizar o projeto, siga os seguintes passos:

Clone o repositório 📂
Certifique-se de que possui o Django instalado em sua máquina. Caso não possua, execute o seguinte comando no terminal: 💻
Copy code

pip install django

Acesse a pasta do projeto através do terminal e execute o comando a seguir para criar o banco de dados: 💾

python manage.py migrate

Crie um superusuário para acessar a área administrativa do site: 

python manage.py createsuperuser

Execute o comando abaixo para iniciar o servidor local: 

python manage.py runserver

Acesse o site em seu navegador, digitando o seguinte endereço na barra de endereços: 🔍
http://localhost:8000/

Estrutura do Projeto 📁
O projeto possui a seguinte estrutura de arquivos:

cliente/ 🧑‍💼
Arquivos do aplicativo "cliente"

eventos/ 📅
Arquivos do aplicativo "eventos"

templates/ 📝
Templates HTML do site

type_event/ 📊
Arquivos do aplicativo "type_event"

usuarios/ 👤
Arquivos do aplicativo "usuarios"

venv/ 🐍
Virtual environment do Python

db.sqlite3 💾
Banco de dados SQLite3 utilizado no projeto

manage.py 🛠️



Contribuições 🤝
Contribuições são bem-vindas! Sinta-se à vontade para enviar um pull request ou relatar qualquer problema encontrado no projeto. Vamos juntos tornar essa experiência ainda melhor! 🤜🤛
