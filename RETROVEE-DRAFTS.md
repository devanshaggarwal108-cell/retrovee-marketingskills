# Retrovee draft workflow

This edition builds on [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills). Original copyright and licensing are in [LICENSE](LICENSE).

Upstream main branch ZIP SHA-256: `78722ec7eb7ee1bd91940daedb77cffd9da97e29b1d0be44729444aa35f9792d`.

Use the [`retail-seo-audit` skill](codex-skills/retail-seo-audit/SKILL.md) for the Codex draft workflow. Copy the entire skill directory into your Codex skills directory. This skill has no runtime dependencies. The upstream tools retain their separate setup instructions in the original README.

Keep credentials, customer data and performance exports out of Git. Review proposed external changes and get approval before making them live.

## GitHub Actions

The original workflows are retained in `.github/upstream-workflows/` for review. Enable selected workflows only after checking their triggers, tokens and publish targets.
