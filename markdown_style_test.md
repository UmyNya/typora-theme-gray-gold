# Markdown Style Test

A markdown file for style testing.

Reference:

- https://www.markdownguide.org/basic-syntax/
- https://www.markdownguide.org/extended-syntax/
- https://support.typoraio.cn/Markdown-Reference/

## Catalogue

[toc]

## Headings

# Heading level 1 

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

## Paragraphs

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

## Embellish and Emphasize

### Bold

I just love **bold text**.

### Italic

Italicized text is the *cat's meow*.

### Bold and Italic

This text is ***really important***.

### Highlight

This is the ==highlight==.

Highlight with:

- ==**bold**==
- ==*italic*==
- ==<u>underline</u>==
- ==[links]()==

### Underline

This is the <u>underline</u>.		

### Strikethrough

This is ~~Strikethrough~~.

### Subscript

H~2~O

### Superscript

X^2^

### Horizontal Rules

Try to put a blank line before...

---

...and after a horizontal rule.

## Lists

### Ordered Lists

1. First item
2. Second item
3. Third item
   1. Indented item
   2. Indented item
4. Fourth item

### Unordered Lists

- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item

### Task Lists

- [ ] First item
- [x] Second item
- [ ] Third item
  - [ ] Indented item
  - [x] Indented item
- [ ] Fourth item

## Blockquotes

### Blockquotes with Multiple Paragraphs

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Nested Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Blockquotes with Other Elements

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

## Code Blocks

A inline code block is as follows:

- Use `code` in your Markdown file.

- ``Use `code` in your Markdown file.``

And a multi-line code block is as follows:

```cpp
#include <iostream>

int main() {
    int str = "Hello, World!";
    std::cout << str << std::endl;
    return 0;
}
```

## Math Blocks

A inline math block is as follows:

- The area of a circle is calculated using the formula $A = \pi r^2$, where $A$ represents the area and $r$ is the radius.

And a multi-line math block is as follows:

$$ \mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ \frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\ \frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\ \end{vmatrix} $$

## Links

### Common Links

https://duckduckgo.com

### Adding Titles

My favourite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

### URLs and Email Addresses

<https://www.markdownguide.org>

<fake@example.com>

### Formatting Links

I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

## Images

![The San Juan Mountains are beautiful!](markdown_style_test.assets/san_juan_mountains.jpg "San Juan Mountains")

## Table

| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here’s this |
| Paragraph |    Text     |    And more |

## Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^big_note]

[^1]: This is the first footnote.
[^big_note]: Here’s one with multiple paragraphs and code.<br /> Indent paragraphs to include them in the footnote.<br />`{ my code }`<br />Add as many paragraphs as you like.

