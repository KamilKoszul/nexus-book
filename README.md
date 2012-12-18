Repository Management with Nexus

Available at http://www.sonatype.com/Support/Books/Repository-Management-with-Nexus

This is the source code and build setup for the book. The content is
written in asciidoc format.  To edit asciidoc, use Emacs, vi, TextMate
or whatever other text editor you prefer.  You can even just preview
the files right in github and edit them on the web interface directly.

The main file for the book is

* book-nexus.asciidoc

which in turn includes a whole bunch of files named 

* chapter-*.asciidoc

These are all you should have to edit in terms of text content.

Figures and screenshots?  

Put them into figs/orig.

The rest is taken care of by the build.

Anything else? 

You'll see a lot of distracting files in that directory.  For now,
you should just ignore them.  Actually, in general, you'll notice a
number of distracting files in this project.  Really, just ignore
them or contact us directly if you need something.

Q: Right, so how do you build the book?

A: I knew you'd ask that, and here's the simple answer:

.. Install asciidoc
.. Install dblatex and the docbook xsl style sheets
.. Install python
.. run ./build.sh

Build is known to work on Mac OS X and Ubuntu. If you use something
else you might or might not end up in trouble.

If you have any suggestions or requests please file an issue at 

https://issues.sonatype.org/browse/NXBOOK

Enhancements can be contributed as pull requests and are very welcome.

Thanks

Sonatype Team
