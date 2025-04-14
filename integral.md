### 区间再现

$$
\begin{align}
&\int_{a}^{b} f(x)dx \\
=&\int_{a}^{b} f(a+b-x)dx \\
=&\int_{a}^{\frac{a+b}{2}} f(x)+f(a+b-x)dx \\
=&\int_{\frac{a+b}{2}}^{b} f(x)+f(a+b-x)dx \\
=&\frac{1}{2}\int_{a}^{b}f(x)+f(a+b-x)dx
\end{align}
$$

---

### 换区间
$$
\int_{0}^{+\infty} f(x)dx=\int_{0}^{1} \left [ f(x)+f(\frac{1}{x})\frac{1}{x^2} \right ]dx
$$

