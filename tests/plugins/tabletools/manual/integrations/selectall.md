@bender-ui: collapsed
@bender-tags: tc, 18, tp1723
@bender-ckeditor-plugins: wysiwygarea, toolbar, clipboard, table, tabletools, selectall, sourcearea, undo, elementspath

## `selectall` integration

Perform steps for each editor.

1. Select multiple cells, e.g. 1x3 selection starting at "Cell 1.1.1" and ending at "Cell 1.3.1".
1. Press "Select all" button.

**Expected:**
Whole editor content is selected.

**Unexpected:**
Table selection is still visible.

Repeat the procedure, but instead of clicking button, use `Cmd/Ctrl+A`.
