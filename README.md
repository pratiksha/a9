r9
==

**r9** (*remembered*) is a web-based note-taking application.

It is basically (Evernote basic functionalities) + (LaTeX support) - (upload limit).

Features
--------

With r9, you can ...

* edit and preview a [Markdown](http://daringfireball.net/projects/markdown/) document at the same time
* save the document in Markdown format, which can be opened directly by other editors
* organize documents into "books" like in [Evernote](https://evernote.com/)
* print documents in full-page format
* customize styling by editing the CSS files
* insert LaTeX formulas using `$..$` and `$$..$$` — the equations will be displayed using [MathJax](http://www.mathjax.org/)
* draw simple graphics (like graphical models) with special SVG hacks (to be documented)

The documents are saved locally.
To sync or back up the documents, use [an existing sync or backup service](http://alternativeto.net/category/backup-and-sync/).

Screenshot
----------

![r9 screenshot](/../screenshot/static/images/screenshot.png?raw=true "r9 screenshot")

Requirements
------------

Python 2.7 and a modern browser (i.e., not IE <= 8)

Setup
-----

Run `server.py` either by double-clicking the icon or invoking through a terminal.
