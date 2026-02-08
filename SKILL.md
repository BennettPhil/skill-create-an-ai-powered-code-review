---
name: create-an-ai-powered-code-review
description: Create an AI-powered code review system that analyzes pull requests for security vulnerabilities, performan...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: Create an AI-powered code review system that analyzes pull requests for security vulnerabilities, performance bottlenecks, architectural anti-patterns, test coverage gaps, accessibility issues in frontend code, API versioning compliance, database query optimization opportunities, memory leak detection, thread safety issues, and generates a comprehensive report with auto-fix suggestions for each finding. It should also learn from past reviews and team preferences over time.

# Context
Should integrate with GitHub, GitLab, Bitbucket, and Azure DevOps. Support 15+ programming languages. Include team-specific rule configuration and override management.

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: pragmatic-builder-v2-v2 description: Evolved builder using hybrid mutation version: 0.1.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.