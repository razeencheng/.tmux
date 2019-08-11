# .tmux
Oh My Tmux!  我的tmux配置，以及相关设置。

![Jietu20190811-232428.gif](http://st.razeen.cn/image/blog/Jietu20190811-232428.gif)



### 我的环境

- 系统：Mac OS X 10.14
- 终端：Mac 终端
- Tmux:  3.0



### 安装

直接运行以下命令既可安装。（如果你已经有配置了，可以先备份一下。）

```bash
cd ~
git clone https://github.com/razeencheng/.tmux.git
ln -s -f .tmux/.tmux.conf
```



### 可能会遇到的问题

- 无法复制

  需要安装`reattach-to-user-namespace`命令。

  ```bash
  brew install reattach-to-user-namespace
  ```

  选中需要复制内容，按‘y‘即可复制。

- 无法使用鼠标滚动Tmux内容（直接滚动的是终端）

  修改终端设置即可。

  打开终端>偏好设置>高级

  取消“输入时滚动到底部”勾选。

  ![](http://st.razeen.cn/image/blog/Jietu20190723-231812.jpg)



### 特征

1. 前置按钮由`C-b`改为`C-a`，使用更顺手（特别是你将Caps Lock按键修改成Ctrl情况下，附上Mac修改键盘位方法）

   系统偏好设置>键盘>修改按键，截图如下

   ![Jietu20190812-001613.jpg](http://st.razeen.cn/image/blog/Jietu20190812-001613.jpg)

2. `C-a s/v`  水平，垂直分屏。
3. `C-a R` 重载tmux 配置。
4. 启用vi模式。
5. `C-a h/j/k/l` 左/下/上/右 切换窗格。
6. 可使用鼠标切换窗格/Tab。
7. 选中文章，按`y`即可复制。



tmux也用了2年多了，这些基本的使用已经能满足日常需求了，后续有改进的，持续更新。