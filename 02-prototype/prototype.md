# Prototype · Juno

> Module 2 · Prototype. The working build that tests your idea, made with your build tool of choice.

## Prototype link

https://lovable.dev/preview/fJ7uDYds1vACcUwhrVMao1Uv1UHuwJnv
_____

## What it demonstrates

A PM types `/digest` in the #product-feedback Slack channel and Juno replies in the same channel with a five-part insight digest (summary, top themes table, weak signals, questions for the PM, how it grouped them).

_____

## Debrief

- **What worked:** The concept passed the filter. It replaces a job PMs already do by hand every week, it sits where the signals already are, and the quote-per-theme rule means the PM can check the output in seconds. My partner needed explination.
- **What broke / felt like a toy:** The outcome is still fake good. The digest is hand-written, so it only proves the format. The eight messages were clean and grouped themselves. The hard part, finding the real themes in 200 noisy messages without missing one, is not tested at all. The table is also cramped inside a chat bubble.
- **What I'd change next pass:** Connect `/digest` to a real LLM with the skill file as the system prompt. Feed it 40 messy messages, not 8 clean ones. Add a visible "last 7 days" scope. Then the test is simple: does the PM still open the channel to trust the digest? If yes, the idea is dead. If no, it is a boring killer.
