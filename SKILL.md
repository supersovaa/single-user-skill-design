---
name: single-user-skill-design
description: Design, introduce, and revise skills for a repository operated by one user with an AI agent, using repository-specific user information to keep workflows direct and lightweight.
---

# Single-user skill design

Design skills and their supporting artifacts for one user working with an AI agent.

Optimize for the user's actual workflow.
Use stable user-specific operations, decisions, and preferences when they make a skill simpler or more predictable.
Prefer concrete procedures over general-purpose flexibility.

## User model

Use the repository-root `user.md` as the source of repository-specific user information.

Read it before designing or revising a skill.

Record only user information that materially affects skill behavior or supporting artifacts.
Reflect user-specific information as concrete procedures where practical.

When `user.md` is missing, create it from the bundled template and determine the required information using the repository's established decision process.

When current instructions conflict with `user.md`, resolve the conflict with the user.
Update `user.md` when the resolved decision changes the continuing repository workflow.

When `user.md` changes, update affected skills and supporting artifacts.

## Skill introduction

Before introducing this skill, a public skill, or a project-local skill, thoroughly inspect the repository's active skills and artifacts for conflicting instructions, overlapping responsibilities, and competing outputs.

Resolve each conflict or overlap with the user before introduction.

Adapt general-purpose public skills to the repository's single-user environment when appropriate.
Choose the adaptation method with the user when it affects existing repository structure or skill ownership.

## Environment

When introducing this skill, configure the repository's governing instructions so skill creation and revision apply `single-user-skill-design`.

Public skills designed under this model state that they target a single-user AI-agent environment.
Require `user.md` only when the skill actually depends on repository-specific user information.

Keep skill instructions focused on behavior that materially affects the workflow.
