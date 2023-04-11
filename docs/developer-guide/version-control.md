# Version Control

## Commit messages

To support the automatic [semantic versioning](https://semver.org/) commit messages should always be prefixed with the type.
The format of the message should be

```
type(issuenr): message
```

The following types are supported:

- *chore* is a type of commit that does not affect the functionality of the software. It doesn't change it and has therefore no effect on the version tag.
- *fix* is used to singify a fix on existing funtionality. It increases the *patch* version (X.X.**X**).
- *feat* adds new functionality to the codebase but does not break existing APIs. It increases the *minor* version (X.**X**.X).
- *BREAKING* changes behaviour of existing APIs and increases the *major* version (**X**.X.X)
