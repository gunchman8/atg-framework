# ATGF Model Selection Policy

## Purpose

ATGF does not force a specific AI provider or model.

Models should be selected based on role requirements, not personal preference or maximum capability.

## Default Mapping

| Role | Primary Need | Suggested Model Profile |
|---|---|---|
| Architect | reasoning, planning, system design | strongest reasoning model |
| Developer | implementation, debugging, code generation | coding-focused model |
| Reviewer | criticism, risk detection, quality analysis | strong reasoning model |
| Tester | verification, repetition, execution checks | fast reliable model |

## Selection Order

Use this order:

```
Role
 ↓
Required capability
 ↓
Permission level
 ↓
Model choice
 ↓
Effort level
```

## Avoid

Do not select models only because they are the most powerful.

A stronger model with excessive permissions can create more risk than value.

## Human Approval

Changing model capability, permissions, or execution scope should be treated as a governance decision for important projects.

## Provider Independence

This policy can be adapted to:

- Codex
- Claude Code
- Gemini-based agents
- Local models
- Other agent frameworks
