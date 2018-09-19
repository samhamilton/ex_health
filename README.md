# ExHealth ![ExHealth](logo.png)

[![CircleCI](https://circleci.com/gh/MatchedPattern/ex_health/tree/master.svg?style=svg&circle-token=8ed28fee90111e2a034b0d71e0fcf8ae18bba641)](https://circleci.com/gh/MatchedPattern/ex_health/tree/master)

ExHealth provides a health check endpoint for your application

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `ex_health` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:ex_health, "~> 0.1.0"}
  ]
end
```

Ensure ex_health is started alongside your application by adding this to your `mix.exs`

```elixir
def application do
  [applications: [:ex_health]]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/ex_health](https://hexdocs.pm/ex_health).

