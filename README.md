# AI-pokemon-color-matcher
This project uses DSPy and the Gemini API to find a Pokemon that best matches a given color combination, demonstrating how to structure LLM outputs into reliable, typed fields.

# Pokemon Color Matcher

## Tech Stack
- Python 3.10+
- [DSPy](https://github.com/stanfordnlp/dspy) — structured LLM framework
- Google Gemini 2.5 Pro via API
- pandas

## What it does
- Input a color combination (e.g., "Orange and Cyan")
- AI reasons through which Pokemon best matches those colors
- Returns Pokemon name + full ability description
- Processes 20 color themes in batch → outputs a clean DataFrame

## Example Output
