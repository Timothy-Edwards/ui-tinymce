## 0.0.19-accelo.3

Fix (based on https://github.com/angular-ui/ui-tinymce/pull/230)

- Only save editor when editor is marked as stale (like done in debounce, which should really be using the same code)
- Listen to keyup for new keystrokes that are sometimes missed by changes event
- Do not file events when updating model

## 0.0.19-accelo.2

Improvement

- Stop saving editor when the editor fires an event.

## 0.0.19-accelo.1

Fixes

- Fix content disappearing in lists when pasting with power paste and then undoing content.

## 0.0.19-accelo

Improvements

- Performance - use `$evalAsync` to run changes in current or next and only run digest if changes to content are seen. This is to limit digests run by angular
