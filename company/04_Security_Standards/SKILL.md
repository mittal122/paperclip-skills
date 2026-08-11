---
name: security-standards
description: Company-wide security standards governing how AI agents design, develop, review, deploy, and operate secure software, infrastructure, and organizational processes.
version: 1.0.0
category: security
tags:
  - security
  - cybersecurity
  - secure-development
  - governance
  - infrastructure
---

# Security Standards

## Purpose

This skill defines the security principles, engineering practices, operational requirements, and governance standards that every AI agent must follow throughout the software development lifecycle.

Its objective is to ensure every product, service, infrastructure component, automation workflow, and internal process is secure by design rather than secured as an afterthought.

Security is a company-wide responsibility—not the responsibility of a single department.

---

# When to Use

Use this skill whenever an agent is:

- Designing system architecture
- Writing or reviewing code
- Building APIs
- Managing infrastructure
- Configuring cloud resources
- Deploying applications
- Managing databases
- Creating CI/CD pipelines
- Managing authentication
- Handling sensitive information
- Performing security reviews
- Investigating incidents
- Processing customer data

---

# Do Not Use

Do not use this skill for:

- Product planning
- Hiring decisions
- Documentation formatting
- Communication standards

Those responsibilities belong to their respective skills.

---

# Security Philosophy

Security is proactive—not reactive.

Every system should be designed assuming failures, attacks, mistakes, and misuse will eventually occur.

The objective is to reduce risk, minimize impact, and recover quickly.

Every security decision should support long-term resilience.

---

# Core Principles

Every system should be:

Secure by Design

Least Privileged

Defense in Depth

Fail Securely

Auditable

Monitored

Verified

Continuously Improved

---

# Security Objectives

Every project should protect:

- Customer Data
- Company Knowledge
- Source Code
- Credentials
- Infrastructure
- APIs
- Internal Services
- Intellectual Property
- Operational Continuity

Security should preserve:

Confidentiality

Integrity

Availability

---

# Identity and Access Management

Always:

- Apply least privilege.
- Grant only required permissions.
- Use role-based access control (RBAC).
- Separate administrative and operational privileges.
- Review access periodically.
- Remove unused permissions promptly.

Never:

- Share credentials.
- Use administrator privileges unnecessarily.
- Grant permanent elevated access without justification.

---

# Authentication Standards

Always:

- Use strong authentication.
- Require multi-factor authentication (MFA) where supported.
- Protect authentication tokens.
- Use secure session management.
- Expire inactive sessions appropriately.

Never:

- Store passwords in plain text.
- Hardcode authentication credentials.
- Expose session tokens.

---

# Secrets Management

Sensitive information includes:

- API Keys
- Passwords
- Tokens
- Certificates
- SSH Keys
- Private Keys
- Encryption Keys
- Database Credentials

Always:

- Store secrets in approved secret-management systems.
- Rotate credentials regularly.
- Limit secret access.
- Audit secret usage.

Never:

- Commit secrets to Git.
- Hardcode secrets.
- Store credentials in documentation.
- Expose secrets in logs.

---

# Secure Development

Every implementation should:

- Validate all inputs.
- Sanitize outputs.
- Handle errors securely.
- Minimize attack surface.
- Use secure defaults.
- Protect against common vulnerabilities.
- Reuse trusted libraries whenever appropriate.

Never trust external input.

---

# API Security

Every API should include:

- Authentication
- Authorization
- Input Validation
- Output Validation
- Rate Limiting
- Error Handling
- Audit Logging
- Version Management

Avoid exposing unnecessary information in responses.

---

# Infrastructure Security

Infrastructure should:

- Follow least privilege.
- Minimize exposed services.
- Encrypt sensitive communications.
- Enable logging.
- Apply security updates.
- Monitor continuously.
- Isolate workloads appropriately.
- Restrict network access where appropriate.

Infrastructure should be secure by default.

---

# Cloud Security

When using cloud platforms:

- Follow cloud security best practices.
- Separate environments.
- Protect cloud identities.
- Audit permissions.
- Encrypt storage where appropriate.
- Monitor resource activity.
- Review public exposure regularly.

Cloud resources should never be created without security review.

---

# CI/CD Security

Deployment pipelines should:

- Protect credentials.
- Verify artifacts.
- Validate dependencies.
- Restrict deployment permissions.
- Log deployment activity.
- Prevent unauthorized modifications.

Automation should improve security—not bypass it.

---

# Dependency Management

Before using third-party software:

- Evaluate necessity.
- Verify reputation.
- Review maintenance status.
- Monitor for known vulnerabilities.
- Keep dependencies updated.
- Remove unused packages.

Minimize unnecessary dependencies.

---

# Logging and Monitoring

Security monitoring should include:

- Authentication events
- Authorization failures
- Infrastructure changes
- Deployment activity
- Critical configuration changes
- Security alerts
- Incident timelines

Logs should:

- Protect sensitive information.
- Support investigation.
- Remain tamper-resistant where possible.

---

# Incident Response

Whenever a security incident occurs:

1. Detect.
2. Contain.
3. Assess impact.
4. Preserve evidence.
5. Identify root cause.
6. Resolve the issue.
7. Restore services.
8. Document lessons learned.
9. Update Company Brain.
10. Improve standards.

Every incident should strengthen future security.

---

# Security Reviews

Before approving a project verify:

- Authentication implemented
- Authorization verified
- Secrets protected
- Input validation completed
- Logging enabled
- Error handling secure
- Dependencies reviewed
- Infrastructure reviewed
- Risks documented
- Security standards followed

Security review is mandatory before production deployment.

---

# Continuous Security Improvement

Continuously improve:

- Security policies
- Infrastructure
- Detection capabilities
- Monitoring
- Incident response
- Secure coding practices
- Automation
- Security documentation

Security should evolve alongside the company.

---

# Knowledge Integration

Every security event should contribute to:

- Company Brain
- Organizational Learning System
- Knowledge Management
- Incident Database
- Security Playbooks
- Engineering Standards
- Architecture Standards

Security knowledge should become permanent organizational knowledge.

---

# Security Anti-Patterns

Never:

- Ignore security warnings.
- Bypass authentication.
- Disable security protections.
- Hardcode credentials.
- Ignore vulnerability reports.
- Expose sensitive information.
- Deploy unreviewed critical changes.
- Assume internal systems are automatically trusted.

Security shortcuts become future incidents.

---

# Related Company Documents

This skill complements:

- Company Constitution
- Company Brain
- Decision Framework
- Coding Standards
- Documentation Standards
- Communication Protocol
- Organizational Learning System
- Knowledge Management
- Quality Framework
- Project Lifecycle

---

# Final Directive

Every AI agent is responsible for protecting the company, its customers, its software, and its knowledge.

Security is not a final review—it is a continuous responsibility embedded into every decision, every line of code, every deployment, and every operational process.

The objective is not simply to prevent attacks.

The objective is to build an organization where secure thinking becomes a permanent part of the company's culture, engineering practices, and institutional knowledge.
