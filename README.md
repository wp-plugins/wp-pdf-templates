Wordpress PDF Templates
=====================

This plugin utilises the DOMPDF Library to provide a simple URL endpoint (e.g. http://my-site.com/my-post/pdf/) that generates a downloadable PDF file.

If pretty permalinks are disabled. GET parameters (e.g. ?p=1&pdf) can be used instead.

The PDF output can be customised by copying the index-pdf.php file from the plugin directory to your theme and creating your own custom template for PDF prints.

Stylesheets used on the site are disabled by default, but you can define your own stylesheets within the index-pdf.php file. PDF Templates can be previewed as raw HTML at the /pdf-preview URL endpoint.

For further information see **readme.txt**.

## Installation

1. Download and activate the plugin.
2. Installation done! You can now navigate to any post or page on your website and append /pdf/ (or &pdf if not using pretty permalinks) to the URL to view a glorious PDF version of it.

