# Acessando o banco de dados para fins de teste.

Fala pessoal, de uns tempos para cá algumas pessoas me abordam com a seguinte dúvida: "É possível persistir os dados no banco de dados?" e a resposta é sim, é possível realizar qualque ação no BD, desde consulta até deleção. Bem, eu vou falar um pouco de uma gem chamada [sequel](https://github.com/jeremyevans/sequel) que executa bem esse papel.

Mas não é assim tão fácil de configurar um ambiente para essa gem, ou seja, não adianta sair dando "gem install sequel" que não vai funcionar. Para que a instalção faça sentido, vamos precisar dos pré requisitos:

```ruby
Instalar:
- PostgresSQL = sudo apt-get install postgresql
- Phyton = sudo apt-get install python-psycopg2
- Libs = sudo apt-get install libpq-dev
```
E vamos precisar das seguintes gems instaladas:

```ruby
Obs.: Sabe que o ideal é colocar no Gemfile certo??

gem install pg
gem install sequel
gem install sqlite3
```