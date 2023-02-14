---
title: Syntax Guide
description: Overview of all possible Markdown Syntax in the wiki
published: true
date: 2023-02-14T16:46:35.969Z
tags: 
editor: markdown
dateCreated: 2023-02-14T16:46:35.969Z
---

# Embed images

## Embed images {.tabset}

### Preview

![image with 64x64 pixels](/assets/site/baukasten.png =64x)

The image is embedded directly ![image with 16x16 pixels](/assets/site/baukasten.png =16x) in the text.
The resolution is set to `16x16 pixels` so that it fits well into the text flow.
Without the optional specification of the dimension, the image would be output in full resolution.

### Source code

```markdown
![image with 64x64 pixels](/assets/site/baukasten.png =64x)

The image is embedded directly ![image with 16x16 pixels](/assets/site/baukasten.png =16x) in the text.
The resolution is set to `16x16 pixels` so that it fits well into the text flow.
Without the optional specification of the dimension, the image would be output in full resolution.
```

# Embed images (with spoiler)

## Embed images (with spoiler) {.tabset}

### Preview

<details>

![image in spoiler](/assets/site/baukasten.png)

</details>

### Source code

```markdown
<details>

![image in spoiler](/assets/site/baukasten.png)

</details>
```

# Block quote

## Block quote {.tabset}

### Preview

> This is a regular block quote, also known as a block quote.

> This is a `{.is-info}` block quote.
{.is info}

> This is a `{.is-success}` block quote.
{.is-success}

> This is a `{.is-warning}` block quote.
{.is warning}

> This is a `{.is-danger}` block quote.
{.is-danger}

### Source code

```
> This is a regular block quote, also known as a block quote.

> This is a `{.is-info}` block quote.
{.is info}

> This is a `{.is-success}` block quote.
{.is-success}

> This is a `{.is-warning}` block quote.
{.is warning}

> This is a `{.is-danger}` block quote.
{.is-danger}
```

# Emoji

## Emoji's {.tabset}

### Preview

You can use a variety of emojis such as :palm_tree: or :tea:.

### Source code

```markdown
You can use a variety of emojis such as :palm_tree: or :tea:.
```

### Remarks

> A detailed overview of the supported emojis can be found in this [Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/).
>
> If the website is not accessible, the cheat sheet is also available here as an alternative [image](/assets/site/emojis.png).
{.is info}

# Footnotes

## Footnotes {.tabset}

### Preview

In this text[^1] there are two footnotes[^2].
The footnotes can be found at the very end of each page.

[^1]: This is the 1st footnote.
[^2]: This is the 2nd footnote.

### Source code

```markdown
In this text[^1] there are two footnotes[^2].
The footnotes can be found at the very end of each page.

[^1]: This is the 1st footnote.
[^2]: This is the 2nd footnote.
```

# Horizontal dividing line

## Horizontal separator {.tabset}

### Preview

This text is separated by a horizontal

---

dividing line separated.

### Source code

```markdown
This text is separated by a horizontal

---

dividing line separated.
```

# hyperlinks

## Hyperlinks {.tabset}

### Preview

Hyperlinks can be embedded as [text](/markdown syntax) and as image [![image with 16x16 pixels](/assets/site/baukasten.png =16x)](/markdown syntax).

### Source code

```markdown
Hyperlinks can be embedded as [text](/markdown syntax) and as image [![image with 16x16 pixels](/assets/site/baukasten.png =16x)](/markdown syntax).
```

# List (tasks)

## List (Tasks) {.tabset}

### Preview

- [X] This list entry is complete.
- [ ] This list entry is still to be completed.

### Source code

```markdown
- [X] This list entry is complete.
- [ ] This list entry is still to be completed.
```

# List (numbering)

## List (numbering) {.tabset}

### Preview

1. First entry
2. Second entry
3. Third entry

### Source code

```markdown
1. First entry
1. Second entry
1. Third entry
```

### Remarks

> It is sufficient to number all entries with `1.`.
> When the page is built, the numbering is automatically corrected and counted in the order recorded.
{.is info}

# List (without numbering)

## List (unnumbered) {.tabset}

### Preview

Here is an example of a simple list:
- A simple list item.
- Yet another simple list item.
- And one more simple list item.

Here is an example of a grid list:
- A grid element.
- Yet another grid element.
- And another grid element.
{.grid list}

Here is an example of a specially formatted list for hyperlinks:
- [A hyperlink *with description*](/Markdown syntax)
- [Yet another hyperlink *with additional description*](/markdown syntax)
- [And another hyperlink *also with description*](/Markdown syntax)
{.links-list}

