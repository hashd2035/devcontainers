# devcontainers

## templates
- [java template](https://github.com/hashd2035/dc-java)
- [node template](https://github.com/hashd2035/dc-node)
- [python template](https://github.com/hashd2035/dc-python)
- [cpp template](https://github.com/hashd2035/dc-cpp)
- [rust template](https://github.com/hashd2035/dc-rust)
- [go template](https://github.com/hashd2035/dc-go)

## Create repo using a template

1. `gh repo list --topic devcontainer` to see the list of `devcontainer` templates
2. `gh repo create {repo-name} --template {template-name} --private` to create repo based on the template in github
3. `gh repo clone {repo-name}`
4. open in vscode

### Just clone the template repo to have in run just locally and try out
1. `gh repo clone {template-name} {repo-name}`
2. open in vscode

## Create or Modify devcontainer.js

- Specification: https://containers.dev/implementors/json_reference/
- Additional tool specific specification: https://containers.dev/supporting

## More Resources
- More templates - https://github.com/devcontainers/templates
- vscode devcontainer tutorials - https://code.visualstudio.com/docs/devcontainers/containers
