
$\mathbf{定义1. 高德纳箭头(Knuth Arrows)}$
$$
 a \uparrow^c b =
    \left\{\begin{align*}
        &a^b ,&c = 1\\
        &1 ,&b = 0\\
        &a \uparrow^{c-1} (a \uparrow^c (b-1)) ,&else
    \end{align*}
    \right.

$$

例：$a \uparrow b = a^b$，$a \uparrow \uparrow b = a^{a^{\cdots^a}}$



## 参考

[ZhiqiuCao/Googology: This is the latest version of textbook《大数理论》(Googology).](https://github.com/ZhiqiuCao/Googology)