---
type: decision
---
# Implement ontology and agent guardrails

Commit: `0fae716a59f9db4f1d647b29235ba5a6777ee013`
Message: Implement ontology and agent guardrails
Source: https://github.com/ImDanIch/TaskFlow/commit/0fae716a59f9db4f1d647b29235ba5a6777ee013

## Changed files

- `.codex/hooks.json` (added)
- `README.md` (modified)
- `guardrails/README.md` (added)
- `guardrails/__init__.py` (added)
- `guardrails/codex_hook.py` (added)
- `guardrails/policies.json` (added)
- `guardrails/policy.py` (added)
- `ontology/README.md` (added)
- `ontology/__init__.py` (added)
- `ontology/definitions.json` (added)
- `ontology/requirements.txt` (added)
- `ontology/validator.py` (added)
- `tests/test_guardrails.py` (added)
- `tests/test_ontology.py` (added)

## Summary

Adds a TaskFlow-KB ontology with entity and relationship definitions and a read-only Markdown/frontmatter validator. Adds an ordered allow/warn/block policy evaluator, a Codex PreToolUse adapter and hook configuration, documentation, and tests for ontology and guardrails.
