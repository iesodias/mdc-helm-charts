# MDC Charts Repo

## Helm Charts GitHub Repository
- [Helm Charts GitHub Repository](https://github.com/iesodias/mdc-helm-charts)

## Regenerate index.yaml for git Helm Repo
```bash
## Regenerate index.yaml
# Add new charts to existing repo
helm repo index --url https://iesodias.github.io/mdc-helm-charts --merge index.yaml .
```
