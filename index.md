---
layout: default
---

# [](#why)Why?

Is a command line interface written in ruby
that makes development easy in Phoenix Framework

# [](#install)Install

You can get it on gem installer.

```bash
gem install phoenix-cli
```

# [](#usage)Usage

Just type the commands in your terminal in the same directory as your Phoenix project

## Command List

| Command | Description | Phoenix equivalent |
| --- | --- | --- |
| install | Install Phoenix Framework | -
| new APP_PATH | Create new Phoenix application | mix phoenix.new
| deps | Install the Phoenix dependencies | mix deps.get
| server | Start the web server | mix phoenix.server
| console | Start Phoenix console | iex -S mix
| routes | Show Phoenix routes | mix phoenix.routes
| version | Get current CLI version | -

Run `phoenix` for more options


## Generators List
You can use generators with the following syntax

```bash
phoenix generate GENERATOR_NAME
```

| Command | Description | Phoenix equivalent |
| --- | --- | --- |
| scaffold | Generate Full set of model, view, database migration for that model, controller | mix phoenix.gen.html
| api | Generate Full model, view in json, database migration for that model, controller  | mix phoenix.gen.json
| json | Alias for api command  | mix phoenix.gen.json
| model | Generates an Ecto model in your Phoenix application. | mix phoenix.gen.model
| channel | Generates a Phoenix channel  | mix phoenix.gen.channel
| presence | Generates a Presence tracker for your application | mix phoenix.gen.presence
| secret | Generates a secret and print it to the terminal | mix phoenix.gen.secret

