# DelayKiller
拖堂终结者！！！干掉拖堂！

### 机制
借助 Windows 自带的 [任务计划程序](https://learn.microsoft.com/zh-cn/windows/win32/taskschd/about-the-task-scheduler) 在下课时注销 Windows 登录

### 基础用法
> 此教程**面对学生阶段的电脑小白**，不严谨的地方*不喜勿喷*
1. [点击这里](https://github.com/Hakuin123/DelayKiller/releases/download/latest/DelayKiller.xml)下载`拖堂终结者.xml`文件，下载到桌面
2. 打开`任务计划程序`
   - 按下键盘上的`Windows 徽标键`/任务栏上的`开始`（Windows标志）打开开始菜单,在应用列表中找到'Windows 工具'，找到并打开`任务计划程序`
   - 打开`控制面板` - `所有控制面板项` - `Windows 工具`，找到并打开`任务计划程序`
   - 按下键盘上的Win+R，在弹出的`运行`里面输入`C:\WINDOWS\system32\taskschd.msc`，点击确定
3. 点击`导入任务…`![3](/screenshots/3.png)
4. 在桌面导入下载的xml文件
5. （可选）在弹出的窗口点击`触发器`修改下课时间，此时请确认电脑右下角系统时间是否正常
6. 点击确定

恭喜！你已经完成基本的设置了！

### 高阶玩法
- 参考文档：https://learn.microsoft.com/zh-cn/windows/win32/taskschd/about-the-task-scheduler
- 你还可以修改要执行的命令以达到更多效果
