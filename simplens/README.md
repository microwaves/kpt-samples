# simplens

## Description
Just a simple namespace blueprint

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] simplens`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree simplens`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init simplens
kpt live apply simplens --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/