# Testing with github workflows

```yml
on:
  push:
    branches: [ main ]
```
is more than enough to only run the workflow when a commit is made to `main` or a PR is merged to `main`

## Addressing issues

Using `closes #NUMBER` for example in one of the following locations closes issue #NUMBER when merged with main.

- Commit Title
- Commit Description
- PR Description
- PR Title

### Available Keywords (Must be directly in front of issue number)

- close
- closes
- closed
- fix
- fixes
- fixed
- resolve
- resolves
- resolved

[More Info](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue)
