---
title: "Conventional Commits"
linkTitle: "Conventional Commits"
description: >
  A standardized method for naming Git commits to increase clarity.
---

## Commit Types

| Commit Type | Title                   | Description                                                  |
| ----------- | ----------------------- | ------------------------------------------------------------ |
| `feat`      | Feature                 | A new feature                                                |
| `fix`       | Bug Fix                 | A bug fix                                                    |
| `docs`      | Documentation           | Documentation only changes                                   |
| `style`     | Style                   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc) |
| `refactor`  | Code Refactor           | A code change that neither fixes a bug nor adds a feature    |
| `perf`      | Performance Improvement | A code change that improves performance                      |
| `test`      | Tests                   | Adding missing tests or correcting existing tests            |
| `build`     | Build                   | Changes that affect the build system or external dependencies (gulp, broccoli, npm, etc.) |
| `ci`        | Continuous Integration  | Changes to our CI configuration files and scripts (Travis, Netlify, GitHub Actions, etc.) |
| `chore`     | Chore                   | Other changes that don't modify src or test files            |
| `revert`    | Revert                  | Reverts a previous commit                                    |

## Why Use Conventional Commits

- Automatically generating CHANGELOGs.

- Automatically determining a semantic version bump based on the types of commits.

- Communicating the nature of changes to teammates and the public.

- Automatically triggering build and publish processes.

- Making it easier for people to contribute to your projects, by allowing them to explore a more structured commit history.

  

  This style is inspired by Conventional Commits; read the full standard [here](https://www.conventionalcommits.org/en/v1.0.0/#specification).

