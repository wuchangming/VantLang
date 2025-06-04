# 🕳️ VantLang

VantLang is a minimal control language used to operate LLM agents through strict
block-based messages. The `core/prompt/system.md` file defines the canonical
prompt that governs an agent's behaviour.

## Usage

1. Provide the user goal in `!GOAL[...]`.
2. Describe tools and constraints with `@ENV[...]`.
3. Specify the success criteria via `ΩHALT[...]`.

The agent will then follow the loop defined in the system prompt until the goal
is met or it halts with failure.

See the prompt file for full syntax and safety rules.

This repository contains the system prompt specification and examples for VantLang – a structured language designed for LLM-native execution and reasoning.
