# CCF_2021_FraulDectection

----20210928bug修正---------
很多人测试结果和我不一样，这里做了个修改，经群友测试可以，大家试试
[代码在此](https://github.com/Jeremyywb/CCF_2021_FraulDectection/blob/main/ThirdOliver-InternetTrue.ipynb)
代码还有提升空间，自行修改
----20210928-----
样本扩充方法，提升3点精度，最终884线上，
内容在此[YB统计人工智能]( https://mp.weixin.qq.com/s/eabznXXzlwJ2wlK_ZYN85A)
----20210927-----
CCF 2021个贷违约率，881代码。因为昨天时间仓促，写文章时似乎漏掉了一些特征，许多朋友都无法浮现882的成绩；我自己在复现的时候也发现无法复现那个成绩了，这里奉上881的成绩，真实有效

[代码在这里](https://github.com/Jeremyywb/CCF_2021_FraulDectection)

---- 20210926-----
线上88.2，增加一个特征，具体内容在此 [YB统计人工智能](https://mp.weixin.qq.com/s?__biz=MzIwODc1MDg2NQ==&mid=2247484903&idx=1&sn=7d8d4544b3ff20f604ae07912df9f8cc&chksm=977f1599a0089c8f75928d8fe98986bdcede58d7bb96802c94b2f796c42136136b2e52c5f73a&token=1274940859&lang=zh_CN#rd)



> CCF 2021个贷违约率，881代码。因为昨天时间仓促，写文章时似乎漏掉了一些特征，许多朋友都无法浮现882的成绩；我自己在复现的时候也发现无法复现那个成绩了，这里奉上881的成绩，真实有效~
> 此外里面还包含了一些特征和数据处理过程，大家觉得有用的可以自己的方式进行尝试
> 最后在此建议，本地相对容易陷入过拟合，大家可以在数据和模型参数方面进行尝试，大致包含以下几个点
- 模型迭代轮数尽量不超过2-3百哪种
- 树的深度可以设置矮一些，比如4，5，6，7这种
- 叶子树那就是2的dept次方了
- 早停，我这边尝试发现设置50上下效果还算不错的


最后欢迎大家关注我的公众号--- **YB统计人人工智能** ，或者扫码关注

![qrcode_for_gh_cd60da6c7acf_258](https://user-images.githubusercontent.com/10879918/134909621-0b37ed52-a49f-4e95-afa2-57b12a29a1ff.jpg)
