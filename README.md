# FuckDaXueXiScreenshot

青年大学习截图生成器

## 使用方法

1. 部署这个项目。

2. 打开微信，访问网页 `项目部署地址/index.html?term=大学习期数&season=大学习季数`

例如，对于第八季第七期，`https://kenvix.github.io/FuckDaXueXiScreenshot/index.html?term=7&season=8`

默认展示学习完成页面，如果还需要其他类型的截图，可以指定 type 参数，例如，最后一题的截图：

`https://kenvix.github.io/FuckDaXueXiScreenshot/index.html?term=7&season=8&type=1`

## 如何贡献本项目

大学习截图是需要人力添加的。

所有截图都放在 img 文件夹。img 文件夹内的数字表示大学习季数。

打开季数文件夹，可以看到很多 jpg 文件，这就是大学习截图。格式为 `期数-类型编号.jpg`

约定：类型编号 0 表示大学习学习完成的截图，1 为大学习习题最后一题的截图。
