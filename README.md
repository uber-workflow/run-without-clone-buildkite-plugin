# run-without-clone-buildkite-plugin

> Buildkite plugin to skip git clone before running a command

## Usage

```yaml
steps:
  - command: 'echo hi'
    plugins:
      - 'uber-workflow/run-without-clone':
```
