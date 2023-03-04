# Web Apps

Web Apps Presentation for the University of Sussex.

## Install

To recreate the html slideshows from the source [Markdown](https://en.wikipedia.org/wiki/Markdown), first clone this repository, then install [pandoc](https://pandoc.org/). Finally, change to the [presentation](/presentation) subdirectory, and run:

`pandoc -s --webtex -i -t slidy webapps.md --css webapps.css -o webapps.html`

You can then open _webapps.html_ in your favourite browser.

## Licence

GNU General Public Licence v3.0

See [LICENCE](/LICENCE.txt) to see the full text.
