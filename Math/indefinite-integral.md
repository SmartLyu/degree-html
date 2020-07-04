# 不定积分

## 考点

1. 记忆常用积分！！
2. 分式形积分，上下同除
3. 对$$\int f(\sin{x},\cos{x})dx$$类型题目求极限
   1. $$f(-\sin{x},\cos{x})=-f(\sin{x},\cos{x})$$，凑$$d(\cos{x})$$
   2. $$f(\sin{x},-\cos{x})=-f(\sin{x},\cos{x})$$，凑$$d(\sin{x})$$
   3. $$f(-\sin{x},-\cos{x})=f(\sin{x},\cos{x})$$，凑$$d(\tan{x})$$
4. ...

## 不定积分的概念及存在性

1. 原函数

   若存在$$F(x)$$，对$$\forall x \in I$$，有$$F'(x)=f(x)$$成立，则称$$F(x)$$是$$f(x)$$在区间$$I$$上 的一个原函数.

2. 不定积分

   $$f(x)$$在区间$$I$$上的所有原函数称为$$f(x)$$在区间上的不$$I$$定积分，记为$$\int{f(x)}dx$$，这 里$$f(x)$$ 称 为 被 积 函 数 ， 且$$\int{f(x)}dx = F(x) + C$$， 其 中 $$F(x)$$ 是$$f(x)$$在$$I$$上 的一个原函数。

3. 原函数(不定积分)的存在性

   1. 连续函数一定有原函数;
   2. 含有第一类间断点的函数在包含该间断点在内的区间上没有原函数。
   3. 很多函数有原函数，但它的原函数未必都是可求的。

## 计算不定积分

不定积分计算完成后，有+C这个结尾

### 基本积分公式

![image-20200702164750807](https://smartlyu.github.io/degree-html/images/image-20200702164750807.png)

$$\int{(\frac{1}{x(1+x)})} = \int{\frac{1}{x}}-\int{\frac{1}{x+1}} = \ln|\frac{x}{1+x}|$$

### 积分方法

1. **凑微分**

   ![image-20200702165200849](https://smartlyu.github.io/degree-html/images/image-20200702165200849.png)

   例题：

   1. 上下同除$$x^2$$，凑出微分
      $$
      \int(\frac{x^2+1}{x^4+1})dx 
      =\int(\frac{1+\frac{1}{x^2}}{x^2+\frac{1}{x^2}})dx
      =\int(\frac{1}{x^2+\frac{1}{x^2}})d(x-\frac{1}{x}) \\
      =\int(\frac{1}{(x-\frac{1}{x})^2+2})d(x-\frac{1}{x})
      =\frac{\sqrt{2}}{2}\arctan{\frac{x-\frac{1}{x}}{\sqrt{2}}}+C \\
      
      \int(\frac{1}{x^4+1})dx=\frac{\int(\frac{x^2+1}{x^4+1})dx - \int(\frac{x^2-1}{x^4+1})dx }{2} = ....
      $$
      

   2. 对$$\int f(\sin{x},\cos{x})dx$$类型题目求极限

      1. $$f(-\sin{x},\cos{x})=-f(\sin{x},\cos{x})$$，凑$$d(\cos{x})$$
      2. $$f(\sin{x},-\cos{x})=-f(\sin{x},\cos{x})$$，凑$$d(\sin{x})$$
      3. $$f(-\sin{x},-\cos{x})=f(\sin{x},\cos{x})$$，凑$$d(\tan{x})$$

      * $$
        \int{\frac{1}{1+\sin^2x}}dx =\int {\frac{1}{2\sin^2x+\cos^2x}}dx \\
        =\int {\frac{1}{2\tan^2x+1}}d(\tan{x}) = ...
        $$

   3. ...

2. 换元法

   ![image-20200702175652250](https://smartlyu.github.io/degree-html/images/image-20200702175652250.png)

   

3. ...

