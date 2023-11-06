# example-python
Base Python repo for structure and CI/CD


# CI/CD
[Workflows in github](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions) have Ubuntu provided runners 

For python see https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python and https://github.com/actions/setup-python

It is recommneded to always use the setup-python action

## Workflow

The workflow yml controls the action run. To use githubs hosted runner use 
`runs-on: ubuntu-latest`

You can specify what image with

`container: image:tag`, otherwise the default OS image is used. 



