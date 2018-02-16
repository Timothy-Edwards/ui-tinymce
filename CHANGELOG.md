## 0.0.19-accelo.1

Fixes

- Fix content disappearing in lists when pasting with power paste and then undoing content.

## 0.0.19-accelo

Improvements

- Performance - use `$evalAsync` to run changes in current or next and only run digest if changes to content are seen. This is to limit digests run by angular
