# Taste

## Communication

- Writes in Spanish and expects replies in Spanish. Confidence: 0.65

## Workflow

- Prefers answers grounded in the real local environment over docs/memory: expects the assistant to actually query the installed tool/CLI/config ("checa aquí… cuál es") instead of guessing values. Confidence: 0.5
- Impatient with long waits and dislikes slow verification loops; when the change is small, expect focused tests rather than blocking on the full (slow, serial) suite. Confidence: 0.55
- Doesn't accept "ya quedó / should work" as done: when a fix touches a running system, wants the assistant to start it and prove it end-to-end with a simple smoke test ("correlo y pruebalo con algo simple"). Confidence: 0.6

## Engineering

- When offered a quick workaround vs. the canonical approach, wants the canonical one that "queda bien como los demás" — i.e. follow the existing repo patterns/contracts instead of glue wrappers. Confidence: 0.5
