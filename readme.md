mdtoc
=====

A little Markdown filter that scans your document for headings,
numbers them, adds anchors, and inserts a table of contents.

To use it, make sure the headings you want numbered and linked are
in this format:

    ### Title ###

I.e. they must have an equal number of octothorpes around the title
text. (In Markdown, `#` means `h1`, `##` means `h2`, and so on.)
The table of contents will be inserted before the first such
heading.

Then run:

    ./mdtoc.rb src.md | markdown

Released into the public domain.
Sam Stephenson <sstephenson@gmail.com>
2011-04-30
