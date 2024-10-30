# argo-akri-app

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] argo-akri-app`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree argo-akri-app`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init argo-akri-app
kpt live apply argo-akri-app --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
