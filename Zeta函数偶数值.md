
## 法一[^1]


由 $\textbf{Weierstrass 定理}$[^2] 知 
$$\sin z = z\prod_{n=1}^\infty \left(1 - \dfrac{z^2}{n^2 \pi^2}\right)$$

取对数，得 
$$\ln\sin z = \ln z + \sum_{n\ge 1} \ln\left(1 - \dfrac{z^2}{n^2 \pi^2}\right)$$

两边同时求导，有 
$$\cot z = \dfrac{\cos z}{\sin z} = \dfrac{1}{z} + \sum_{n\ge 1} \dfrac{2z}{z^2 - n^2\pi^2}$$

两边同乘 $z$，有

$$\begin{align*}
    z \cot z &= 1 - 2\sum_{n\ge 1} \dfrac{z^2}{n^2\pi^2 - z^2} \\
    &= 1 - 2\sum_{n\ge 1}  \dfrac{z^2}{n^2\pi^2} \dfrac{1}{1 - \dfrac{z^2}{n^2\pi^2}} \\
    &= 1 - 2\sum_{n\ge 1} \sum_{k \ge 1} \dfrac{1}{n^{2k}} \left(\dfrac{z}{\pi}\right)^{2k} \\
    &= 1 - 2\sum_{k \ge 1} \sum_{n\ge 1} \dfrac{1}{n^{2k}} \left(\dfrac{z}{\pi}\right)^{2k} \\
\end{align*}$$

于是令 $\dfrac{z}{\pi} = x$，
$$\pi x \cot \pi x = 1 - 2\sum_{k \ge 1} \zeta(2k)x^{2k}$$

我们知道，
$$x \cot x = \sum_{n \ge 0} (-1)^n \dfrac{B_{2n}}{(2n)!} (2x)^{2n}$$

对比系数，我们就有，
$$\zeta(2n) = (-1)^{n-1} \dfrac{1}{2} \dfrac{B_{2n}}{(2n)!} (2\pi)^{2n} $$

## 参考

[^1]: [Weierstrass定理——解决一类常见的无穷乘积](https://zhuanlan.zhihu.com/p/124237201)

[^2]: [Weierstrass定理——解决一类常见的无穷乘积](https://zhuanlan.zhihu.com/p/124237201)
