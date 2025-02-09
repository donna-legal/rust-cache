# Changelog

## 1.2.0

- Cache `~/.cargo/bin`.
- Support for custom `$CARGO_HOME`.
- Add a `cache-hit` output.
- Add a new `sharedKey` option that overrides the automatic job-name based key.

## 1.1.0

- Add a new `working-directory` input.
- Support caching git dependencies.
- Lots of other improvements.

## 1.0.2

- Don’t prune targets that have a different name from the crate, but do prune targets from the workspace.

## 1.0.1

- Improved logging output.
- Make sure to consider `all-features` dependencies when pruning.
- Work around macOS cache corruption.
- Remove git-db cache for now.
