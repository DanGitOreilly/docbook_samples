# docbook_samples

This repository contains samples of DocBook source files, for use with our internal build tools.

----
NOTE: If you update any boilerplate in this repo, please update the AsciiDoc version as well:

https://github.com/oreillymedia/asciidoc_samples

and then "git pull" in the checkouts here:

/work/tools/samples/docbook_samples
/work/tools/samples/asciidoc_samples

----

When there's a .pdf as well as .xml version, it's generally a good idea to take a look at the PDF before delving into the source; the PDFs not only show the rendering, but in many cases also have some additional commentary (in red).

Files are organized as follows:

## Boilerplate/skeleton files for common book components

* Standard (provided as "starter files" for authors):
  * book.xml       (model for book with XIncludes)
  * preface/animal/ch00.xml       (model for Animal preface; for other series, use preface/all\_other\_series/ch00.xml)
  * ch01.xml       (model for chapters)
* Optional (copy any of these you need for your book):
  * dedication.xml (model for book with a dedication)
  * foreword.xml   (model for book with a foreword)
  * part1.xml      (model for book organized in Parts)
* Extras (generally for internal use, during later production stages):
  * colophon/\<series\>/colo.xml (colophon)
  * book-docinfo.xml (contains ISBN and author information)

## Further info

Please see the Docbook Authoring Guidelines for further information.

* Docbook Authoring Guidelines (Atlas): http://chimera.labs.oreilly.com/books/1234000000058
* Docbook Authoring Guidelines (Subversion Toolchain): http://chimera.labs.oreilly.com/books/1234000001574
