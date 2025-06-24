
## Basic Math Symbols

| Symbol                | Code          | Rendered          |
| --------------------- | ------------- | ----------------- |
| Equals                | `=`           | \( = \)           |
| Not equal             | `\neq`        | \( \neq \)        |
| Less than or equal    | `\leq`        | \( \leq \)        |
| Greater than or equal | `\geq`        | \( \geq \)        |
| Approximately equal   | `\approx`     | \( \approx \)     |
| Proportional to       | `\propto`     | \( \propto \)     |
| Implies (arrow)       | `\Rightarrow` | \( \Rightarrow \) |
| Logical AND           | `\land`       | \( \land \)       |
| Logical OR            | `\lor`        | \( \lor \)        |

---

## Powers, Roots, and Grouping

| Concept | Code | Rendered |
|--------|------|----------|
| Exponent | `x^2` | \( x^2 \) |
| Subscript | `x_1` | \( x_1 \) |
| Square root | `\sqrt{x}` | \( \sqrt{x} \) |
| nth root | `\sqrt[n]{x}` | \( \sqrt[n]{x} \) |
| Parentheses (auto-resize) | `\left( x \right)` | \( \left( x \right) \) |
| Brackets (auto-resize) | `\left[ x \right]` | \( \left[ x \right] \) |
| Braces (auto-resize) | `\left\{ x \right\}` | \( \left\{ x \right\} \) |

---

## Greek Letters

| Letter | Code | Rendered |
|--------|------|----------|
| Alpha | `\alpha` | \( \alpha \) |
| Beta | `\beta` | \( \beta \) |
| Theta | `\theta` | \( \theta \) |
| Lambda | `\lambda` | \( \lambda \) |
| Sigma (sum symbol) | `\Sigma` | \( \Sigma \) |
| Omega | `\Omega` | \( \Omega \) |

---

## Summation and Limits

| Concept | Code | Rendered |
|--------|------|----------|
| Summation | `\sum_{k=1}^{n} x_k` | \( \sum_{k=1}^{n} x_k \) |
| Limit | `\lim_{x \to \infty}` | \( \lim_{x \to \infty} \) |

---

## Fractions and Derivatives

| Concept | Code | Rendered |
|--------|------|----------|
| Fraction | `\frac{a}{b}` | \( \frac{a}{b} \) |
| Partial Derivative | `\frac{\partial f}{\partial x}` | \( \frac{\partial f}{\partial x} \) |

---

## Integrals

| Type | Code | Rendered |
|------|------|----------|
| Indefinite Integral | `\int x^2 \, dx` | \( \int x^2 \, dx \) |
| Definite Integral | `\int_{a}^{b} f(x)\,dx` | \( \int_{a}^{b} f(x)\,dx \) |

---

## Matrix and Piecewise

| Concept | Code |
|--------|------|
| Matrix | `\begin{bmatrix} a & b \\ c & d \end{bmatrix}` |
| Piecewise Function | `\begin{cases} x^2 & x \geq 0 \\ -x & x < 0 \end{cases}` |

---

## Tips

- Use `\text{}` for inline text inside equations:  
  `\text{Rate} = \frac{1}{t}` → \( \text{Rate} = \frac{1}{t} \)

- Use `\,` for a small space and `\\` to break lines.

---

## Example Combo

```latex
\sum_{k=1}^{n} \frac{1}{k^2} = \frac{\pi^2}{6}