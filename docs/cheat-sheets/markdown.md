# Markdown - Cheat Sheet

This file contains some basic syntax information about Markdown, a text-to-HTML conversion tool.

For the full documentation refer to the [official page](https://daringfireball.net/projects/markdown/).

------------
## Table of Contents
- [Headings](#headings)
- [Lists](#lists)
- [Tasks](#tasks)
- [Links](#links)
- [Images](#images)
- [Code Blocks](#code%20blocks)
- [Tables](#tables)
- [License](#license)

------------
## Headings

There are six different headings in Markdown that can be used for titles and subtitles.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```


[back to top](#table%20of%20contents)

------------
## Lists

There are ordered and unordered lists that can be used in Markdown. There is also the option of nested list using tabs.

#### Ordered Lists
```markdown
1. Item 1
2. Item 2
3. Item 3
    1. Item 3.1
4. Item 4
```

#### Unordered Lists
```markdown
- Item 1
- Item 2
- Item 3
    - Nested Item
- Item 4
```

[back to top](#table%20of%20contents)

------------
## Tasks

Tasks in Markdown allows you to create checkboxes that can be checked or unchecked.

```markdown
- [ ] Item 1
- [x] Item 2
- [ ] Item 3
```

[back to top](#table%20of%20contents)

------------
## Links

You can create links to websites, other Markdown files in your local machine or sections in your Markdown file.

#### External Links
```markdown
[Link text](URL)
```

### Project Links
```
[Link text](path/to/your/file-name.md)
```

#### Section Links

A link to the section ID is required to accomplise this link. This is automatically generated.

##### GitHub Example
```markdown
[Example](#example)
[Example with Multiple words](#example-with-multiple-words)
```

##### Obsidian Example
```markdown
[Example](#example)
[Example with Multiple words](#example%20with%20multiple%20words)
```

[back to top](#table%20of%20contents)

------------
## Images

You can add images to your documents using the following syntax:
```markdown
![Alt text](path-to-image.png)
```

[back to top](#table%20of%20contents)

------------
## Code Blocks

You can create code blocks with syntax highlighting for specific programming languages, using the triple backticks followed by the name of the language.

<pre>
```python
print("Hello, world!")
```
</pre>

[back to top](#table%20of%20contents)

------------
## Tables

You can create tables using the following syntax:

```markdown
| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Row 1, Column 1 | Row 1, Column 2 | Row 1, Column 3 |
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3 |
```

You can also align the text of each cell:
```markdown
| Left-aligned | Center-aligned | Right-aligned |
| :----------- | :------------: | ------------: |
| Left         | Center         | Right         |
```

There is also the option of Markdown formatting inside the cells:
```markdown
| Column 1 | Column 2 |
| -------- | -------- |
| *Italic* | **Bold** |
```

[back to top](#table%20of%20contents)

------------
## License

CARS-obsidian is distributed under the MIT license. You should have received a [copy](LICENSE) of the MIT License along with this program. If not, see https://mit-license.org/ for additional details.

[back to top](#table%20of%20contents)