# cleanup-folder-action

[![CI](https://github.com/datalens-tech/cleanup-folder-action/workflows/Check%20PR/badge.svg)](https://github.com/datalens-tech/cleanup-folder-action/actions?query=workflow%3A%22%22Check+PR%22%22)
[![GitHub Marketplace](https://img.shields.io/badge/Marketplace-cleanup-folder-action-blue.svg)](https://github.com/marketplace/actions/cleanup-folder-action)

Action for delete data from action`s workdir

## Usage

### Example

```yaml
jobs:
  cleanup-folder-action:
    steps:
      - name: cleanup-folder-action
        uses: datalens-tech/cleanup-folder-action@v1
```

### Action Inputs

None

### Action Outputs

None

## Development

### Global dependencies

- [Taskfile](https://taskfile.dev/installation/)
- [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script)

### Taskfile commands

For all commands see [Taskfile](Taskfile.yaml) or `task --list-all`.

## License

[MIT](LICENSE)
