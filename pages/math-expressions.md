---
category: Markdown
title: Math Expressions
---

# Math Expressions

Use [KaTeX](https://katex.org/docs/supported.html) to write mathematical expressions.

## Inline

Enclose LaTeX code in dollar signs `$ ... $` to display math inline.

For example `≈$≈\int_a^b f(x) = F(b) - F(a)≈$≈` renders inline as $\int_a^b f(x) = F(b) - F(a)$.

## Centred

Enclose LaTeX code in double dollar signs `$$ ... $$` to display expressions in a centred paragraph. For example

```
≈$$≈
f'(a) = \lim_{x \to a} \frac{f(x) - f(a)}{x-a}
≈$$≈
```

renders as

$$
f'(a) = \lim_{x \to a} \frac{f(x) - f(a)}{x-a}
$$