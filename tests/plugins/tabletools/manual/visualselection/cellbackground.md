@bender-ui: collapsed
@bender-tags: tc, 258, 4.7.0, tp2247
@bender-ckeditor-plugins: wysiwygarea, toolbar, table, tabletools, elementspath

1. Select two cells in the first row.

	## Expected

	Custom table selection is visible on both cells.

	## Unexpected

	Second cell doesn't have background changed.

1. Click outside of the editor to blur it.

	## Expected

	Custom table selection is consistent.

	## Unexpected

	Second cell has a different background color.
