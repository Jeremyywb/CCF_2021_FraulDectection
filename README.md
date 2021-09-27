# CCF_2021_FraulDectection

> CCF 2021个贷违约率，881代码。因为昨天时间仓促，写文章时似乎漏掉了一些特征，许多朋友都无法浮现882的成绩；我自己在复现的时候也发现无法复现那个成绩了，这里奉上881的成绩，真实有效~
> 此外里面还包含了一些特征和数据处理过程，大家觉得有用的可以自己的方式进行尝试
> 最后在此建议，本地相对容易陷入过拟合，大家可以在数据和模型参数方面进行尝试，大致包含以下几个点
- 模型迭代轮数尽量不超过2-3百哪种
- 树的深度可以设置矮一些，比如4，5，6，7这种
- 叶子树那就是2的dept次方了
- 早停，我这边尝试发现设置50上下效果还算不错的
- 特征取值数的限制，树模型因为靠分裂找到最优切分点，想象一下，如果特征取值等于样本数，那么其他特征想要的分裂点在它这里都能找到，可能导致其他特征无用

最后欢迎大家关注我的公众号--- YB统计人人工智能 ，或者扫码关注
![qrcode_for_gh_cd60da6c7acf_258](https://user-images.githubusercontent.com/10879918/134909621-0b37ed52-a49f-4e95-afa2-57b12a29a1ff.jpg)
