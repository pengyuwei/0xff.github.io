# 代码冲动技术博客

2020-0705

碰到特别奇怪的问题， 使用仓库名可以正常访问更新的博客：https://github.com/pengyuwei/0xff.github.io

但是使用github.io三级域名就不能访问：0xff.github.io，得到另外一个空白博客，内容不知道哪里来的。

后来经过来回实验，发现，setting里设置的仓库名虽然为：0xff.github.io，并且提示名字可用。但实际这里的是指的自己的名字空间下名字可用，而不是0xff这个三级域名可用。

github.io这个域名下面的三级域名，实际完全是另外一个东西，你可以随便写一个域名，比如microsoft.github.io，但是md更新后，是不会更新到你设置的域名上去的。

目前尚不知道如何查询哪个三级域名可用，靠谱的方法是直接设置和自己的名字空间一样的名字（汗）
