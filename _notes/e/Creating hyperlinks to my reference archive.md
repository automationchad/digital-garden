It should be easy to make durable, human-readable links to resources in my reference archive.

For instance, when referring to a paper, it’d be nice to link to the PDF—possibly to link to a particular page. I could use a `file://` URL for this, but this poses several problems:

- the file may move around on my system
- I can’t link to a specific page
- the URL would probably be illegible
- this definitely won’t work on iOS

It’d be much nicer to link to a custom scheme (e.g. `ammref://`) which can

- redirect references to concrete files
    - possibly fulfilling them if needed
- avoid tying me to any file system structure or reader apps
- support legible URLs; e.g.
    - `ammref://Hattie/1994/VisibleLearning#p57`

This is pretty doable. It would mean:

- [ ] making a simple script which searches for compatible references
- [ ] making a script which gets a URL for a reference
- [ ] making Alfred workflows to run the latter

---

## References

[Custom Skim URLs](http://www.dansheffler.com/blog/2014-07-02-custom-skim-urls/)

> I wanted to be able to link to any page of a PDF in my Markdown notes, and I knew that I could do it by appending #35, for example, to the end of a file:// URL in my browser. But I use [Skim](http://skim-app.sourceforge.net/) , and reading PDFs in a browser is no good. Further, the URLs end up being super long with ugly things like %20 for spaces and this seemed unnecessary because all my PDFs are carefully organized with [BibDesk](http://bibdesk.sourceforge.net/) . So I set up a little AppleScript that would parse a custom URL starting with sk:// for a BibDesk citekey and a page index, then figure out which PDF I want from BibDesk and open that PDF in Skim to the right page index.

URNs may be relevant in the design: [Uniform Resource Name - Wikipedia](https://en.wikipedia.org/wiki/Uniform_Resource_Name)
