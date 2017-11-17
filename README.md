# 智慧树视频自动播放

智慧树视频不能在播放完后自动播放下一集，并且偶尔会弹出个对话框，看看你人在不在电脑旁，我想着利用所学的前端知识，写个插件，帮助自己刷课，所以就有了这个chrome插件。

功能：

- 只对智慧树视频网站有效(`http://online.zhihuishu.com/`)
- 播放视频时实现：1.5倍速度，标清，无声播放
- 自动播放视频的下一集
- 对偶尔弹出的`测试`对话款进行关闭处理

需要的工具：

- chrome55+ (我用了es7的语法: `async/await` , 只有chrome55+的js引擎才能解析)

## 一、使用方法

1、打开chrome浏览器，来到 [github.com/perhaps-yo/zhihuishu](github.com/perhaps-yo/zhihuishu) 界面，下载插件源码

![下载插件]()

解压后的源码放到自己喜欢的目录

2、chrome浏览器输入 `chrome://extensins` ，来到扩展程序页面。按步骤：勾选`开发者模式` -> 单击`加载已解压的扩展程序`，选择刚刚源码的位置 -> 勾选`已启用`。效果如下图：

![安装插件]()

脚本安装成功，准备刷课！

3、来到智慧树视频网站 [online.zhihuishu.com](http://online.zhihuishu.com)，登录后，到视频页面，就会自动开始刷课啦～

![自动刷课]()

会看到

## 二、遇见的问题

- Q: 来到智慧树视频网站后，没能实现 `1.5倍速度，标清，无声播放`？
  - A: 按 `f5` 刷新页面。

## 三、License

[MIT](https://github.com/aspnetboilerplate/aspnetboilerplate/blob/dev/LICENSE).
