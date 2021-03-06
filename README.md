# tasker-lite-selector



## 说明
左下角快捷弹出菜单
* 安装tasker
* 导入tasker项目
* [lite-selector-init]下配置根路径[LITE_SELECTOR_ROOT_PATH]变量为自己的路径，并在路径中放入[jquery-3.2.1.min.js]和[pay]文件夹
* [lite-selector-init]下配置弹出圆环样式[lite_circle_style]，可选值为[1半圆\2全圆]，默认值为[2]
* [lite-selector-init]下配置是否展示关闭按钮[lite_show_close_button]，默认值为[true]
* [lite-selector-init]下配置菜单选项[lite_confs]，格式参考[resources->lite_confs_demo.txt]
* 弹出菜单底色跟随壁纸，需要[tasker-common](https://github.com/bjc5233/tasker-common)中的[tasker-comm-wallpaper-color]模块支持
* 默认第二圆环设置为支付宝微信的支付方式，需要[tasker-pay](https://github.com/bjc5233/tasker-pay)模块支持
* 在桌面创建该任务的快捷方式
* 点击快捷方式弹出界面，再次点击快捷方式退出；也可以使用xposed edge模块配置[长按menu键执行lite-selector任务]
* 点击菜单打开APP\执行tasker任务



### 更新
* 2017-09-16版本中可配置圆环样式是半圆\全圆
* 2017-09-13版本中可配置打开APP\tasker任务
* 2017-09-13版本中增加多圆环支持，默认添加支付宝微信支付方式
* 2017-09-12版本中增加关闭按钮



## 预览
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-16-17-45-09-117.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-13-20-42-40-338.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-12-18-07-48-348.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-12-00-17-12-453.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/Screenshot_2017-09-12-00-57-49-640.png"/></div>
<br>
<div align=center><img height="480" width="270" src="https://github.com/bjc5233/tasker-lite-selector/raw/master/resources/ScreenRecord_2017-09-12-01-44-50.gif"/></div>
