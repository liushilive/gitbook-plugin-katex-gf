# Math typesetting using KaTex (Global function)

Use it for your book, by adding to your book.json:

```json
{
    "plugins": ["katex-gf"]
}
```

then run `gitbook install`.

## Usage

<https://khan.github.io/KaTeX/function-support.html>

```html
Inline math: $$\int_{-\infty}^\infty g(x) dx$$

Block math:

$$
\def\arraystretch{1.5}
\begin{array}{c|c:c}
   a & b & c \\ \hline
   d & e & f \\
   \hdashline
   g & h & i
\end{array}
$$

$$\fcolorbox{red}{aqua}{A}$$

$$\textcolor{#228B22}{F=ma}$$

Or using the templating syntax:

{% math %}\int_{-\infty}^\infty g(x) dx{% endblock %}
```

### Comparison with [MathJax](https://github.com/GitbookIO/plugin-mathjax)

- Faster
