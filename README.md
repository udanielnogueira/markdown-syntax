# MarkdownSyntax
💙 Markdown basic syntax.

## Heading

To create a heading, add number signs (#) in front of a word or phrase.

~~~~markdown
# heading 1
~~~~

~~~~markdown
## heading 2
~~~~

~~~~markdown
## heading 3
~~~~

## Heading best practices

Try to put a blank line before and after a heading.

## Paragraphs

Use a blank line to separate one or more lines.

~~~~markdown
I really like using Markdown.
~~~~

## Paragraphs best practices

Unless the paragraph is in a list, don't put tabs or spaces in front of your paragraphs.

## Emphasis

You can add emphasis by making text bold or italic.

### Bold

~~~~markdown
We love **bold text**.
~~~~

~~~markdown
We love __bold text__.
~~~

### Italic

~~~~markdown
We love *italic text*.
~~~~

~~~~markdown
We love _italic text_.
~~~~

### Bold and italic

~~~~markdown
We love ***bold and italic text***.
~~~~

~~~~markdown
We love ___bold and italic text___.
~~~~

## Blockquotes

To create a blockquote, add a > in front of a paragraph.

~~~~markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
~~~~

## Ordered lists

Add line items with numbers followed by periods, you can indent them too. The numbers don’t have to be in numerical order, but the list should start with the number one.

~~~~markdown
1. First item
1. Second item
9. Third item
~~~~

## Unordered lists

Add dashes (-), asterisks (*), or plus signs (+) in front of line items. You can indent one or more items too.

~~~~markdown
- First item
* Second item
+ Third item
~~~~

## Code

To denote a word or phrase as code, enclose it in backticks (`).

~~~~markdown
This is `a bit of code!`
~~~~

## Horizontal rules

Use three or more asterisks (***), dashes (---), or underscores (___).

~~~~markdown
***

---

___
~~~~

## Links

To create a link, enclose the link text in brackets and then follow it immediately with the URL in parentheses.

~~~~markdown
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
~~~~

**Output:**

My favorite search engine is [Duck Duck Go](https://duckduckgo.com)

### Adding titles

You can optionally add a title for a link, this will appear when the user hovers over the link.

~~~~markdown
My favorite search engine [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
~~~~

**Output:**

My favorite search engine [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

### URL and email

To quickly turn a URL or email address into a link, enclose it in angle brackets.

~~~~markdown
<https://www.markdownguide.org>

<fake@example.com>
~~~~

**Output:**

<https://www.markdownguide.org>

<fake@example.com>

## Images

Add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

~~~~markdown
![This is an image](coding.gif "This guy is coding")
~~~~

![This is an image](coding.gif "This guy is coding")

## References

https://www.markdownguide.org/basic-syntax
