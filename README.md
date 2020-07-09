# GitHub Actions

## Concepts

A Workflow is a collection of Job(s), and each Job is a collection of Step(s).

Actions can be sourced from within the same repository, from another public repository or from a published Docker container image.

## Workflows

### Triggers

Execute the workflow anytime that code is pushed into your repository.
```
on: push
```