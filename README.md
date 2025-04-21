# Actions

This repository contains reusable composite actions for GitHub Actions workflows.

## Usage

Simply import the action like so:

```yml
name: My workflow
on:
    push:
jobs:
    my-job:
        name: My job
        runs-un: ubuntu-latest
        steps:
            - name: Checkout repository
              uses: actions/checkout@v3
            - name: Reusable action
              uses: dnd-mapp/actions/setup-node@main
        
```
