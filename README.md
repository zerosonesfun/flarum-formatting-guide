Use Markdown or BBcode to add formatting. The toolbar will help you add common Markdown which involves adding certain special characters in front of or around your text, such as: `**bold**`, `*italics*`, `~~strike~~`, `>!spoiler!<`, `[link text](url)`, and `![alt text](image url)`.

BBcode is a common bracket style code that wraps your text, such as: `[b]bold[/b]`, `[i]italics[/i]`, `[s]strike[/s]`, `[url=]link text[/url]`, and `[img]url[/img]`.

Below you will find additional options and examples.
- - -

### Markdown
#### Block elements

#### Blockquotes

A line that starts with a right angle bracket `>` (optionally followed by a space) is a blockquote. Blockquotes can be nested but they can't be used inside of lists. Consecutive blockquotes can be separated with two blank lines.

```md
> > Deep blockquote
>
> Shallower blockquote

No blockquote
```
Example:
> > Deep blockquote
>
> Shallower blockquote

No blockquote

#### Lists

`*`, `-` and `+` for unordered lists, or any number of digits followed by a dot such as `1.` for an ordered list. The list item must be followed by a space then at least one character. Lists can be nested and can be used inside of blockquotes.

The indentation inside of nested lists emulates the behaviour of the original Markdown, meaning that sublists after the first should be indented by 4 spaces or a tab.

If a list has any of its text content or list items separated with a blank line, each of its items' content is wrapped in a paragraph. Consecutive lists can be separated with two blank lines.

Ordered:
```md
1. Collect
2. **?**
3. Profit
```
Example:
1. Collect
2. **?**
3. Profit

Unordered:
```md
- Collect
- **?**
- Profit
```
- Collect
- **?**
- Profit

#### Indented code blocks

A series of lines indented by at least 4 spaces or a tab, preceded with an empty line.

```
Check out this program:

    10 PRINT "Hello"
	20 GOTO 10
```

#### Fenced code blocks

A series of lines between two markers composed of at least 3 consecutive <code>&#96;</code> or `~` and identical in length. The name of the programming language can be appended to the first marker.

#### Spoilers

Block spoilers are similar to blockquotes and follow the same rules as blockquotes. Block spoilers use `>!` as opening markup instead of `>`. Subsequent lines can be started with `>`.

```md
>! >! Super spoiler
>!
>! Spoiler

No spoiler
```
Example:
>! >! Super spoiler
>!
>! Spoiler

No spoiler

#### Headers

```md
This is an H1
=============

This is an H2
-------------
```
Example:
This is an H1
=============

This is an H2
-------------

```md
# This is an H1

## This is an H2

###### This is an H6
```
Example:
# This is an H1

## This is an H2

###### This is an H6

### Horizontal rules

Each of those creates an horizontal rule.
```
* * *

***

*****

- - -

---------------------------------------
```

#### Paragraphs and line breaks

Paragraphs are automatically created. Newlines are ignored by default, line breaks can be forced by ending a line with two spaces.

```md
normal
forced  
another line
```
### Formatting elements

#### Links

Note that special characters inside links can be escaped with a backslash.

