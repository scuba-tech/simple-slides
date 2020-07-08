# simple-slides
Create and present simple slideshows through an awesome local implementation of Remark, Markdown, Mermaid, and Katex!

Why? Because, honestly... who *really* wants to deal with office suite formatting changes, spending too-much time making diagrams, and worrying about long-term compatibility and cross-platform editing of presentations?

This implementation allows you to create the slideshow *very* rapidly inside of a single file, refer to any outside assets *if* desired, is offline-portable, and can run on any modern web browser on any operating system (oh, and you can easily export your work to any format down the road!)

## Use
- Download the template HTML file. 
- Open it in browser, and then open it in your text editor of choice. 
- You'll very quickly figure it out. HINT: use markdown, and "---" denotes a new slide. :)

### Formatting
- Main content: Markdown
- Diagrams: Mermaid
- Formulae: KaTeX

### Controls
- Advance slide: **right**, **down**, and **space**
- Previous slide: **left**, **up**
- Fullscreen toggle on selected window: **F**
- Clone Window: **C**
    - yes, original and cloned windows are synchronized
    - great for presenting (P-toggle one, and fullscreen the other)
- Presenter's toggle: **P**
- Help: **H**

### Printing and PDF Exports
- Before printing, be sure to flip through every slide! This ensures that all diagrams, formulae, code blocks, etc. are properly rendered.
  - From there, you can use your browser print menu to Print-to-PDF. Use no margins, and experiment with format-size and background toggles.


## Credits
Although I've put a *lot* of work into this, much of the original source code is from the following awesome projects:
- Remark: https://github.com/gnab/remark <3
- KaTeX: https://katex.org/ <3
- Mermaid: https://mermaid-js.github.io/ <3
- Bellbind's initial online Mermaid implementation: https://bl.ocks.org/bellbind/cbe25c08651ce56637dfb08346a8cfee <3
- The community at StackExchange/Overflow and W3Schools for teaching me how to embed JS, make and modify CSS, and change font references. <3
