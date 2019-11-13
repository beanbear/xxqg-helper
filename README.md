# 公告！！！
* 本助手只供个人**学习Auto.js**使用，不得用于**其它违法或商业用途**，否则造成的一切**后果自负！**

# 注意事项&&常见问题！(必看!)
* 1.部分手机**收藏和分享按钮**控件找不到，运行到收藏分享步骤时会报错，请将`articleStudy()`函数中的`CollectAndShare(i)`函数删除
* 2.**华为**部分机型console不支持，如报错中含有'huawei'关键字请将主函数中`console.show()`函数删除
* 3.请更新auto.js版本至**4.0.0beta或 4.0.1beta**,否则部分手机会有兼容性问题，进入文章页会找不到按钮等控件会**自动退出！**
* 4.尽量**不要在凌晨运行**，凌晨当天新闻没有刷新，请在**早上10点之后运行！**，10点之后当天的文章会出来很多
* 5.运行时请保持**网络畅通**，建议在**WIFI**状态下使用，否则中途加载页面或按钮过慢会**出错**！

# 使用方式 
* 下载Auto.js 4.0.0版本apk并安装
* 打开Auto.js导入最新版xxqg.js文件
* 点击右上角“运行”按钮运行,(运行会提示打开无障碍模式)

# v2.7beta3最新版
* 更新了学习步骤：**百灵小视频->电台+文章->电台**，广播和文章同时进行，大幅缩短时间。
* 新增控制台`console`打印学习进程，之前`toast`弃用
* 现在凌晨也能学习，找不到当天新闻自动学习昨日新闻
* **新增页面检测**，意外情况离开页面会有提示并停止计时，返回界面继续计时
* 修复文章界面有时会加载视频的情况

# v2.6版本更新
* 巨大更新，文章学习根据当天日期抓取当天的文章，不再重复学习昨天的文章！
* 修复了某些情况下由于个别手机加载速度慢导致进入文章页抓取不到页面秒退的情况

# v2.5.1更新
* 修复新闻进入“专题”一栏无法跳出bug
* “电视台”改为“中央广播电视总台”

# v2.5版本更新
* app又换了布局导致按钮控件不能用了（无奈- -），这次又修改了控件抓取，收藏分享评论又能用了
* 评论随机，评论过后删除
* 学习文章时滚动，学习时间随机上下波动10秒
* 分享改为app内分享，不用打开微信

# v2.4版本更新
* 新增评论功能，可自行修改commentText评论内容
* 将点赞与分享整合进前两篇文章学习过程中，节约了一定时间，不再视频学习完之后单独点赞分享

# v2.3版本更新
* 更新了视频学习逻辑，延长第一个视频（30分钟新闻联播正片）的学习时间，缩短了下面小新闻片段的学习数量和时间，分数更加准确
* 新增总运行时间统计

# v2.2版本更新
* 因为最新版app更换了页面布局,所以更改了按钮控件的抓取

# v2.1版本更新
* 新增弹窗函数，防止部分手机息屏
* 新增延时函数，单位由之前毫秒统一为秒

# v2.0版本更新
* 基于控件点击,不再基于屏幕坐标点击,更具有通用性
* 新增收藏和微信分享(2分)
* 修改若干bug
* “视听学习”更改为“电视台”

# 可修改变量
* `aCount`文章学习篇数,`vCount`小视频学习个数,`aTime`每篇文章学习时长(秒),`rTime`广播收听时长(秒),`vTime`每个小视频学习时长(秒) 
* 以上参数根据实际需要修改

# xxqg-helper学习强国助手
* Auto.js 学习强国APP助手，自动刷文章和视频分(24分 6+6+6+6)，支持收藏和分享(2分 1+1)，评论（2分），不支持自动答题
* 仅限Android系统，需下载auto.js并开启**无障碍模式**
* Android版本至少在5.0之上，**最好7.0之上**，7.0以下滑动等函数不能用！
* 测试环境:小米MIX 2S, MIUI 11, Auto.js V4.0.0beta
