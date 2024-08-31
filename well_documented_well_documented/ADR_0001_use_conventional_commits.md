# Standardize Git Commit Messages With Conventional Commits

* Status: proposed
* Deciders: @jfahne
* Date: 2024-08-31

## Context and Problem Statement

As this project is tracked in git, it presents the interesting question of how best to use git
as part of the project's documentation structure? Specifically, what convention should be used
in commit messages?

## Considered Options

* No convention
* Plain language summary
* [Conventional Commits](https://www.conventionalcommits.org)

## Decision Outcome

Chosen option: "Conventional Commits", because it is a simple but effective enrichment of git commit
messages that allows for semantic versioning of documentation and automated changelog generation.

### Positive Consequences

* Automate changelog generation
* Lightweight enough to minimize migration efforts in the future
* Widely adopted

### Negative Consequences

* Requires git history manipulation in the future for a produced standard to be used.

