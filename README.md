# Issues

An [Github Issues](https://help.github.com/articles/about-issues/) API wrapper written in Elixir.

This a sample project from the book [Programming in Elixir 1.3](https://pragprog.com/book/elixir13/programming-elixir-1-3), by [Dave Thomas](https://github.com/pragdave).

## Usage

`$ issues <github user> <github project> [number of issues (default to 4)]`

Example:

`$ issues elixir-lang elixir 2`

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `issues` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:issues, "~> 0.1.0"}]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/issues](https://hexdocs.pm/issues).
