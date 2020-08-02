# Dominando o Active Jobs do rails

Mini curso de active-jobs ministrado pela [onebitcode.com](https://www.onebitcode.com).

Ferramentas utilizadas:

* Ruby on Rails

* Sqlite3

* Redis

* Sidekiq

Para rodar o projeto basta:

* instalar o redis na sua maquina(geralmente usando docker).

* rodar o comando bundle install para instalar as gems: 

```sh
bundle install
```

* logo em seguida subir o projeto:

```sh
rails server
```

* subir o servidor do redis (caso tenha subido um docker separado nem será preciso desse comando):

```sh
redis-server
```

* e por fim subir o sidekiq:

```sh
bundle exec sidekiq -q reports -c 3
```

e bons estudos!