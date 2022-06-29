<!-- Markdown Introduction -->
## Markdown Introduction
---
### What is Markdown?
* Markdown is a lightweight markup language with a plain text formatting syntax
* Can be converted into HTML/XHTML and other formats
* It's main purpose is readability and ease of use

---

### What is it used for?
* Readme Files (Github, etc)
* Forum & Blog Posts
* Used In Many Static Site Generators

---

### Some things you can format
* Headings
* Lists
* Emphasis
* Links
* Blocks of convertedImages
* Blockquotes
* Horizontal Rules

---

### Some Popular Markdown Editors
* TextEditor Extensions (VSCode, Atom, etc)
* MarkPad
* HarooPad
* MarkdownPad2
* Typora

---
---

## Markdown's Syntactic Sugar & Capabilities

---

<!-- Headings -->

### Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

```markup
    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
    ##### Heading 5
    ###### Heading 6
```

---

<!-- Italics -->

### Italics

*This text is italic*

_This_ text is italic

```markdown
    *This text is italic*

    _This_ text is italic
```

---

<!-- Strong -->

### Strong

**This text** is bold

__This text__ is bold

```markdown
    **This text** is bold

    __This text__ is bold
```

---

<!-- Strikethrough -->

### Strikethrough

~~This text~~ is strikethrough

```markdown
    ~~This text~~ is strikethrough
```

---

<!-- Horizontal Rule -->

### Horizontal Rule

---
___

```markdown
    ---
    ___
```

---

<!-- Escape Characters -->

### Escape Characters

In order to escape characters simple add a '\\' in front a special character to markup

<!-- PLEASE NOTE: the double backslash above is only because this is a markdown file -->
<!-- You should only be using one backslash in practice -->

```markdown
    \
```

---

<!-- Blockquote -->

### Blockquote

> This is a blockquote


```markdown
    > This is a blockquote
```

---

<!-- Links -->

### Links

[Markdown Tutorial Link](https://youtu.be/HUBNt18RFbo)

```markdown
    [Markdown Tutorial Link](https://youtu.be/HUBNt18RFbo)
```
<!-- to show add a hover title, put a space add the end of the link with some quotes -->
[Markdown Tutorial Link with Hover Title](https://youtu.be/HUBNt18RFbo "Hello, I'm the hover title")

```markdown
    [Markdown Tutorial Link with Hover Title](https://youtu.be/HUBNt18RFbo "Hello, I'm the hover title")
```

---

<!-- UL -->

### Unordered List

* Item 1
* Item 2
* Item 3
  * Nested Item 1
  * Nested Item 2

```markdown
    * Item 1
    * Item 2
    * Item 3
        * Nested Item 1
        * Nested Item 2
```

---

<!-- OL -->

### Ordered List

1. Item 1
2. Item 2
3. Item 3

```markdown
    1. Item 1
    2. Item 2
    3. Item 3
```

---

<!-- Inline Code Block -->

### Inline Code Block

`<p>This is a codeblock</p>`

```markdown
    `<p>This is a codeblock</p>`
```

---

<!-- Image -->

### Image

![Markdown Logo](https://markdown-here.com/img/icon256.png "Hello, I'm the hover title")

```Markdown
    ![Markdown Logo](https://markdown-here.com/img/icon256.png "Hello, I'm the hover title")
```

---
---

<!-- Github Markdown -->
## GitHub Markdown

---

<!-- Code Blocks -->
### Code Blocks

#### Bash Code
```bash
    npm install

    npm start
```

#### Markdown Code

```
    ```bash
        npm install

        npm start
    ```
```

#### Javascript Code

```javascript
    function add(num1, num2){
        return num1 + num2
    }
```

#### Markdown Code

```
    ```javascript
        function add(num1, num2){
            return num1 + num2
        }
    ```
```

#### Python Code

```python
    def add(num1, num2):
        return num1 + num2
```

#### Markdown Code

```
    ```python
        def add(num1, num2):
            return num1 + num2
    ```
```

---

<!-- Tables -->
### Tables
| Name | Email | Birthday |
|-|-|-|
| John Doe | john@email.com | 01/01/2000 |
| Jane Doe | jane@gmail.com | 01/01/2000 |

```
    | Name | Email | Birthday |
    |-|-|-|
    | John Doe | john@email.com | 01/01/2000 |
    | Jane Doe | jane@gmail.com | 01/01/2000 |
```

---

<!-- Task Lists -->
### Task Lists
* [x] Task 1
* [x] Task 2
* [ ] Task 3

```
    * [x] Task 1
    * [x] Task 2
    * [ ] Task 3
```