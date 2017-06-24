To start:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.


Some weird Crypto Rand Bytes error: try this after putting {:plug, "~> 1.0"} in the mix.exs file:
mix deps.update --all
