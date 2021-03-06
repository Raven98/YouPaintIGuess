# 你画我猜
YPIG(你画我猜)，Linux操作系统课的大作业，游戏编程，目的是为了熟悉Linux底层进程通信知识。
[English]()

# 游戏介绍
一款基于HTTP协议的canvas「你画我猜」实时web游戏。

# 技术栈
## 前端
- canvas
- Vue.js
- JQuery
- Bootstrap

## 后端
- C

# 截图
## Draw Player
![](https://github.com/Raven98/YouPaintIGuess/blob/master/other/images/image-20181027222028063.png)
## Guess Player
![](https://github.com/Raven98/YouPaintIGuess/blob/master/other/images/image-20181027222054455.png)

# 不足
- HTTP 1.0 不适合这个游戏，只能利用 js 的 setInterval 函数去轮询请求刷新。websocket协议更合适。
- 游戏逻辑不够完整，我将尽快更新。

# 链接
- 在线试玩: http://weneu.xyz:8087/index.html (服务器不一定会一直开启)
- 我使用了 [@imcuttle](https://github.com/imcuttle/paint_game) 的html 代码。他使用node.js作为后端，我则使用了纯C。

# 想法
短短六周的Linux操作系统课程很快就结束了。六周的时间我真的学到太多知识。在上这门课之前，我其实有用过CentOS服务器运行一款我的产品（weNEU微信小程序），所以我本以为我对Linux操作系统有一些了解。但是在这门课上我才发现，我对Unix/Linux的了解只是皮毛，只是简单了解了一些应用层的知识，而关于底层知识则大抵不知道。

这门课再次点醒了我，平常的学习其实更应该深入到底层知识，如果总是停留在应用层，永远也学不到真正的知识，永远不能和前辈们有思维上的碰撞。框架每天都在变，只有学好了底层知识才能应对自如，成为真正的大牛。

课程虽然结束了，但是我想我会继续保持对操作系统学习的热爱，保持对计算机理论学习的热爱。