### Source code

```markdown
Here is an example of a simple list:
- A simple list item.
- Yet another simple list item.
- And one more simple list item.

Here is an example of a grid list:
- A grid element.
- Another whiteother lattice element.
- And another grid element.
{.grid list}

Here is an example of a specially formatted list for hyperlinks:
- [A hyperlink *with description*](/Markdown syntax)
- [Yet another hyperlink *with additional description*](/markdown syntax)
- [And another hyperlink *also with description*](/Markdown syntax)
{.links-list}
```

# Source code

## Source code {.tabset}

### Preview

This text contains `inline` source code formatting.

```
This entire block of text is formatted as source code.
```

Example with syntax highlighting:

```csharp
public static void Main(string[] args)
{
Environment.Exit(0);
}
```

### Source code

````markdown
This text contains `inline` source code formatting.

```
This entire block of text is formatted as source code.
```

Example with syntax highlighting:

```csharp
public static void Main(string[] args)
{
Environment.Exit(0);
}
```
````

# Spoilers

## Spoilers {.tabset}

### Preview

<details>
   <summary>Warning: Spoilers</summary>
   This is spoiler text.
</details>

### Source code

```markdown
<details>
   <summary>Warning: Spoilers</summary>
   This is spoiler text.
</details>
```

# Table

## Table {.tabset}

### Preview

| Designation | type | value |
|:--------------- |:-------:| ----:|
| First element | First | 1600 |
| Second element | Second | 12 |
| Third element | Third | 1 |

### Source code

```markdown
| Designation | type | value |
|:--------------- |:-------:| ----:|
| First element | First | 1600 |
| Second element | Second | 12 |
| Third element | Third | 1 |
```

# Tabs

## Tabs {.tabset}

### Preview

The tabs, which can already be seen here on the whole page, should serve as an example.

### Source code

````markdown
## Tabs {.tabset}

### Preview

The tabs, which can already be seen here on the whole page, should serve as an example.

### Source code

```markdown
TEXT
```
````

### Remarks

> The tabs can only be used if the corresponding headings are used.
> As can be seen in the example, the `{.tabset}` element must be appended to a superordinate heading.
> For each tab, a corresponding heading must then be specified one level down, which serves as a tab designation.
{.is info}

# Keyboard icons

## Keyboard symbols {.tabset}

### Preview

Button icons can also be rendered to improve documentation and guides:

<kbd>CTRL</kbd> + <kbd>X</kbd> to cut a content.
<kbd>CTRL</kbd> + <kbd>C</kbd> to copy content.
<kbd>CTRL</kbd> + <kbd>V</kbd> to insert content.

### Source code

```markdown
Button icons can also be rendered to improve documentation and guides:

<kbd>CTRL</kbd> + <kbd>X</kbd> to cut a content.
<kbd>CTRL</kbd> + <kbd>C</kbd> to copy content.
<kbd>CTRL</kbd> + <kbd>V</kbd> to insert content.
```

# Text formatting

## Text formatting {.tabset}

### Preview

This text is **bold**.

This text is *italic*.

This text is <ins>underlined</ins>.

This text is ~~strikethrough~~.

This text is ^superscript^.

This text is ~subscript~.

### Source code

```markdown
This text is **bold**.

This text is *italic*.
This text is _italic_.

This text is <ins>underlined</ins>.
This text is <u>underlined</u>.

This text is ~~strikethrough~~.

This text is ^superscript^.

This text is ~subscript~.
```

### Key combination

<kbd>CTRL</kbd> + <kbd>B</kbd> for **bold**.
<kbd>CTRL</kbd> + <kbd>I</kbd> for **italics**.


# Headlines

## Headings {.tabset}

### Preview

The headings are also used very frequently on this page.

The level of the heading can be specified by using `#`. The less `#`, the higher the level and vice versa.
The syntax can be checked accordingly in the source text tab.

Alternatively, `=` or `-` can also be inserted under the heading.

### Source code

```markdown
# 1st level heading
## 2nd level heading
### Stage 3 heading
#### Level 4 heading
##### Level 5 heading
###### Stage 6 heading

####### This is no longer a headline.

This is an alternative spelling for a level 1 heading
==

This is an alternate spelling for a 2nd level heading
--
```

# Additional

There are other functions that still need to be documented or are provided by plugins.

> Wiki.js supports full markdown syntax.
> Therefore, functions that are not described here should also work (e.g. embedding YouTube videos, etc.).
{.is info}