# DepWarningExample

Example project for [this github issue](https://github.com/elixir-lang/elixir/issues/10624).

To reproduce the warning, simply `mix deps.get` and then run `iex -S mix`. You should get this warning:

```
You have configured application :git_hooks in your configuration file,
but the application is not available.

This usually means one of:

  1. You have not added the application as a dependency in a mix.exs file.

  2. You are configuring an application that does not really exist.

Please ensure :git_hooks exists or remove the configuration.
```
