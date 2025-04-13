### 积分不等式

Cauchy不等式

$$
\int_{a}^{b}f^2(x)dx \int_{a}^{b}g^2(x)dx \ge \left ( \int_{a}^{b}f(x)g(x)dx \right ) ^2
$$

---
均值不等式

$$
ln \left ( \frac{1}{b-a} \int_{a}^{b}f(x)dx \right ) \ge \frac{1}{b-a}\int_{a}^{b} lnf(x)dx
$$

---
Chebyshev不等式

$h(x)在[a,b]上可积,且h(x)>0,f(x)和g(x)在[a,b]单调性相同$

$$
\int_{a}^{b} h(x)f(x)dx \int_{a}^{b} h(x)g(x)dx \le \int_{a}^{b} h(x)dx \int_{a}^{b} h(x)f(x)g(x)dx
$$

$注:取h(x)=1,有特殊情形$

$$
\int_{a}^{b} f(x)dx \int_{a}^{b} g(x)dx \le (b-a) \int_{a}^{b} f(x)g(x)dx
$$

$此外,易见f(x), g(x)单调性相反时, 不等号反向$

$再令g(x)=x,有$

$$
\frac{a+b}{2} \int_{a}^{b} f(x)dx \le \int_{a}^{b} xf(x)dx
$$

---
Hadamard不等式

$f(x)是[a,b]上的连续凹函数$

$$
f\left ( \frac{a+b}{2} \right ) \le \frac{1}{b-a} \int_{a}^{b} f(x)dx \le \frac{f(a)+f(b)}{2}
$$

---
Jensen不等式

$f(x)是[a,b]上的连续凹函数$

$$
f(\frac{1}{n} \sum_{i=0}^{n}x_i) \le \frac{1}{n} \sum_{i=0}^{n}f(x_i)
$$

$当2项时,有$

$$
f(\frac{a+b}{2} ) \le \frac{f(a)+f(b)}{2}
$$

$f(x)为凸函数不等号反向$

---
Carlson不等式

$$
\frac{1}{(b-a)(d-c)}\int_{a}^{b}f(x,y)dxdy \ge \exp \left ( \frac{1}{(b-a)(d-c)}\int_{a}^{b}lnf(x,y)dxdy \right )
$$

---
Young不等式

$若 a,b\ge0,p,q>0且\frac{1}{p}+\frac{1}{q}=1$,有$ab\le \frac{a^p}{p}+\frac{b^q}{q}$
