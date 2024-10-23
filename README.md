# cleanup-folder-action

[![CI](https://github.com/datalens-tech/cleanup-folder-action/workflows/Check%20PR/badge.svg)](https://github.com/datalens-tech/cleanup-folder-action/actions?query=workflow%3A%22%22Check+PR%22%22)
[![GitHub Marketplace](https://img.shields.io/badge/Marketplace-cleanup-folder-action-blue.svg)](https://github.com/marketplace/actions/cleanup-folder-action)

cleanup-folder-action

## Usage

### Example

```yaml
jobs:
  cleanup-folder-action:
    permissions:
      contents: read

    steps:
      - name: cleanup-folder-action
        id: cleanup-folder-action
        uses: datalens-tech/cleanup-folder-action@v1
```

### Action Inputs

| Name          | Description  | Default |
| ------------- | ------------ | ------- |
| `placeholder` | Placeholder. |         |

### Action Outputs

| Name          | Description  |
| ------------- | ------------ |
| `placeholder` | Placeholder. |

## Development

### Global dependencies

- [Taskfile](https://taskfile.dev/installation/)
- [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script)

### Taskfile commands

For all commands see [Taskfile](Taskfile.yaml) or `task --list-all`.

## License

[MIT](LICENSE)
