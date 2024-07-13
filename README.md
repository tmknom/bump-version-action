# bump-version-action

Bump up the version according to semantic versioning.

<!-- actdocs start -->

## Description

Specify the version level to increment and calculate the next version based on semantic versioning.
Choose to bump either the major, minor, or patch version.

If the current version is not provided, it will be automatically fetched from the latest Git tag.

## Usage

```yaml
  steps:
    - name: Bump Version
      uses: tmknom/bump-version-action@v0
      with:
        bump-level: minor
```

## Inputs

| Name | Description | Default | Required |
| :--- | :---------- | :------ | :------: |
| bump-level | Determines which part of the version to increment [patch/minor/major] | n/a | yes |
| current-version | The current version. | n/a | no |

## Outputs

| Name | Description |
| :--- | :---------- |
| next-version | The next version. |

<!-- actdocs end -->

## Permissions

| Scope    | Access |
| :------- | :----- |
| contents | read   |

## FAQ

N/A

## Related projects

N/A

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[releases]: https://github.com/tmknom/bump-version-action/releases
