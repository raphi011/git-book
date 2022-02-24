# Gradle

Difference between `check` and `test`

* `check` performs all verification tasks in the project, including tests and others like linting
* `test` only runs the project's tests

Difference between `api()` and `implementation()` : the latter doesn't expose transitive dependencies to projects that use the library.

## Useful commands:

List all projects:

```
./gradlew -q projects
```

