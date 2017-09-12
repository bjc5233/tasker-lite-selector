# tasker-lite-selector



## 说明
左下角快捷弹出菜单
* 安装tasker
* 导入tasker项目
* [lite-selector-init]下配置根路径[LITE_SELECTOR_ROOT_PATH]变量为自己的路径，并在路径中放入[jquery-3.2.1.min.js]
* [lite-selector-init]下配置弹出圆环大小[lite_circle_radius]，默认值为[120]
* [lite-selector-init]下配置是否展示关闭按钮[lite_show_close_button]，默认值为[true]
* [lite-selector-init]下配置菜单选项[lite_confs]。name键为菜单展示名，task键为需要执行的tasker任务名，fontSize键为字体大小[用于微调某个菜单，可选]
* 弹出菜单底色跟随壁纸，需要[tasker-common](https://github.com/bjc5233/tasker-common)中的[tasker-comm-wallpaper-color]模块支持
* 在桌面创建该任务的快捷方式
* 点击快捷方式弹出界面，再次点击快捷方式退出；也可以使用xposed edge模块配置[长按menu键执行lite-selector任务]
* 点击菜单执行对应的tasker任务

## 预览
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-12-18-07-48-348.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-12-00-17-12-453.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-12-00-57-49-640.png"/></div>
<br>
<div align=center><img height="480" width="270" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/ScreenRecord_2017-09-12-01-44-50.gif"/></div>
