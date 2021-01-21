# 七上期中数学附加卷

## 一、填空题

### 1. $(5a^3-3a^2b+7ab^2-2b^3)(3a^2+ab-3b^2)$的展开式中，$a^2b^3$项的系数\___

**分析：**

1. 这一题的关键在于要清楚$a^3b^2$是由哪两项相乘得来的；
2. 注意计算过程中两个乘数的$\pm$号；

**解：**

由题意可知，$a^3b^2$项是由$(+7ab^2)(+ab)+(-3a^2b)(-3b^2)+(-2b^3)(+3a^2)$得来

$\therefore a^3b^2$项的系数=$7+9-6=10$

### 2. 计算：$\begin{aligned}\frac{20202020^2+1}{20202019^2+20202021^2}=\end{aligned}$\________

**分析：**

1. 直接计算看上去是不可能了
2. 但是观察那几个大数字，它们和接近，这样就以考虑用换元法来简化分式

**解：**

令$20202020=a, 则20202019=a-1, 20202021=a+1$

$\begin{aligned}原式&=\frac{a^2+1}{(a-1)^2+(a+1)^2}\\&=\frac{a^2+1}{a^2-2a+1+a^2+2a+1}\\&=\frac{a^2+1}{2a^2+2}\\&=\frac{1}{2}\end{aligned}$

### 3. 一列数$\begin{aligned}-1\frac{1}{2}, -2\frac{1}{6}, -3\frac{1}{12}, -4\frac{1}{20}, ...\end{aligned}$其中第$n$个数是\_**\_\_**，前100个数的和等于\_______

**分析：**

1. 观察每个数的特点，正数部分和分数部分分别各有规律

**解：**


$\begin{aligned}&~由题意的:第n个数的整数部分=-n, 分数部分=-\frac{1}{n(n+1)}\\&~\therefore~第n个数=-n-\frac{1}{n(n+1)}\\&~\therefore~前100个数之和为：\end{aligned}$

$$
\begin{aligned}
\sum_{n=1}^{100}{[-n-\frac{1}{n(n+1)}]}&=-(1+\cdots+100)-(\frac{1}{2}+\frac{1}{6}+\cdots+\frac{1}{100\times101}) \\
&=-5050-(1-\frac{1}{101}) \\
&=-5050\frac{100}{101}  
\end{aligned}
$$

### 5. 已知$x-1$是多项式$x^3-3x+k$的一个因式，这个多项式分解因式为\_______

**分析：**

1. $x-1$是多项式$x^3-3x+k$的一个因式，说明$x-1$可以整除多项式$x^3-3x+k$

**解：**

由题意得，$\begin{aligned}\frac{x^3-3x+k}{x-1}=x^2+x\cdots\cdots-2x+k\end{aligned}$

$\because~能整除$

$\therefore~k=2$

$\begin{aligned}\therefore~原式&=x^3-3x+2 \\&=x^3-x-2x+2 \\&=x(x-1)(x+1)-2(x-1) \\&=(x-1)(x^2+x-2) \\&=(x-1)^2(x+2)  \end{aligned}$

### 6. 已知$a$为正数，且$a[a(a+b)+b]+b=1$，则$a+b$的值是\_**\_**

**分析：**

1. 此题为根据已知条件（通常为一个等式）求值类型，其基本解法是：
   * 根据已知等式求出未知数
     * 分为等于0或者等于一个整数两种情况  
       * 等于0时
         * 对多项式进行因式分解
         * 各个因式等于零，再排除不可能的情况
         * 求出未知数
       * 等于一个整数时
         * 对多项式进行因式分解
         * 对整数进行质因数分解
         * 找到合适的解，注意$\pm$的问题
   * 带入所求多项式或者分式

**解：**

由题意得：

$$
\begin{aligned}
a[a(a+b)+b]+b&=1 \\
a(a^2+ab+b)+b&=1 \\
a^3+a^2b+ab+b-1&=0 \\
a^3-1+a^2b+ab+b&=0 \\
(a-1)(a^2+a+1)+b(a^2+a+1)&=0 \\
(a+b-1)(a^2+a+1)&=0
\end{aligned}
$$

$\because~a\gt0$

$\therefore~a^2+a+1\gt0$

$\therefore~a+b-1=0$

$\therefore~a+b=1$

### 7. 若方程$\begin{aligned}\frac{1}{4-x^2}+2=\frac{k}{x-2}\end{aligned}$有增根，则$k=$\_____

**分析：**

1. 这一类型的题首先要求解，会有两种情况
   * 可以用$k$的代数式表示$x$, 即$x=f(k)$
     * 若$x=x\_1$时，会产生增根，则$f(k)=x_1$，即可求出$k$
   * 无法用$k$的代数式表示$x$，只得到含有$x, k$的方程
     * 若$x=x_1$时，会产生增根，带入方程中，求出$k$
2. 注意关键在于要找到所有增根，并求出其对应的$k$

**解：**

由题意得：

