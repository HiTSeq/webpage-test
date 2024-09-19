# webpage-test
Testing version of the webpage. You can see the webpage at [https://www.hitseq.org/webpage-test/](https://www.hitseq.org/webpage-test/)

When not in use for development, website is disabled in github repo settings, section Pages.

Important files shared among subpages:

* `_layouts/default.html` Overall layout of the page
* `_includes/head.html`  `<head>` element of the page
* `_includes/header.html` Top part of the page with menu and logo
* `_includes/sidebar.html` Sidebar with important dates
* `_includes/footer.html` Footer of the page

All submages are in `.md` (Markdown) files. For now they are in HTML as on the original website, although Markdown markup can be used as well. 

If you use HTML in Markdown files, outermost HTML block (e.g. div) must start and end at the left margin and inside the block must be indented.
Blank lines should be before and after it.