```md
[Link text](http://example.org)
[Link text](http://example.org "Link title")
[Link text](http://example.org 'Link title')
[Link text](http://example.org (Link title))
[Mars](http://en.wikipedia.org/wiki/Mars_(disambiguation))
[Mars](http://en.wikipedia.org/wiki/Mars_\(disambiguation\))
```
Example:
[Link text](http://example.org)
[Link text](http://example.org "Link title")
[Link text](http://example.org 'Link title')
[Link text](http://example.org (Link title))
[Mars](http://en.wikipedia.org/wiki/Mars_(disambiguation))
[Mars](http://en.wikipedia.org/wiki/Mars_\(disambiguation\))

#### Emphasis

A pair of `*` or `_` around non-whitespace text marks emphasis (`<em>`) while a pair of `**` or `__` marks strong emphasis (`<strong>`). One exception: a single `_` between two ASCII alphanumerical characters is kept as-is.

```md
un*frigging*believable

***ON SALE!***

a * b = b * a

perform_complicated_task()
```
Example:
un*frigging*believable

***ON SALE!***

a * b = b * a

perform_complicated_task()

When a block of three `*` or `_` is found, the order of strong/em depends on the next series of `*` or `_` characters.

```md
***foo* bar**

***foo** bar*
```
Example:
***foo* bar**

***foo** bar*

#### Inline spoilers

Any text between `>!` and `!<` or between `||` and `||`. Unlike block spoilers, they can be used anywhere on a line.

```md
This is a Reddit-style >!spoiler!<.
This is a Discord-style ||spoiler||.
```
Example:
This is a Reddit-style >!spoiler!<.
This is a Discord-style ||spoiler||.

#### Strikethrough

Any text between two `~~` markers.

```md
90s haircuts are ~~cool~~ ~~lame~~ cool again.
```
Example:
90s haircuts are ~~cool~~ ~~lame~~ cool again.

#### Subscript and superscript

```md
x^2
x^2^
x^(n - 1)
x^(n^2)
x^(n^(2))
H~2~O
H~(2)O
```
Example:
x^2
x^2^
x^(n - 1)
x^(n^2)
x^(n^(2))
H~2~O
H~(2)O

#### Inline code

Any text between two markers of same length, entirely composed of backticks <code>&#96;</code> and neither preceded or followed by a backtick. Leading and trailing whitespace is removed. The backslash does not escape characters inside of a code span.

```md
Single `print("``")` or double ``print("`")``
```
Example:
Single `print("``")` or double ``print("`")``

### Inline elements

#### Images

```md
![](http://example.org/img.png)
![Alt text](http://example.org/img.png)
![Alt text](http://example.org/img.png "Image title")
[![Alt text](http://example.org/img.png)](http://example.org/)
```
Example:
![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Malus_domestica_a1.jpg/1200px-Malus_domestica_a1.jpg)
![Flowers](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Malus_domestica_a1.jpg/1200px-Malus_domestica_a1.jpg)
![Flowers](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Malus_domestica_a1.jpg/1200px-Malus_domestica_a1.jpg "Flowers")
[![Flowers](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Malus_domestica_a1.jpg/1200px-Malus_domestica_a1.jpg)](#)
- - -
### BBCode
The following BBCodes are available.

`[b]bold[\b]` Example: [b]bold[/b]
`[i]italics[/i]` Example: [i]italics[/i]
`[u]underline[/u]` Example: [u]underline[/u]
`[s]strike[/s]` Example: [s]strike[/s]
`[url=#]link[/url]` Example: [url=#]link[/url]
`[email]email@invalidmail.com[/email]` Example: [email]email@invalidemail.com[/email]
`[code]<html><?php echo "ok"; ?></html>[/code]`
Example: [code]<html><?php echo "ok"; ?></html>[/code]
`[quote]You may quote me on this.[/quote]`
Example: [quote]You may quote me on this.[/quote]

`[list]
[*]item 1[/*]
[*]item 2[/*]
[/list]`

Example: 
[list]
[*]item 1[/*]
[*]item 2[/*]
[/list]

`[del]delete/strike[/del]` Example: [del]delete/strike[/del] (`[s][/s]` works too)
`[color=red]red[/color]` Example: [color=red]red[/color]
`[center]center[/center]` Example: [center]center[/center]
`[size=20]size[/size]` Example: [size=20]size[/size]

`[img]http://example.org/img.png[/img]` Example:

[img]https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Malus_domestica_a1.jpg/1200px-Malus_domestica_a1.jpg[/img]

*Above documentation is a modified version of the original [TextFormatter](https://github.com/s9e/TextFormatter) documentation for Markdown and BBCode.*

*Flower image above by Opioła Jerzy (Poland) [CC BY 2.5](https://creativecommons.org/licenses/by/2.5 "Creative Commons Attribution 2.5"), [Link](https://commons.wikimedia.org/w/index.php?curid=772504).*
