﻿# 函数加餐课部分笔记

标签（空格分隔）： js

---

难点：37min到45min
笑点：43min31s我他（ma??竟然忍住了口头禅哈哈哈)

感觉这部分弄懂了，不知道是不是正确的理解，或者对其他小白是不是有用，反正就是非常爽，所以我要写下来。而且，我觉得我看了狠多遍！就算是不完全正确的理解，对我自己也会有价值~


38min提示，其实有两个返回结果，后面是围绕这个在讲。加return、接受结果、打印是为了说明这是立即返回函数，加不加return都是有返回的；
老板调用callback，callback结束老板已经得到答案； 是不是return，他都有结果。编程思维什么鬼，我就没有啊。不要callback那段演示是为了说明要不要回调，我都是同步函数（都有结果，无论是不是返回），实际情况是不是可以理解为，老板调用的函数肯定是他觉得基本能得到答案的，这里就是他知道给秘书打电话，秘书肯定会给他一个回答；他传一个参数，是他觉得这个参数调用的通道（这里的微信）或许能给他信息，但他也不确定（所以只是当作参数传进去，算是给被调用的函数（通过电给秘书获得答案）一个建议，但这个建议是不是被采用，看秘书怎么处理），起码没有电话确定，他要是确定直接就调用微信（callback）能得到答案就不调用电话（checkflightschedule函数）了，所以老板调用的函数本身肯定能直接返回给他值，不论有没有提示具体要return什么东西出来，直接调用的函数都是有结果的，如果没写出来，那打印的时候会出现undefined，表示不知道这是什么值，但这个值是存在的。老师说这是编程思维，我不知道我有没有，不过我知道，这里说的就是这个知识点。44min38s直接说了重点，不返回也会有undefined,这就是结果。
没有参数的函数，调用时传了参数没问题，因为反正你传了也没用~

明白了之后好像后面都是在讲同一件事了。没想明白的时候，说别这么想，我的OS：我要怎么想？？？46min那边说图有意思，我咋不知道，47min22s看图和代码是一样的，我咋不造，不过现在看完大概知道了。画的图和文字的表达方式可能有一点差异，不好看我也先放上哈哈~非常感谢老师给回放。
一遍遍看，一步步弄懂老师说的话是为了说明什么，渐渐聚焦问题。目标小点，达到的概率大点，今晚的目标是把做的作业推送上，还好没有因为完成不了觉得自己做的事没意义。（推送有问题差点放弃）

虽然我没有像李朋同学一样，第一遍就直接大脑运行出代码结果，但只要我想要，弄懂就是迟早的事。（哈哈哈还是把这碗深夜鸡汤端上来了，主要炖给自己)



















