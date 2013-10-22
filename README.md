deck.js-pandoc-slides
=====================

# Instalation and how to use

## Dependencies

- [Pandoc 1.11.1](http://johnmacfarlane.net/pandoc/) (needs to be installed)
- [Deck.js](http://imakewebthings.com/deck.js/) (included)

## Creation

- First copy the doc folder and rename it as you like. This is not necessary but
  helps you organize your documents.

- Create the md files that you want to generate. The md files are
  [Markdown](http://en.wikipedia.org/wiki/Markdown) files which are nothing more
  than plain text files with extension md, and a lightweight markup (we should
  know it but it is very simple).

- Once created the md files, can generate docx, html, pdf, beamer and slides with a script.

## Build

- To build docx, html, pdf, beamer and slides from md, go to the root folder and execute:

~~~
   ./build.sh - To convert all md files of all the folders
~~~

~~~
   ./build.sh [folder_name] - To convert all md files of one folder
~~~

## Slide keyboard shortcuts

~~~
                    [F] - Find text
                    [M] - Miniature slides
                    [G] - Go to slide number
                    [P] - Pointer mouse
             [ctrl]+[+] - Zoom in
             [ctrl]+[-] - Zoom out
   [ctrl]+[wheel mouse] - Zoom in/out
                [space] - Next page
                [intro] - Next page
              [page up] - Next page
             [up arrow] - Next page
          [right arrow] - Next page
            [backspace] - Previous page
            [page down] - Previous page
           [down arrow] - Previous page
           [left arrow] - Previous page
~~~
