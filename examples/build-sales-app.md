# Example: Build a Sales App with ATGF

## User input

> Tôi muốn xây một app bán hàng.

## What ATGF does

Instead of giving the whole task to one AI agent, ATGF creates a small AI team.

```
Human Authority
        |
        v
Architect
        |
        +---- Developer
        |
        +---- Reviewer
        |
        +---- Tester
```

## Proposed team

### Architect

Goal:
- Understand the business goal.
- Define MVP scope.
- Design system boundaries.

Permission:
- Read context.
- Create plans.

Cannot:
- Modify production code.
- Deploy.

### Developer

Goal:
- Implement approved tasks.

Permission:
- Modify assigned files.
- Run approved tests.

Cannot:
- Access secrets.
- Deploy without approval.

### Reviewer

Goal:
- Find problems before release.

Permission:
- Read code and evidence.

Cannot:
- Approve own work.

### Tester

Goal:
- Verify acceptance criteria.

Permission:
- Run validation.

Cannot:
- Change architecture.

## Workflow

```
Idea
 |
v
Architect creates plan
 |
v
Human approval
 |
v
Developer builds
 |
v
Reviewer checks
 |
v
Tester validates
 |
v
Human accepts
```

## The important idea

ATGF does not make AI smarter.

It helps humans organize AI capability safely.

```
Capability != Authority

Role first
Permission second
Model third
Effort last
```
