# Homebrew tap for cursor-plus

Install the current release:

```bash
brew tap errr0rr404/cursor-plus
brew install cursor-plus
cursor+ --setup
cursor+ --doctor
```

**Born** 2026-09-23 (`v0.1.0`). **Current formula** 0.1.7 (2026-10-23).

Prompt history and bookmarks:

- `cursor+ --history` reads `~/.cursor-plus/history.jsonl`. Each line has `ts`, the time the prompt was submitted.
- `cursor+ --snippets` reads `~/.cursor-plus/bookmarks.json`. Each bookmark has its own `ts`. Inside a session, Ctrl+B bookmarks the last reply.

Source, changelog, and the rest of the docs: [Errr0rr404/cursor-plus](https://github.com/Errr0rr404/cursor-plus).
