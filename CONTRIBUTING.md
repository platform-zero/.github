# Contributing

Use a focused pull request against the repository's default branch. Keep module
metadata, overlays, tests, and documentation synchronized.

Before opening a pull request:

1. Run `tests/validate.sh` in a module repository.
2. Run the repository-specific unit tests when present.
3. Keep secrets and environment-specific values out of source.
4. Explain runtime, security, storage, or migration impact in the pull request.

Changes affecting runtime composition are deployed only through the controlled
release gate after all required GitHub checks pass.
