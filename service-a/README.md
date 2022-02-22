# service-a

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] service-a`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree service-a`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init service-a
kpt live apply service-a --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
