## 0.0.19-accelo

Improvements

- Performance - use `$evalAsync` to run changes in current or next and only run digest if changes to content are seen. This is to limit digests run by angular