$$
\begin{aligned}
\frac{1}{4-x^2}+2&=\frac{k}{x-2} \\
\frac{1}{(2-x)(2+x)}+2+\frac{k}{2-x}&=0 \\
1+2(2-x)(2+x)+k(2+x)&=0 \\
9-2x^2+2k+xk&=0  
\end{aligned}
$$

$\because~当x=\pm2时，方程有增根$

$\therefore~当x=2时：$
$$9-2\times2^2+2k+2k=0$$ $$k=-\frac{1}{4}$$ 
$\therefore~当x=2时：$ 
$$9-2\times(-2)^2+2k-2k=0$$ $$5=0$$ $$无解$$

### 8. 若关于$x$的方程$\begin{aligned}\frac{2x+a}{x-1}=1\end{aligned}$的解是正数，则$a$的取值范围是\_**\_**

**分析：**

1. 这一类型的题首先要求解方程
2. 根据题意列出不等式求范围
3. 注意增根的情况

**解：**

由题意得：

$$
\begin{aligned}
\frac{2x+a}{x-1}&=1 \\
2x+a&=x-1 \\
x&-a-1 
\end{aligned}
$$

$\because~x\gt0$

$\therefore~-a-1\gt0, 即a\lt-1$

$又\therefore~当x=1是原方程的增根$

$\therefore~-a-1\ne=1, 即a\ne-2$

$\therefore~a\lt-1, 且a\ne-2$

### 9. 已知$\begin{aligned}2\big(x^2+\frac{1}{x^2}\big)-3\big(x+\frac{1}{x}\big)=1，则x+\frac{1}{x}\end{aligned}$的值是\_____

**分析：**

1. 此题是典型的$\begin{aligned}x+\frac{1}{x}\end{aligned}$，关键在于利用$\begin{aligned}(x\pm\frac{1}{x})^2=x^2+\frac{1}{x^2}\pm2\end{aligned}$这一关系，对原式进行恒等变形
2. 这一题中，就是利用$\begin{aligned}(x\pm\frac{1}{x})^2=x^2+\frac{1}{x^2}\pm2\end{aligned}$将原式中的$x^2+\frac{1}{x^2}$转化成$\begin{aligned}(x+\frac{1}{x})^2-2\end{aligned}$

**解：**

由题意得：

$$
\begin{aligned}
2\big(x^2+\frac{1}{x^2}\big)-3\big(x+\frac{1}{x}\big)=1 \\
2[\big(x+\frac{1}{x}\big)^2-2]-3\big(x+\frac{1}{x}\big)=1 \\
2\big(x+\frac{1}{x}\big)^2-3\big(x+\frac{1}{x}\big)-5=0 \\
[2\big(x+\frac{1}{x}\big)-5][\big(x+\frac{1}{x}\big)+1]=0 
\end{aligned}
$$

$\begin{aligned}\therefore~\big(x+\frac{1}{x}\big)=\frac{5}{2}或-1\end{aligned}$

### 10. 方程$\begin{aligned}\frac{1}{x(x-1)}+\frac{1}{x(x+1)}+\cdots+\frac{1}{(x+9)(x+10)}=\frac{11}{12}\end{aligned}$的解是\_____

**分析：**

1. 此题是典型的裂项法类型

**解：**

$$
\begin{aligned}
\frac{1}{x-1}-\frac{1}{x}+\frac{1}{x}-\frac{1}{x+1}+\cdots+\frac{1}{x+9}-\frac{1}{x+10}&=\frac{11}{12} \\
\frac{1}{x-1}-\frac{1}{x+10}&=\frac{11}{12} \\
12(x+10-x+1)&=11(x-1)(x+10) \\
x^2+9x-22&=0 \\
(x+11)(x-2)&=0
\end{aligned}
$$

$\therefore~x=2或-11$

### 12. 4个不同的正整数$m, n, p, q满足(7-m)(7-n)(7-p)(7-q)=4$，则$m+n+p+q=$\______

**分析：**

1. 此题为多个整数相乘等于一个整数类型，其解法就是
   * 先对整数进行质因数分解，注意要根据题意判断是否负因数以满足题意
   * 在根据题意看那些因数的组合满足题意

**解：**

$\because m, n, p, q为四个不同的整数$

$\therefore 7-m, 7-n, 7-p, 7-q为四个不同的整数$

$又\because 4的因数有\pm1, \pm2, \pm4$

$\therefore 7-m, 7-n, 7-p, 7-q只可能是\pm1，\pm2$

$\therefore 解得m, n, p, q分别为8，6，9，5$

$\therefore m+n+p+q=28$

### 13. 因式分解：$a^2(b-c)+b^2(c-a)+c^2(a-b)=$\_______

**分析：**

1. 类似这种题可以用主元法结合十字相乘法

**解：**

$$
\begin{aligned}
原式&=a^2b-a^2c+b^2c-b^2a+c^2a-c^2b \\
&=(b-c)a^2+(c^2-b^2)a+b^2c-c^2b \\
&=[(b-c)a+b^2-cb](a-c) \\
&=[(b-c)a+b(b-c)](a-c) \\
&=(b-c)(a+b)(a-c)
\end{aligned}
$$

