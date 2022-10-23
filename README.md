# vabland: github-workflows

## Description
This repository have all github workflows templates to be used for vabland projects.


## Usage
On jobs configuration:

```yml
jobs:
  job-name-1:
    uses: vabland/actions-templates/.github/workflows/terraform-build-workflow.yml@main
    with:
      #...
    secrets:
      #...
```

```yml
jobs:
  job-name-2:
    uses: vabland/actions-templates/.github/workflows/terraform-destroy-workflow.yml@main
    with:
      #...
    secrets:
      #...
```
