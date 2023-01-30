# test-automatic-release1
- With this GitHub Action -> https://github.com/cycjimmy/semantic-release-action
- The Action use this package -> https://github.com/semantic-release/semantic-release
- Conventional Commits -> https://www.conventionalcommits.org/en/v1.0.0/


### Increase PATCH X.X.1
summary: `fix: Some description text`

### Increase MINOR X.1.X
summary: `feat: Some description text`

### Increase MAJOR 1.X.X
summary: `feat or fix`<br>
description: `BREAKING CHANGE: Some description text`


## Plugins

### @semantic-release/commit-analyzer

### @semantic-release/exec

### @semantic-release/release-notes-generator

#### @semantic-release/changelog

### @semantic-release/git
Plugin to commit release assets to the project's git repository

### @semantic-release/github
Semantic-release plugin to publish a GitHub release and comment on released Pull Requests/Issues.
