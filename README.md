# Netshoot
2021腾讯游戏客户端公开课作业2，基于UE4多人射击游戏案例实现飞碟和结算UI功能。

连接局域网需要开启启用网络发现，如果有虚拟网卡需要禁用。

增加的功能有：

- 每隔一段时间或者被击中后生成的飞碟，网络同步，击中后有加分和变色效果；
- 1分钟倒计时，结束后弹出结算UI，根据玩家分数给出胜负结果；
- 击中角色后取消瞄准，避免玩家压起身，另一个玩家复活就被击杀。

未解决的问题：

- 客户端的飞碟运动有时会抖动，猜测和网络有关。
