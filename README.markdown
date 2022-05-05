# acme4real

A Vim (and Pandoc) colorscheme heavily inspired by acme(1) by Rob Pike,
but with actual syntax-highlighting.

## Screenshots (Vim)


|![img/shot_04-05-22_181515.jpg](img/shot_04-05-22_181515.jpg)|
|:--:|
|*Editing a program written in Go.*|

|![img/shot_04-05-22_180932.jpg](img/shot_04-05-22_180932.jpg)|
|:--:|
|*Editing a program written in Shell script for the GNU Bourne-Again Shell.*|

|![img/shot_04-05-22_182152.jpg](img/shot_04-05-22_182152.jpg)|
|:--:|
|*Editing a Markdown document, in Portuguese with UTF-8 support.*|

## The Pandoc port

I have created a Pandoc port of acme4real when I was compiling the
[Copacabana](http://copacabana.pindorama.dob.jp) *tabula* (a.k.a.
"Copacabana Linux documentation") from Markdown to HTML, with deploying
it online in mind. After testing a couple of syntax highlighting themes,
I figured out that none of them had, in fact,
[Pindorama](http://pindorama.dob.jp)'s visual identity as acme4real itself.  
Then, I decided that it was worth wasting some hours reading documentation
about [Skylighting](https://github.com/jgm/skylighting) (the syntax highlighting engine using by Pandoc) and
[KDE/Kate theming](https://docs.kde.org/trunk5/en/kate/katepart/highlight.html#katehighlight-xml-format)
(since Skylighting uses KDE-style syntax highlighting themes).  

Thanks for Tristano Ajmone (``@tajmone``) and for some other contributors for the
terrific "[Pandoc Goodies](https://github.com/tajmone/pandoc-goodies)"
repository, which documents and makes some notes on Pandoc extra features, such
as macros, templates and, of course, syntax highlighting via the Skylighting
library.  

### Screenshots (Pandoc port)

|![img/2022-05-04_21.25.16__03b2ca6e3a2a.jpg](img/2022-05-04_21.25.16__03b2ca6e3a2a.jpg)|
|:--:|
|*A Shell script snippet, in a HTML documment rendered via Vivaldi 5.2.2623.41 stable; the text is in Portuguese, with UTF-8 support.*|

## Licence

Volkerding's Slackware licence (similar in spirit to ISC).
