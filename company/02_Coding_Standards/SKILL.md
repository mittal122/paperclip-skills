---
name: coding-standards
description: Company-wide engineering standards for writing, reviewing, refactoring, and maintaining software. Use this skill whenever an agent produces or modifies code.
version: 1.0.0
category: engineering
tags:
  - coding
  - engineering
  - quality
  - review
  - architecture
---

# Coding Standards

## Purpose

This skill defines the engineering standards every software engineering agent must follow while designing, writing, reviewing, refactoring, debugging, or maintaining software.

Its objective is to ensure that every code change is:

- Readable
- Maintainable
- Scalable
- Secure
- Reliable
- Testable
- Consistent

---

# When to Use

Use this skill whenever an agent is:

- Writing new code
- Refactoring existing code
- Fixing bugs
- Reviewing code
- Creating APIs
- Designing software architecture
- Building libraries
- Creating automation
- Writing tests
- Improving performance

---

# Do Not Use

Do not use this skill for:

- Product planning
- Hiring decisions
- Company strategy
- Business analysis
- Market research
- Project management

---

# Engineering Philosophy

Always optimize for:

Business Value

↓

Readability

↓

Maintainability

↓

Reliability

↓

Security

↓

Performance

↓

Scalability

Never sacrifice long-term quality for short-term speed.

---

# Core Principles

Every implementation should be:

Simple

Readable

Consistent

Modular

Reusable

Documented

Secure

Testable

Maintainable

---

# Before Writing Code

Always understand:

- Business Requirement
- Acceptance Criteria
- Existing Architecture
- Existing Components
- Company Standards
- Previous Implementations
- Company Brain
- Knowledge Base

Never write code before understanding the problem.

---

# Coding Rules

Always:

- Write self-explanatory code.
- Follow the existing architecture.
- Reuse existing components.
- Avoid duplication.
- Keep functions focused on one responsibility.
- Keep classes cohesive.
- Prefer composition over unnecessary complexity.
- Avoid hidden side effects.
- Handle failures gracefully.
- Keep code easy to modify.

Never:

- Hardcode secrets.
- Ignore architecture.
- Introduce unnecessary complexity.
- Copy code without understanding it.
- Leave undocumented technical debt.
- Commit broken code.

---

# Naming Standards

Names should be:

- Clear
- Predictable
- Descriptive
- Consistent

Prefer names such as:

- UserRepository
- AuthenticationService
- AgentCoordinator
- WorkflowExecutor
- ProjectAnalyzer

Avoid generic names such as:

- temp
- value
- obj
- data
- test1

---

# Error Handling

Every error should:

- Be handled intentionally.
- Produce meaningful messages.
- Preserve useful debugging information.
- Avoid exposing sensitive information.
- Fail safely.

---

# Security Requirements

Always:

- Validate inputs.
- Sanitize outputs.
- Protect secrets.
- Use least privilege.
- Follow company security standards.

Never:

- Hardcode credentials.
- Expose API keys.
- Trust external input.
- Disable security protections.

---

# Testing Requirements

Every implementation should include appropriate testing.

Possible test types include:

- Unit Tests
- Integration Tests
- Regression Tests
- Failure Scenarios
- Edge Cases

Critical functionality should always be verified before completion.

---

# Documentation Requirements

Document:

- Public APIs
- Complex algorithms
- Configuration
- Architectural decisions
- Important workflows

Avoid documenting obvious code.

---

# Git Standards

Every commit should:

- Be focused.
- Be atomic.
- Have a meaningful commit message.
- Avoid unrelated changes.

Example:

```text
feat(agent): add dynamic hiring workflow

fix(memory): prevent duplicate lesson creation

refactor(api): simplify authentication middleware
```

---

# Code Review Checklist

Before considering work complete, verify:

- Requirements satisfied
- Architecture respected
- Code readable
- Naming consistent
- Security considered
- Tests completed
- Documentation updated
- No duplicated logic
- Existing knowledge reused

---

# Knowledge Integration

Before solving any technical problem, consult:

- Company Brain
- Organizational Learning System
- Knowledge Management
- Previous Projects
- Incident Reports
- Existing Components

Do not reinvent previously solved solutions.

---

# Related Company Documents

This skill complements:

- Company Constitution
- Company Architecture
- Decision Framework
- Quality Framework
- Security Standards
- Documentation Standards
- Learning Framework
- Knowledge Management

---

# Final Directive

Every line of code represents the company.

Write software that another engineer can confidently understand, maintain, extend, and trust years from now.

The objective is not simply to make the software work.

The objective is to build software that strengthens the company's long-term engineering excellence.
