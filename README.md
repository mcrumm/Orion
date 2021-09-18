# Orion

Orion is a Dynamic Distributed Profiler. It allows you to profile any function
in an erlang cluster and get back an histogram representing the profile of the
function calls across the whole cluster.

It is meant to be used as a library in part of your existing application.

## Goals

- [ ] Can show a graph of fake or real data
- [ ] Can change the function traced to a new one
- [ ] Can get trace data in a distributed way
- [ ] More to come !

## Non Goals

- Be useable in any BEAM language. This may happen in the future but for now we
  depend on dog_sketch which is in elixir
- separate frontend and data collection library. That may come in the future,
  but no time for it at spawnfest

## TODO add how to add it to your app

## Hacking

Orion is a phoenix liveview application for the frontend.

To start your Phoenix server:

- Install dependencies with `mix deps.get`

Test can be run with `mix test`. We try to keep everything in the elixir side tested fairly completely

If you want to see it in action

- Install Node.js dependencies with `yarn install --cwd assets` inside the `assets` directory
- Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.
