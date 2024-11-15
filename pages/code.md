---
category: Markdown
title: Code
---

# Code

## Inline Code

```
This is some `inline code`.
```

This is some `inline code`.

<br>

```
This is some ``inline code with `backticks` ``
```

This is some ``inline code with `backticks` ``

## Block Code

use either

- three backticks ` ``` `,
- three tildes `~~~`,
- four backticks ` ```` ` (if the code block should contain three back ticks) or
- 4 spaces indentation.

```
some block code
some block code with ≈highlighting≈
some block code with ≈highlighting≈
some block `code`
some block code with      # a comment
some block code with      # a ≈hightlighted≈ comment
some block code with      # a comment containing `code`
```
## ASCII Block Code

code blocks annotated by `ascii` use a different font and reduced line height

### Markdown

````
```≈ascii≈

    +----------------+   Send    +-------+   ≈≈≈Subscribe≈≈≈    +---------------------+
    |  Event Source  |---------->|  ESP  |<---------------|  ≈`≈Event Destination≈`≈  |
    |                |           |       |--------------->|                     |
    +----------------+           +-------+   Consume      +---------------------+

```
````
### Output

```ascii

    +----------------+   Send    +-------+   ≈Subscribe≈    +---------------------+
    |  Event Source  |---------->|  ESP  |<---------------|  `Event Destination`  |
    |                |           |       |--------------->|                     |
    +----------------+           +-------+   Consume      +---------------------+

```
