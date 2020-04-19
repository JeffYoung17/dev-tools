# dev-tools

开发环境使用的工具

[TOC]

## tmux

### 基本概念

服务server：开启tmux服务 --》打开QQ软件
会话session：多个会话相当于登录多个QQ账号
窗格pane：每个pane表示一个伪终端
窗口window：多个pane组成的当前屏幕；

### 常用快捷键
！！！重新配置tmux快捷键后，需要重启session使其生效。
配置文件的路径：~/.tmux.conf

```shell
# window
prefix + c : 新建窗口
prefix + & : 关闭窗口
prefix + l : 切换到上一个窗口
prefix + w : 选择窗口的列表

# pane
prefix + % : 水平划分
prefix + " : 垂直划分
prefix + x : 关闭窗格
prefix + 方向键或者o : 切换窗格
```
### 参考资料

[bilibili十分钟掌握 tmux](https://www.bilibili.com/video/BV1ab411J7xT?from=search&seid=6153849982347372287)