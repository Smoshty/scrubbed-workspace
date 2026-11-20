# Reference findings

- A fresh Codex agent on Linux built and repaired a local demonstration using
  a fictional mailbox, a local model and a separate checked reader. It verified
  that an unreadable attachment stayed held and that repeat processing produced
  one copy. The simulated owner handled no terminal commands.
- The reference's wider 100-message evaluation failed acceptance. Some messages
  with useful tasks stayed held, and one copy lost part of a required phrase.
  Later focused checks passed. The current design still requires its own checks.
- A first-use email detector tried a network lookup. Using its bundled domain
  list fixed the lookup while preserving full address detection in tests.
- Mac setup, Claude as the setup agent, and actual Workspace delivery have yet
  to be demonstrated in this project.

## Optional reference code

[Download the reference at `c5ece5e`](https://github.com/Smoshty/scrubbed-workspace/blob/main/reference-c5ece5e.zip?raw=true).
Extract it and read its README to run the included synthetic software checks.
Choose what to reuse for this setup.
