# Single-User Skill Design

A lightweight skill for designing, introducing, and revising skills for one user working with an AI agent.

## Core idea

A single-user repository can use stable repository-specific user information directly when doing so makes skill behavior simpler and more predictable than general-purpose flexibility.

## Responsibility

`single-user-skill-design` owns adaptation of skills and their supporting artifacts to that single-user model.
It owns the role of repository-root `user.md` as stable user-specific context and the responsibility for reconciling skill behavior with that context when skills are introduced or revised.

## Adjacent responsibilities

General skill-repository planning and responsibility splitting belong to `skill-development-planning`.
Implementation of a settled skill-repository plan belongs to `skill-development-implementation`.
Independent review of the resulting skill definition belongs to `skill-definition-review`.

Executable behavior and detailed operational rules remain in `SKILL.md`.
