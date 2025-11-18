---
title: "How to format an article with Markdown"
date: 2025-10-10T10:00:00+01:00
description: "A Google friendly and short description of the article."
tags: ["tag1", "tag2"]
type: "post"
hero: "https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fstatic001.geekbang.org%2Finfoq%2F9b%2F9b28bd0349f444e4f9cca76ef5772f00.jpeg&f=1&nofb=1&ipt=2a511560b541a94300db0a37697fc160d69f2e877870af4971aff1485f497c5d"
---

This guide provides a comprehensive reference for Markdown syntax, covering all the essential elements you need to create well-formatted documents.

## Headers

Headers are created using hash symbols (`#`). The number of hashes indicates the header level:

```markdown
# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6
```

## Text Formatting

### Bold and Italic

- **Bold text** is created with double asterisks: `**bold**` or `__bold__`
- _Italic text_ is created with single asterisks: `*italic*` or `_italic_`
- **_Bold and italic_** can be combined: `***bold italic***`

### Strikethrough

~~Strikethrough text~~ is created with double tildes: `~~strikethrough~~`

## Lists

### Unordered Lists

Use asterisks, dashes, or plus signs:

```markdown
- Item 1
- Item 2
  - Nested item
  - Another nested item
- Item 3
```

### Ordered Lists

Use numbers followed by periods:

```markdown
1. First item
2. Second item
3. Third item
   1. Nested numbered item
   2. Another nested item
```

## Links

### Inline Links

```markdown
[Link text](https://example.com)
```

### Reference Links

```markdown
[Link text][reference]

[reference]: https://example.com
```

### Automatic Links

```markdown
<https://example.com>
<email@example.com>
```

## Images

```markdown
![Alt text](image-url.png)
![Alt text](image-url.png "Optional title")
```

## Code

### Inline Code

Use backticks for `inline code`: `` `code` ``

### Code Blocks

Use triple backticks with optional language specification:

````markdown
```python
def hello():
    print("Hello, World!")
```
````

## Blockquotes

```markdown
> This is a blockquote.
> It can span multiple lines.
>
> And include multiple paragraphs.
```

## Horizontal Rules

Create horizontal dividers with three or more dashes, asterisks, or underscores:

```markdown
---
---

---
```

## Tables

```markdown
| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |
```

### Table Alignment

```markdown
| Left | Center | Right |
| :--- | :----: | ----: |
| Left | Center | Right |
```

## Task Lists

```markdown
- [x] Completed task
- [ ] Incomplete task
- [ ] Another task
```

## Escaping Characters

Use a backslash to escape special characters:

```markdown
\*not italic\*
\#not a header
```

## Line Breaks

- Single line break: End a line with two spaces
- Paragraph break: Leave a blank line between paragraphs

## Additional Tips

- Use HTML tags when you need more control: `<br>`, `<strong>`, `<em>`, etc.
- Some Markdown processors support extensions like footnotes, definition lists, and more
- Always test your Markdown in the target environment to ensure compatibility
