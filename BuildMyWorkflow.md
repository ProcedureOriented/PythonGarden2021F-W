# Build My Workflow
此文档主要包括了在自己的电脑上建立工作环境的个人经验和搜集的经验  

## 0. 在配置工作环境之前
一些优化体验的小操作！  

### NKU_WLAN免验证自动登录
厌烦了每次连接校园网都要登陆？  
访问NKU_WLAN的IP地址，http://202.113.18.106/  
进入“自服务（Self）”，登录账号密码和登录校园网相同  
顶栏选择“服务”，再选择中间的 **“无感知MAC地址维护”**  
![8001130B486AB095813796F62EA7CEA9](https://user-images.githubusercontent.com/10933927/133569381-c234cc1e-0467-4b29-88be-6a9f26cceeba.jpg)

大概看一下在线状态和登录时间就知道是自己的哪台设备了，点击右侧的绑定即可，此后就忘记登录输密码这回事吧！  
来，试试看！  
<img width="637" alt="Screenshot 2021-09-16 153039" src="https://user-images.githubusercontent.com/10933927/133570125-217b2ba8-31b2-45c7-82c7-35e31ca41472.png">

### QuickLook【强烈推荐】
用空格就可以快速预览图片、PDF、文档等文件,不用再等漫长的打开过程（从macOS学的）  
（在电脑自带的Microsoft Store可以搜索到）  

### WinDynamicDesktop
让你的Windows电脑有媲美macOS的日夜间自动壁纸，晚上再也不用因为桌面刺眼了  
（在Microsoft Store可以搜索到）  

### TranslucentTB
让任务栏变透明或者模糊！桌面更开阔！  
（在Microsoft Store可以搜索到）  

### Tampermonkey【强烈推荐】
也称“油猴脚本”，主要加载一些用户脚本（User Script）以改变网页的表现或增加功能。  
（在Chrome/Chromium/Edge/Firefox中以拓展（Extension）形式安装）  
<img width="281" alt="Screenshot 2021-09-16 153801" src="https://user-images.githubusercontent.com/10933927/133570615-8c81ae81-2928-404a-81ad-c81d58dc490e.png">

#### 获取脚本的渠道
Greasy Fork  
包括了安装Tampermonkey的链接和搜索脚本功能  
https://greasyfork.org/zh-CN  
<img width="933" alt="Screenshot 2021-09-16 153950" src="https://user-images.githubusercontent.com/10933927/133571112-0775f74c-eeb5-4a05-be29-fc52ef981557.png">

*也有个人开发者会在互联网上发布自己的脚本*  
这里列举我用到的一些脚本

#### 网页夜间模式
https://github.com/syhyz1990/darkmode
在网页的右下角添加一个小按钮，使网页变成深灰色，比一般的调暗或变黄更舒适。  
夜间赶作业查网页时的好帮手！！

#### 视频加速！广告加速！
https://greasyfork.org/en/scripts/372673-%E8%AE%A1%E6%97%B6%E5%99%A8%E6%8E%8C%E6%8E%A7%E8%80%85-%E8%A7%86%E9%A2%91%E5%B9%BF%E5%91%8A%E8%B7%B3%E8%BF%87-%E8%A7%86%E9%A2%91%E5%B9%BF%E5%91%8A%E5%8A%A0%E9%80%9F%E5%99%A8
各视频网站刷剧必备！！广告光速读完，视频调速随心所欲（思政课慕课就不要倍速啦）。
鼠标移到网页左侧绿色的小圆球来调整速度。

#### CNKI 中国知网PDF全文下载
https://greasyfork.org/en/scripts/18842-cnki-%E4%B8%AD%E5%9B%BD%E7%9F%A5%E7%BD%91-pdf-%E5%85%A8%E6%96%87%E4%B8%8B%E8%BD%BD-%E7%89%B9%E5%88%B6%E7%89%88
在查询结果页点击下载可以直接下载pdf而不是caj文件

#### 解除知网复制限制CNKI copy
https://greasyfork.org/en/scripts/393843-%E8%A7%A3%E9%99%A4%E7%9F%A5%E7%BD%91%E5%A4%8D%E5%88%B6%E9%99%90%E5%88%B6cnki-copy

#### 文本选中复制
https://greasyfork.org/en/scripts/405130-%E6%96%87%E6%9C%AC%E9%80%89%E4%B8%AD%E5%A4%8D%E5%88%B6
除了知网的复制限制，你还可以用这个脚本解除其他网站的限制，比如百度文库等
在CSDN复制别人的代码的时候不用自己再登录了

#### 网页限制解除
https://greasyfork.org/en/scripts/28497-remove-web-limits-modified
叠BUFF！解除禁止复制、剪切、选择文本、右键菜单的限制，可以和上面两个一起用。
如果不生效可以在网页右上角的灰色选择框里打上勾

## 1. 配置环境
