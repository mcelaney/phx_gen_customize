# Phx.Gen.Customize

A generator template customizer

## Overview

The purpose of `phx.gen.customize`is to generate customizable overrides for Phoenix 1.7 [generator](https://hexdocs.pm/phoenix/Mix.Tasks.Phx.Gen.html) templates. These templates are be overridden by copying the [template files](https://github.com/phoenixframework/phoenix/tree/main/priv/templates) in to the `priv/templates` directory of the project - which isn't necesarily obvious to newcomers. Further - these template files lack certain features which can be time consuming or confusing to add after the fact.

This project provides an alternative to generate these generator template files with various options.


## Usage

When [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `phx_gen_customize` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:phx_gen_customize, "~> 0.1", only: [:dev], runtime: false},
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/phx_gen_customize>.

