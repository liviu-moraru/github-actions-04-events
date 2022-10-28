# 04. Workflows & Events

- Documentatie events [aici](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)

## Event filters & Activity Types

- Activity Types

Ex: pull_request event has opened, closed, edited Activity Types

- Filters

Ex: push gas filter based on target branch

### Activity types
Ex:

```yaml
name: Events Demo 1
on:
  pull_request:
    types: [opened, edited]
  workflow_dispatch:
```



