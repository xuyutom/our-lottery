1.程序用途：比赛抽奖

2.框架：Beego

3.需求：

>根据金数据表单的提交数据建立一份名单(每行一个人名，可以手动建立),编写一个程序用于抽奖

>功能

>>基于WEB，便于演示；

>>有启停按钮，点击启动按钮则开始极速循环遍历名单（人名或序号），点击停止按钮则选出此刻的人名；

>>需要实时列有中奖名单；

>>选出10人（可配置）后启停按钮不可用，抽奖结束。

4.修改抽奖者名单
>修改conf/test.txt内容

5.运行步骤
>前提：确保正确安装beego环境

>下载代码，放置$GOPATH/src/下

>cd $GOPATH/src/out-lottery/

>bee run

6.其他未尽事项
>界面需要美工再优化