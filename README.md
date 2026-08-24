# Agent Team Governance Framework (ATGF)

A provider-independent framework for designing reliable, human-governed AI agent teams.

## Why ATGF?

Building capable AI agents is not enough. Real-world AI systems require governance:

- clear responsibilities
- controlled permissions
- structured communication
- verification workflows
- human escalation
- auditability

ATGF provides reusable patterns for operating multi-agent AI systems across different providers and runtimes.

## Core Principles

```
Capability != Authority
Intelligence != Trust
Autonomy != Unlimited Permission
```

## Reference Architecture

```
Human Authority
       |
Governance Layer
       |
+------+-------+------+
|      |       |      |
Planner Builder Reviewer
|      |       |
+------+-------+
       |
Validation Layer
       |
Execution Layer
```

## Features

- Agent role separation
- Permission boundaries
- Evidence-based handoff
- Context management
- Approval gates
- Audit-friendly workflows

## Project Status

ATGF is an early-stage open-source governance framework for multi-agent AI systems.

Contributions and discussions are welcome.

## License

Apache-2.0
