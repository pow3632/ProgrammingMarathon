#天仙配

##题目描述
　　今年的七夕异常的热闹，很多对新人都把结婚日子选在了那天。 于是，他们决定一起举办“天上地下姻缘一线牵”活动，在广场上举行集体婚礼。<br>
　　为了活跃气氛，司仪想出了一个很有意思的游戏：会场有n(1≤n≤10000)对新人，司仪在地上画出一排(共2n个)格子， 每个格子里都写着一个随机的整数Ai(1≤Ai≤10000)。<br>
　　游戏开始后，让新人们任意地站成一排。等他们都站好以后，司仪开始计算他们每个人自己的得分， 记分规则是：男方的分数等于把从自己所站的位置开始一直累加到开头，女方的分数等于从自己所站 位置开始一直累加到末尾。如果某一对新人的得分数是相同的，那你们就获胜。可以得到一份司仪精心准备的礼物。^_^<br>
　　比如，有3对新人，地上的那一排数字为:3，6，2，4，5，2。<br>
　　如果男方站在第三个位置(2)，他的得分为：3+6+2=11；女方站在第4个位置(4)，她的得分为4+5+2=11。两人得分相同，可以获胜。<br>
　　或者男方站第6个位置(2)，女方站第1个位置(3)，他们的得分都等于22，也可以获胜。<br>
　　这么高兴的日子不能太扫兴，所以我们发现，无论地上的数字填成什么样子，女方站在开头和男方站在末尾就一定可以获奖。 我们不得不感叹司仪的用心良苦。呵呵。<br>
　　碰巧，nowcoder的姐姐和姐夫也在那天结婚，为了帮姐姐夺得奖品，nowcoder来请你帮忙，计算一下他姐姐获得奖品有多少种站法。

##输入描述:
　　输入包括多组测试数据。<br>
　　每组测试数据包括两行。<br>
　　第一行为一个数据n，即新人的对数。<br>
　　第二行有2n个数据，代表地上的数字。<br>
　　输入以0结束，这一行不做处理。


##输出描述:
　　每组输出占一行。<br>
　　输出共有几种站法。

##输入例子:
```
3
3 6 2 4 5 2
0
```

##输出例子:
```
2
```