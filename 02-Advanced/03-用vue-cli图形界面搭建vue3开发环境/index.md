<!--
 * @Author: gaoyuan
 * @Date: 2020-10-27 16:24:00
 * @LastEditors: gaoyuan
 * @LastEditTime: 2020-10-27 16:41:18
-->
上一节是利用命令行或者终端vue-cli来构建vue3的项目，这节看了一下vue-cli如何使用图形界面构建项目的。
因为是图形界面，所以代码很少，多是界面，建议观看视频学习。

#### 启动vue-cli的图形界面
当你安装了最新版的vue-cli 就可以使用 vue ui 命令，开启一个ui界面，然后会出现下面的提示
```javascript
Starting GUI.
Ready on http://localhost:80
```
点击创建--在此处创建新项目--输入项目名称和包管理器，这里输入vue3-2，使用npm 作为管理器
--点击下一步，之后让你选择预设模板，选择手动，之后和命令行基本这一致，根绝自己项目来进行配置。
完成后选择创建项目---弹出提示, 是不是保存这个配置，这里依然是不保存--这时候如果你注意到vscode的终端，
会发现他已经开始为我们构建项目了，大概一分钟左右，会跳出”欢迎来到新项目“页面，说明构建已经成功了

这时候启动终端，进入项目 cd vue3-2，启动服务 npm run serve 等到系统服务台启动后打开终端中的地址，可以看到界面
说明运行成功