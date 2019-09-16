# Cheat sheet for various Markdown/-up/-sideways/-back/… implementations

Original Idea by [@michaeldexter](https://twitter.com/michaeldexter/status/1173663111644991491).

Currently:

-   [Vanilla Markdown](https://daringfireball.net/projects/markdown/syntax)
-   [GitHub](https://guides.github.com/features/mastering-markdown/)
-   Riot
-   [Slack](https://get.slack.help/hc/en-us/articles/202288908-Format-your-messages)

## Simple formatting

###  Vanilla Markdown

```
*emphasis* **strong** ***strong emphasis***
```

### GitHub

```
*emphasis* **strong** ***strong emphasis***

_emphasis_ __strong__ ___mixed__ bag_
```

*emphasis* **strong** ***strong emphasis***

_emphasis_ __strong__ ___mixed__ bag_

### Riot

```
*emphasis* **strong** ***strong emphasis***
```

### Slack

```
_emphasis_ *strong* ~strikethrough~
```

## Blockquotes

### Vanilla Markdown

```
> This be a quote
```

### GitHub

```
> This be a quote
```

> This be a quote

### Riot

```
> This be a quote
```

### Slack

```
> This be a quote
```

## Code / Preformatted text

### Vanilla Markdown

```
This is an example of `inline code`

    Four spaces denote a code block
    No syntax highlighting
```

### GitHub

```
This is an example of `inline code`

    Four spaces denote a code block

\```
Alternatively you can surround the code block with triple backticks
\```

\```c
#include <stdio.h>

int main ()
{
  printf("Also supports syntax highlighting!\n");
  return 0;
}
\```
```

This is an example of `inline code`

    Four spaces denote a code block

```
Alternatively you can surround the code block with triple backticks
```

```c
#include <stdio.h>

int main ()
{
  printf("Also supports syntax highlighting!\n");
  return 0;
}
```

### Riot

```
This is an example of `inline code`

    Four spaces denote a code block
    No syntax highlighting
```

### Slack

```
This is an example of `inline code`

\```
Blocks are marked with with triple backticks
\```
```

## Headers

### Vanilla Markdown

```
# Heading 1

## Heading 2

Heading 1
=========

Heading 2
---------
```

### GitHub


```
# Heading 1

## Heading 2

Heading 1
=========

Heading 2
---------
```

### Riot

```
# Heading 1

## Heading 2
```

### Slack

Not implemented

## Numbered Lists

### Vanilla Markdown

```
1.   First item
1.   Second item
1.   Third item
1.   Fourth item
```

### GitHub

```
1.   First item
1.   Second item
1.   Third item
1.   Fourth item
```

1.   First item
1.   Second item
1.   Third item
1.   Fourth item

### Riot

```
1.   First item
1.   Second item
1.   Third item
1.   Fourth item
```

### Slack

```
1.   First item
1.   Second item
1.   Third item
1.   Fourth item
```

## Unordered Lists

### Vanilla Markdown

```
-   Item
-   Item
-   Tiem
-   Meti
```

### GitHub

```
-   Item
-   Item
-   Tiem
-   Meti
```

-   Item
-   Item
-   Tiem
-   Meti

### Riot

```
-   Item
-   Item
-   Tiem
-   Meti
```

### Slack

```
-   Item
-   Item
-   Tiem
-   Meti
```
