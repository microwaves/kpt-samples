# review-namespace

## Description
review-namespace description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] review-namespace`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree review-namespace`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init review-namespace
kpt live apply review-namespace --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
