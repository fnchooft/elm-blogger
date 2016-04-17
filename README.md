# elm-blogger

A blogging platform written in Elm + Elixir

## Phoenix Info

To start the app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
    * You may need to create a role in postgres for the DB user:
    * `$ psql`
    * `=# CREATE ROLE postgres LOGIN CREATEDB;`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.
