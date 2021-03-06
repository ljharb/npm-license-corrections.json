SPDX license expressions for npm packages without proper metadata

# Schema

This package exports an Array of Objects.  Each Object looks like:

```json
{
  "name": "optimist",
  "version": "6.0.1",
  "license": "MIT"
}
```

`license` contains a valid SPDX license expression for `version` of package `name`.

`name` may contain a scope, as well as a package name, like `@scope/package`.

# Versioning

| When this project ... | ... it will increment |
|-----------------------|-----------------------|
| corrects an entry     | patch                 |
| adds a new entry      | minor                 |
| breaks schema         | major                 |
