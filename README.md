# Regex Garden 🌻

A calm and grounding space to explore regular expressions. It provides an interactive web-based interface where you can generate strings, compare syntax and learn what runs underneath regular expressions.

## Features Let's Plant Together!
- **Plant Palette**: Easily insert atoms like letters, digits, and operators (`|`, `*`, `+`, `?`, `()`, `ε`) into your expressions.
- **Grow Strings**: Provide an expression seed and watch the tool enumerate strings over the alphabet up to a chosen maximum length to keep the ones the Native Finite Automaton (NFA) accepts.
- **Compare Flowers**: Check equivalency of two regex patches (languages) by comparing every string up to a fixed test depth.

## Implementation Details
The script uses a tiny regex engine supporting literals, empty string (`ε`), union (`|`), concatenation, and the typical Kleene operators.
It works by parsing your expression into a syntax tree and then converting it to a Thompson NFA to correctly evaluate expressions and inputs.

## Getting Started
Just open `regex-garden.html` in your favorite modern browser to start planting!

## Working Demo
https://youtu.be/oZpzA0SRTmY?si=JTzzb_KLjBLoIDOb
