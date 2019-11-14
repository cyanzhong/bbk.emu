# BBK.EMU

集合了步步高电子词典上的几个经典老游戏：

- 伏魔记
- 三国霸业
- 金庸群侠传
- 魔塔
- 侠客行

本模拟程序基于 https://bgwp.gitee.io/baye/ 网页版，可以在 [JSBox](https://apps.apple.com/cn/app/id1312014438) 上离线运行。

# 声明

本程序模拟的游戏最早发布于步步高 4980 型号的电子词典，大约是在 2003 年，是我上初中的时候上课时候开小差玩的，也可以说启蒙了我对“程序”的概念。

在这十余年里，不断地有爱好者对伏魔记进行移植，到各种各样的平台。JSBox 版本基于 [iBaye](https://gitee.com/bgwp/iBaye) 项目，其使用 Emscripten 编译步步高的 C 语言原版。

感谢通宵虫、南方小鬼，以及不断复刻这个游戏的有趣的人们。

# 按键说明

除了上下左右以外：

- `Y` 和 `X` 对应电子词典上的上下翻页
- `B` 对应返回键，`A` 对应确认键
- `F1` 对应查找键，`F2` 对应帮助键

# 已知问题

目前发现`伏魔记`、`金庸群侠传`和`侠客行`的存档会串，如果从 A 游戏读取 B 的存档，会读入错误的游戏数据。
