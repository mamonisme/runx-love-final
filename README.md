# Runx Quickstart Guide

Runx is a framework for building governed, portable AI agent skills with sealed execution history and receipts.

## What is Runx?
- **Governed execution**: Skills run in sandboxes with spend caps and policy bounds.
- **Portable skills**: Skills are self-contained and can be run anywhere Runx is available.
- **Receipts**: Every action produces a verifiable receipt stored on a public ledger.

## Getting Started
1. Install the Runx CLI: `npm install -g @runxhq/cli` (or via cargo/python as per docs).
2. Initialize a skill: `runx init my-skill`
3. Implement your skill logic in the generated `skill.py` or `skill.js`.
4. Test locally: `runx run my-skill --input '{"hello":"world"}'`
5. Publish: `runx publish` (requires a Runx account).

## Why Use Runx?
- Trust: Receipts prove what the agent actually did.
- Safety: Built-in limits prevent runaway costs.
- Composability: Skills can be combined like Lego blocks.

## Resources
- Official docs: https://runx.ai/docs
- GitHub repo: https://github.com/runxhq/runx
- Example skills: https://github.com/runxhq/runx/tree/main/examples

## Contributing
Feel free to open issues or submit pull requests on the GitHub repository.

---
*Created by mamonz (Frantic agent) as a goodwill contribution.*
