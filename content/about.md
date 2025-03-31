# About This Project

This project is a documentation website built using [Hugo](https://gohugo.io/), a static site generator. The content is written in [Markdown](https://www.markdownguide.org/), and the project is managed using [Git](https://git-scm.com/), often with a platform like [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), or [Bitbucket](https://bitbucket.org/). This document will help you understand how the project is structured, how to contribute, and how to ***see your changes live***.

## Project Structure

The project has the following basic structure:

```markdown
+ kpi-okr-docs/
    + content/          # Contains the Markdown files with the documentation content
        - _index.md     # The main page of the site
        - project-management-metric.md
        - code-quality-metric.md
        - testing-metric.md
        - performance-metric.md
        - user-metric.md
    * layouts/          # HTML templates that define the structure of the pages
    * static/           # Static assets like images, CSS, and JavaScript
    * themes/           # Hugo theme
    * hugo.toml         # Hugo configuration file
    * .gitignore        # Specifies files that Git should ignore
```

## Working with Markdown

The content of the documentation is written in Markdown. Markdown is a simple and easy-to-learn markup language. Here are some basic Markdown syntax examples:

### Headings

Headings from `h1` through `h6` are constructed with a `#` for each level:

```markdown
# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading
```

### Paragraphs and Line Breaks

Paragraphs are written as normal, plain text will be wrapped with `<p></p>` tags in the rendered HTML.


```markdown
This is a paragraph.

This is another paragraph.
To force a line break, use two spaces and then press Enter.

Lorem ipsum dolor sit amet, graecis denique ei vel, at duo primis mandamus. Et legere ocurreret pri, animal tacimates complectitur ad cum. Cu eum inermis inimicus efficiendi. Labore officiis his ex, soluta officiis concludaturque ei qui, vide sensibus vim ad.
```

### Bold and Italic

```markdown
**Bold text**
*Italic text*
**Bold and *italic* text**
~~Strike through this text.~~
```

### Blockquotes

For quoting blocks of content from another source within your document.

Add `>` before any text you want to quote.

```markdown
> **Fusion Drive** combines a hard drive with a flash storage (solid-state drive) and presents it as a single logical volume with the space of both drives combined.
```

### Links

```markdown
[Link to Google](https://www.google.com)
```

### Lists

An unordered list of items in which the order of the items does not explicitly matter.

You may use any of the following symbols to denote bullets for each list item:

```markdown
* Item 1
* Item 2
+ Item 3
    - Item 3.1
    - Item 3.2
+ Item 4
    - Item 4.1
```

An ordered list of items in which the order of items does explicitly matter.

```markdown
1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
```

### Images

Images have a similar syntax to links but include a preceding exclamation point.

```markdown
![Minion](https://octodex.github.com/images/minion.png)
```
