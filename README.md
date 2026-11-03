# config-manager

Lightweight Lua config loader.

## Description

`config-manager` is a minimal library for loading and parsing configuration files in Lua. It provides a basic set of utilities for reading configuration data and converting it into Lua tables.

## Project Structure

- `src/` — Source code.
  - `init.lua` — Entry point.
  - `parser.lua` — Configuration parsing logic.
  - `utils.lua` — Helper functions.
- `examples/` — Usage examples.
  - `basic.lua` — Basic usage example.
- `tests/` — Test suite.
  - `test_parser.lua` — Tests for the parser module.

## Requirements

- Lua 5.1 or higher.

## Usage

Refer to the `examples/basic.lua` file for a basic usage example.

```lua
local config = require("config-manager")
-- ...
