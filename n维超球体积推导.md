
首先，设 $n$ 维单位超球体积为 $V_n$，易知半径为 $r$ 的 $n$ 维超球体积为 $V_n r^n$.

类比三维球体，$n$ 维超球可以划分成无穷多片 $n-1$ 维超球(圆柱).

$$ \begin{align*}
    V_n &= 2\int _0^1 V_{n-1} (1-x^2)^{\frac{n-1}{2}} \mathrm dx \\
    % &= 2 V_{n-1} \int _0^{\frac{\pi}{2}} \cos^n \theta \mathrm d \theta\\
    &= V_{n-1} \int _0^1 t^{-\frac 1 2} (1-t)^{\frac{n-1}{2}} \mathrm dx \\
    &= B(\frac 1 2, \frac{n+1}{2}) V_{n-1} \\
    &= \frac{\Gamma(\frac 1 2)\Gamma(\frac{n+1}{2})}{\Gamma(\frac n 2 + 1)} V_{n-1} \\
    &= \sqrt \pi \frac{\Gamma(\frac{n+1}{2})}{\Gamma(\frac n 2 + 1)} V_{n-1} \\
    &= \frac{\pi^{\frac n 2}}{\Gamma(\frac n 2 + 1)}
\end{align*}
$$

## 参考资料

[高维空间(5)——n维球的体积公式及表面积公式](https://zhuanlan.zhihu.com/p/104715872?utm_psn=1853474901081604096)