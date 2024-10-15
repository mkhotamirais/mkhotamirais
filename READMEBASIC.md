# README BASIC

## Table of Content
- [ExternalLink](#external-link)
- [Typography](#typography-and-links)
- [Colors](#colors)
- [Images](#images)
- [Lists](#list)
- [Using Emojis](#using-emojis)
- [Alerts](#alerts)
- [Comments](#comments-and-ignoring-markdown)



## External link
- [Reference of this Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Keyboard shortcuts](https://docs.github.com/en/get-started/accessibility/keyboard-shortcuts)



## Typography and Links
# heading 1
## heading 2
### heading 3

> quoting text using >

quoting code within single backtic `quoting code` like that.
```
use triple backtics to format code or text into its own distinct block
npm install
```

Paragraph: use `extra enter` to start the next paragraph.

Paragraph: use `tab or extra space` at the end of the line to start the new text line.

**bold** or __bold__; *italic* or _italic_; ~~strikethrough~~; **bold and _nested italic_**; **_all bold italic_**; <sup>superscript</sup>; <sub>subscript</sub>

Link, there are three kind of link, link to external link [go to google](https://google.com), section links [linke table of content](#table-of-content) and dinamic link [path of current repo](index.html). Additionally you can use custom anchor <a href="https://google.com">go to google</a> but not considered by the automatic naming and numbering behavior of automatic heading links.

you can mention a person or team by typing `@` plus their username

Here is a simple footnote[^1].  
A footnote can also have multiple lines[^2].




## Colors
hex `#0969DA` rgb `rgb(9, 105, 218)` hsl `hsl(212, 92%, 45%)`



## Images
Use ! then [alt] then (url) [more information](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#uploading-assets)

![Octocat smiling and raising a tentacle](https://myoctocat.com/assets/images/base-octocat.svg)

You can specify image depend on your device theme:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>



## List
- using -
- using -
* using *
* using *
+ using +
+ using +
1. using 1
2. using 2
    - nested list by indenting
        + like this
        * and this
    - back to the list
3. using 3
- [ ] #234
- [x] task list using - [x]
- [ ] task list using - []
- [more information about task list](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists)




## Using emojis
You can add emoji to your writing by typing `:EMOJICODE:` like this 👍 and :cat2: and others. see [the emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)



## Alerts
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.



## Comments and ignoring markdown
comment in markdown like comment in html
<!-- like this -->
to ignore markdown formatting you can use `\` before the makrdown character like this *italic* and \*italic markdown\*. [see more markdown syntax](https://daringfireball.net/projects/markdown/syntax#backslash)



## Footnotes
[^1]: My reference.  
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.