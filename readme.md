Coins-Summary-Manager

Aplicação que permite gerenciar usuários e adicionar ativos favoritos para cada usuário
E também mostra os valores diários de que ativo favorito por usuário.

Como rodar a aplicação:

1- Instale o pipeenv com esse comando:
pip install pipenv

2- Instale as dependencias do projeto com esse comando:
pipenv install

3 - Para iniciar o container docker com seu banco de dados use esse comando:
docker-compose up

4- Para criar as tabelas do banco use esse comando:
python database/init_db.py

Para rodar a aplicação utilizando o uvicorn use esse comando:
uvicorn main:app --port 8080 --reload

Acesse a documentação nessa url:
localhost:8080/docs

