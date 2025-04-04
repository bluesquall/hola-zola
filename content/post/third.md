+++
title = "examples of markdown"
template = "post.html"
date = 2025-04-03

[extra]
selected = true
+++

# examples of markdown

To effectively illustrate the selected color palette and typography of the theme, it is useful to collect examples of markdown elements into a single post.

## color palette

The color palette is [solarized] by Ethan Schoonover. The site will switch between dark & light modes depending on `insert variable here`.

To avoid distracting from the content, *all* text & links are rendered in monotones, unless explicitly ...

### navigation bar (header) & footer

These elements use the (emphasized)/(background highlight) pairing, either `base1/base02` or `base01/base2`.

### accent colors

- monogram
- links
- headings
- `<strong>`

## layout

This theme primarily uses headings and lists for content layout. The notable exception is the main index page (expand on this).

## typography

Serif fonts can be easier to read[^s].

Sans-serif fonts seem to be more popular.

Monospace fonts are useful, especially for (pseudo)code listings.

Font stacks are useful — you can specify your first choice, followed by a prioritized list of fallback fonts.
The theme has the following font stacks:

### basic styles

Here is an unordered list of basic markdown styles:

- *italic*
- _bold_
  - can also be achieved with double asterisks: **bold**
- `code`
- underlined text is reserved for hyperlinks, if you enable old-school mode
- ~~strikethrough~~ probably won't be used much on your website, but I could be wrong.

### links

To underline hyperlinks, like in ancient times, set `old-school = true`. 

### headings

Tufte believes you really only need two levels of headings[^t]. I’m inclined to agree that the necessary number is small, so we’re only going to use three.

### quotes & epigraphs

Blockquotes are useful.

> The two most important days in your life are the day you are born, and the day you find out why.

Include attribution, where appropriate:

> A certain amount of ordinary laziness would lend our culture the pleasant mellowness which it singularly lacks.
> ~ <cite>Alan Watts</cite>

Even better, include attribution with a link to the source:

> Billy Cruiser says that the best navigators are not always certain of where they are, but they are always aware of their uncertainty.
> — <cite>Frank Bama[^f]</cite>
[^f]: Frank Bama is a seaplane pilot, and the fictional protagonist in [*Where is Joe Merchant?* (Buffett, 1992)][wijm]

Perhaps I will get around to implementing these as shortcodes someday.

<!-- Tufte puts these elements to the side (i.e., in the margins) so that they become **TODO**. -->

### notes

This theme includes full support for footnotes[^id] with the standard markdown syntax `[^id]`.

Sometime in the future I may extend it to support sidenotes (e.g., `[^s:id]`) and margin notes (e.g., `[^s:id]`) as in [tufte-css].

## less common elements

These could really be covered in a list, but let's use subsections and expand on each of them, just for giggles.

### unicode symbols

### abbreviation

### subscript & superscript

### kbd

### mark

### hline

I like to separate footnotes and other links under a horizontal break, so here is one.
_____________
[^s]: citation needed
[^t]: citation needed

[solarized]: https://ethanschoonover.com/solarized/
[tufte-css]: https://edwardtufte.github.io/tufte-css/
[wijm]: https://en.wikipedia.org/wiki/Where_Is_Joe_Merchant%3F