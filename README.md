Description
Markdown is awesome! All your README.md are made in Markdown, but do you know how GitHub are rendering them?

It’s time to code a Markdown to HTML!

Requirements
All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7 or higher)
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the PEP 8 style (version 1.7.*)
All your files must be executable
All your modules should be documented: python3 -c 'print(__import__("my_module").__doc__)'
Your code should not be executed when imported (by using if __name__ == "__main__":)

Markdown Syntax Cheatsheet
This is a quick reference for Markdown syntax. A more complete guide can be found on GitHub.

Basic Formatting
Bold: **Bold**
Emphasized: *Emphasized*
Strikethrough : ~~Strikethrough~~
Horizontal rules: --- (three hyphens), *** (three asterisks), or ___ (three underscores).
Headings
All heading levels (e.g. H1, H2, etc), are marked by # at the beginning of a line. For example, an H1 is # Heading 1 and an H2 is ## Heading 2. This continues to ###### Heading 6.

Links
Links can be created using several methods:

Links can be [inline](https://markdowntohtml.com)
Inline links can [have a title](https://markdowntohtml.com "Awesome Markdown Converter")
Also, there can be reference links that allow the URL to be placed later in the document:
Here is a [reference link][markdowntohtml] that links to this site.
References are case-insensitive (for example [this link][MarkDownToHTML] works).
References can also [use numbers][1].
Or leave it empty and use the [link text itself].
Also, you can use relative links [like this](../blob/master/LICENSE.txt).
URLs and URLs in angle brackets will automatically get turned into links: https://markdowntohtml.com or <https://markdowntohtml.com>.
URLs for reference links are somewhere later in the document like this
