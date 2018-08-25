# Headless Chrome Examples

## Dealing with header/footer
Chrome adds a header and footer by default to the printed pdf page.  To remove
this header use this section in the html head:

	<style>
	@media print {
	  @page { margin: 0; }
	  body { margin: 1.6cm; }
	}
	</style>

## Paths
For local files, use absolute paths which Chrome can find.
