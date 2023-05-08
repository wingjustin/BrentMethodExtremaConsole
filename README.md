# BrentMethodExtremaConsole

<h3>Brent's Minimization Method</h3>

<p>
不需對連續函數求導的求根算法
<br><br>
主要有兩種算法, 黃金分割法 和 拋物線插值
<br><br>
黃金分割法保證收斂且收斂速度為線性, 拋物線插值不保證收斂但速度為超線性
<br>另外拋物線插值要求3個不同點
<br><br>
當前算法若果出現估值超出[a,b]區間或除零等壞情況,需要更換算法, 順序為 拋物線插值, 黃金分割法
<br><br>
每次迭代視情況更換算法加速並保證收斂
<br><br>
<div>references:</div>
<ul>
<li>1. R. P. Brent, Algorithms for Minimization without Derivatives, Prentice-Hall, Englewood Cliffs, New Jersey, 1973</li>
<li>2. https://www.youtube.com/watch?v=BQm7uTYC0sg</li>
<li>3. boost.org, https://www.boost.org/doc/libs/1_76_0/libs/math/doc/html/math_toolkit/brent_minima.html</li>
<li>4. boost.org, https://www.boost.org/doc/libs/1_76_0/boost/math/tools/minima.hpp</li>
</ul>
</p>

