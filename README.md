#解析几何<br> 
##主要功能：<br> 
###绘制函数图像<br> 
###绘制参数方程图像<br> 
###支持鼠标拖动和触控拖动、双指缩放<br> 
###丰富的设置项：<br> 
线条颜色、粗细<br> 
绘制方式：点或者线<br> 
是否自动计算网格大小<br> 
可调精度<br> 
可调参数<br> 
###支持图片输出<br> 
###附带两个小工具：<br> 
普通计算器<br> 
解方程：支持二分法解方程和详细的一元二次方程求解<br> 
<br> 
##更新日志：<br> 
2015-11-28<br> 
【解析几何图像】启动 “解析几何图像”计划<br> 
【解析几何图像】新增 解析几何图像-函数图象<br> 
2015-11-29<br> 
完成 项目图标<br> 
【解析几何图像】新增 解析几何图像-参数方程<br> 
【解析几何图像】新增 解析几何图像-特殊方程（圆、椭圆）<br> 
【解析几何图像】新增 解析几何图像-配置的保存和读取<br> 
【解析几何图像】新增 解析几何图像-按回车键绘制<br> 
【解析几何图像】修复 解析几何图像-内容为空时也可按确定<br> 
2015-12-6<br> 
【项目】启动 “数学工具”计划<br> 
【项目】启动 “启动器”计划<br> 
【项目】启动 “普通计算器”计划<br> 
【项目】重做 程序图标<br> 
【启动器】完成 启动器<br> 
2015-12-12<br> 
【启动器】重做 启动器<br> 
【项目】更改 子程序引用启动器<br> 
【普通计算器】完成 普通计算器<br> 
2015-12-19<br> 
【解析几何图像】重做 解析几何图像-特殊方程（圆、椭圆、双曲线），使用交互输入方式<br> 
【解析几何图像】新增 保存图像<br> 
【解析几何图像】新增 鼠标滚轮放大缩小<br> 
【解析几何图像】修复 图像的顶部和底部有时无法画全<br> 
【解析几何图像】修复 画好图像后移动到不可见范围或最小化后还原，图像缺失。使用bitmap作为中介将graphics和panel进行绑定<br> 
【解析几何图像】修复 即使函数图象的输入框为空也可以按确定<br> 
2015-12-20<br> 
【解析几何图像】新增 自动确定最佳网格大小，并在缩放时可以生效<br> 
【解析几何图像】新增 恢复初始设置<br> 
【解析几何图像】修复 自变量前有负号时无法绘制<br> 
【解析几何图像】优化 窗口和绘制区大小及比例<br> 
2015-12-21<br> 
【解析几何图像】新增  图像绘制方式 选择<br> 
【解析几何图像】修复 不显示参数方程参数区间标签<br> 
【解析几何图像】修复 “清空”按钮失效<br> 
2015-12-22<br> 
【解析几何图像】优化 曲线平滑度，点坐标改为浮点平面点PointF<br> 
【解析几何图像】优化 界面布局，重排界面控件<br> 
【解析几何图像】优化 改为只在绘图区内滚动鼠标才有缩放功能<br> 
2015-12-26<br> 
【解析几何图像】新增 双曲线的虚轴端点、焦点、渐近线<br> 
【解析几何图像】新增 椭圆的焦点<br> 
【解析几何图像】修复 椭圆输入时a<b也可以按确定<br> 
【解析几何图像】优化 曲线在屏幕上端及下端的显示效果<br> 
【解析几何图像】优化 在新线程绘制图像，在绘制时不假死<br> 
【解析几何图像】优化 界面布局，更加宽松，设置项保持与底部距离不变，排齐GroupBox的左右<br> 
【解析几何图像】优化 为了抵消使用线程造成的性能下降，更改默认精度为5<br> 
2016-1-1<br> 
【启动器】优化 启动器使用单独的方法<br> 
【启动器】优化 启动器启动与屏幕中央<br> 
<br> 
2016-2-5起，开始将”数学工具“从WinForm移植至WPF<br> 
<br> 
2016-2-5<br> 
【解析几何图像】开始移植数学工具从winForm到WPF，开始做界面<br> 
2016-2-6<br> 
【解析几何图像】继续移植界面，并更改了CheckBox的样式<br> 
2016-2-7 <br> 
【解析几何图像】继续移植界面，并更改了Button、RadioButton等样式，去掉边框、更改为win10样式<br> 
【解析几何图像】开始移植后台代码，直接复制出现数百个错误<br> 
2016-2-8<br> 
【解析几何图像】继续移植代码。成功移植函数部分、缩放平易部分<br> 
2016-2-9<br> 
【解析几何图像】移植限制输入部分、键盘操作部分、读配置项部分<br> 
2016-2-10<br> 
【解析几何图像】移植写配置项部分、参数方程部分、点的绘制方式部分，并移植贝塞尔曲线。至此，基本功能已完成。<br> 
2016-2-16<br> 
新增 自定义错误提示框<br> 
【解析几何图像】优化 缩放平移后自动判断性能，若可行则重绘<br> 
2016-2-27<br> 
【解析几何图像】新增 基本的拖动画面功能（未完成）<br> 
2016-2-28<br> 
【解析几何图像】修复 拖动画面功能，包括：<br> 
拖动时坐标系又有时不能完全显示<br> 
拖动时有时图形消失<br> 
拖动时若光标移至绘图区域外导致拖动失败<br> 
范围较小时坐标系数字显示为不精确的十余位小数<br> 
【解析几何图像】修复 “方形网格”在绘图区域长宽不等时会成为长方形<br> 
2016-3-5<br> 
【解析几何图像】新增 各种缩放按钮<br> 
【普通计算器】完成 普通计算器<br> 
【解析几何图像】修复 “保存”和“清空”按钮失效<br> 
【启动器】启动 启动器<br> 
2016-3-6<br> 
【启动器】完成 启动器<br> 
【解方程】完成 二分法解方程<br> 
2016-3-12<br> 
【解方程】启动 二元一次方程<br> 
【解方程】完成 二元一次方程布局<br> 
2016-3-13<br> 
【解方程】完成 一元二次方程<br> 
【解析几何图像】修复 部分TextBox布局变形<br> 
【解析几何图像】修复 部分TextBox无法删光文字<br> 
<br> 
2017-3-4<br> 
时隔一年，再次重启项目<br> 
更改项目名称为《解析几何》<br> 
重构计划-完成解析几何图像类中XMAL控件名称规范化<br> 
2017-3-8<br> 
增强对触控屏的支持，增加双指缩放和单指平移功能（相对于以前的模拟鼠标单指平移性能有较大降低）<br> 
2017-3-9<br> 
重构计划-完成解析几何图像类中代码文件的方法、事件名称规范化<br> 
重构计划-更改所有类名为英文<br> 
增加同时画多个图像功能，取代“自动清空”功能；设置输入区域可以自动伸展<br> 
修复了以前因为闪退导致暂时停用的配置项保存功能<br> 
修复了缩放超出范围导致的FC，并增加提示语。<br> 
将颜色选择对话框的按钮语言改为中文<br> 
修复了【解方程】中当无法使用二分法解方程时输出错误答案的BUG<br> 
修复了【解方程】中当所求解为区间的整数分之一时无法输出正确解的BUG<br> 
增加窗体和程序图标<br> 
修复了【提示框】和【错误提示框】显示在任务栏的BUG<br> 
修复了【普通计算器】启动时没有显示在屏幕中央的BUG<br> 
修复了某些应该输入数字的文本框无法输入“-”号的BUG<br> 
修复了发现输入内容不对后光标回到最前面的BUG<br> 
2017-3-10<br> 
针对小尺寸屏幕优化，新增鼠标滚轮在操作区域上下滚动能上下平移操作区的功能<br> 
2017-3-12<br> 
修复了保存图片的默认名称无法保存的BUG<br> 
修复了一些函数在斜率大的部分拖动时无法完全显示的BUG，并减少了部分判断<br> 
修复了参数方程图像完全无法绘制的BUG<br> 