### 14. 已知$a, b, c$均为不等于1的正数，且$a^{-2}=b^3=c^6$，则$abc=$\_**\_**

**分析：**

1. 用一直条件推出$a, b, c$之间的关系

**解：**

$\because a^{-2}=c^6$

$\therefore a^2c^6=1$

$又\because~a\gt0, c\gt0$

$\therefore~ac^3=1, 即a=c^{-3}$

$\because~b^3=c^6, 且b\gt0, c\gt0$

$\therefore~b=c^2$

$\therefore~abc=c^{-3}c^2c=1$

## 二、解答题

### 15. 已知$m, x, y$满足$①\frac{2}{3}(x-5)^2+5|m|=-m^2, ②整式3a^2b^3-2a^2b^{y+1}不是多项式$，计算：$\begin{aligned}0.375x^2y+5m^2x-\left\{-\frac{7}{16}x^2y+\left[-\frac{1}{4}xy^2+\big(-\frac{3}{16}x^2y-3.475xy^2\big)\right]-6.275xy^2\right\}\end{aligned}$

**分析：**

**解：**

由①解得，$x=5, m=0$

由②可得，$3=y+1，即y=2$

带入原式可得：

$$
\begin{aligned}
原式&=0.375x^2y+5m^2x-\left\{-\frac{7}{16}x^2y+[-\frac{1}{4}xy^2+\big(-\frac{3}{16}x^2y-3.475xy^2\big)]-6.275xy^2\right\} \\
&=0.75x^2-\left\{-\frac{7}{8}x^2+[-x+\big(-\frac{3}{8}x^2-13.9x\big)]-25.1x\right\} \\
&=0.75x^2+\left(\frac{7}{8}x^2+x+\frac{3}{8}x^2+13.9x+25.1x\right) \\
&=2x^2+40x \\
&=50+200 \\
&=250 
\end{aligned}
$$

### 16. 因式分解：$(x+5)^4+(x+3)^4-82$

**分析：**

1. 拆项法

**解：**

$$
\begin{aligned}
原式&=(x+5)^4+(x+3)^4-82 \\
&=(x+5)^4-1+(x+3)^4-3^4 \\
&=[(x+5)^2+1][(x+5)^2-1]+[(x+3)^2+9][(x+3)^2-9] \\
&=(x^2+10x+26)(x+6)(x+4)+(x^2+6x+18)(x+6)x \\
&=(x+6)(x^3+10x^2+26x+4x^2+40x+104+x^3+6x^2+18x) \\
&=(x+6)(2x^3+20x^2+84x+104) \\
&=2(x+6)(x^3+10x^2+42x+52) \\
&=2(x+6)(x^3+8+10x^2+42x+44) \\
&=2(x+6)[(x+2)(x^2+2x+4)+(5x+11)(2x+4)] \\
&=2(x+2)(x+6)(x^2+2x+4+10x+22) \\
&=2(x+2)(x+6)(x^2+12x+26)
\end{aligned}
$$

### 17. 已知$a, b, c$满足$abc=-1, a+b+c=4$, $\begin{aligned}\frac{a}{a^2-3a-1}+\frac{b}{b^2-3b-1}+\frac{c}{c^2-3c-1}=\frac{4}{9}\end{aligned}$，求$a^2+b^2+c^2$的值

**分析**

1. 利用已知条件求出所需的部分

**解：**

由题意得：

$$
\begin{aligned}
\frac{a}{a^2-3a-1}+\frac{b}{b^2-3b-1}+\frac{c}{c^2-3c-1}&=\frac{4}{9} \\
\frac{a}{a^2-3a+abc}+\frac{b}{b^2-3b-+bc}+\frac{c}{c^2-3c+abc}&=\frac{4}{9} \\
\frac{1}{a-3+bc}+\frac{1}{b-3+ac}+\frac{1}{c-3+ab}&=\frac{4}{9} \\
\frac{1}{1-b-c+bc}+\frac{1}{1-a-c-ac}+\frac{1}{1-a-b+ab}&=\frac{4}{9} \\
\frac{1}{(1-b)(1-c)}+\frac{1}{(1-a)(1-c)}+\frac{1}{(1-a)(1-b)}&=\frac{4}{9} \\
\frac{3-a-b-c}{(1-a)(1-b)(1-c)}&=\frac{4}{9} \\
\frac{-1}{(1-a)(1-b)(1-c)}&=\frac{4}{9} \\
(1-a)(1-b)(1-c)&=-\frac{9}{4} \\
1-a-b-c+ab+bc+ac-abc&=-\frac{9}{4} \\
1-4+ab+bc+ac+1&=-\frac{9}{4} \\
ab+bc+ac&=-\frac{9}{4}+2 \\
ab+bc+ac&=-\frac{1}{2}
\end{aligned}
$$

$又有，a+b+c=4，可得，$

$$
\begin{aligned}
(a+b+c)^2&=16 \\
a^2+b^2+c^2+2(ab+bc+ac)&=16 \\
a^2+b^2+c^2-1&=16 \\
a^2+b^2+c^2&=17
\end{aligned}
$$

