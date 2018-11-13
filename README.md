用我们的算法和开源的zcash算法做一个对比

我们的算法是equihash.so.  为了防止代码泄露, 我没有把源代码拷贝到这个项目里, 可能需要自己重新编译.

新的算法是https://github.com/morpav/zceq_solver, 有一个编译好可以用的代码在https://github.com/morpav/zceq_solver--bin.

我们之前的代码bug描述请看这里: http://blogs.360.cn/post/%E9%BB%91%E5%AE%A2%E4%BC%AA%E9%80%A0%E7%AE%97%E5%8A%9B%E7%9B%97%E5%8F%96%E5%A4%9A%E7%A7%8D%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81.html


测试用例有两个:
1. 用一个正确的数据, 来检查新老的算法
2. 用有bug的数据, 来验证新老算法