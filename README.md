# License Check Action

A GitHub Action for ensuring dependencies use only permitted licenses or explicitly approved.

Drived from [license-finder-action](https://github.com/jmservera/license-finder-action)

## Inputs
### permitted-licenses
A comma separated list of licenses that are permitted. For example:

```
permitted-licenses: MIT,Apache-2.0
```

### approved-dependencies
A comma separated list of dependencies that are approved
```
approved-dependencies: jquery,bootstrap
```

### base-path
Required If it is not in the root workspace parth, the base path with the code to review.

Default: ${{ github.workspace }}


