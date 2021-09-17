# Build My Workflow
工欲善其事必先利其器，选择好如何配置自己的工作环境，会让自己写程序和作业时更得心应手，节省时间。  

作为初学者，我们基本能做的事就是“编辑”，“调试”和“运行”  
因此我们要清楚，什么软件是做哪个操作的，以及我们要选择适合自己的方式来编写程序文件。  

**记住这个简化流程**：本学期我们大多数时候在做的  
1. 在**编辑器**里写代码（我在哪个窗口写东西？）  
2. 让**解释器**运行你的代码（我的Python本体装在哪？）  
3. 用**终端**呈现解释器运行的结果（我在哪个窗口看到结果？）  

## 0.一个概念：编辑器和IDE（集成开发环境）
IDE重点在于开发，一个成型的项目需要版本控制、代码组织等功能。通常需要付费，也有适用于小型开发者的免费版本。  
编辑器在于编辑代码 *（如果你愿意的话，Windows记事本就是一个编辑器）*，写小型的程序或者片段是足够的，运行交给解释器（interpreter）跑一下结果就能看了。  
相比于IDE，编辑器更轻量，只需要编写文本和运行，因此性能要求不高，运行快。  
  
对于初学者来说，一个编辑器足矣。若想要尝试体验完整的开发环境，或有志于发展计算机方面的同学可以选择安装IDE。
  
使用Python时可选的  
IDE：PyCharm、Wingide、LiClipse、Visual Studio（VS，适用于大多数语言的开发）等  
编辑器：Visual Studio Code（VS Code）、Vim、Atom、Emacs、Sublime等  
也许后面几种学习成本较高，下面只会写到相对易用的VS Code  

选择你的~~英雄~~配置
## 1. 只装Python，使用IDLE编辑和调试文件，使用系统的命令行运行。
优点：占用地方小，干净  
缺点：IDLE编辑器极其简陋，默认字体不适合编程，语法高亮不丰富，只能通过pip进行包管理，管理虚拟环境很麻烦  
**不建议经验少的同学使用**  
  
看到安装编辑器之前就行↓  
https://zhuanlan.zhihu.com/p/111168324?from_voters_page=true  

## 2. 只安装Anaconda，可以使用IDLE以及jupyter notebook编辑，在命令行里运行。
优点：Anaconda相当于Python本体多加了常用的软件包以及conda包管理器，也就是说，需要手动安装的包变少了，并且你可以使用pip和conda两种方式来安装需要的包。  
你还可以用**conda命令**和Navigator中的图形化管理器来管理虚拟环境。  
在Navigator中你还可以选择安装jupyter notebook，这样你又多了一个编辑器，它可以编写小的片段并运行，**非常适合写本学期的作业**。  
缺点：但IDLE和jupyter notebook界面简陋仍有较差编写体验。

【IDLE和jupyter notebook】
<img width="1377" alt="Screenshot 2021-09-17 092534" src="https://user-images.githubusercontent.com/10933927/133709260-afbd0223-e7b9-4b89-8a7c-e0dbfda083f8.png">

如果你的用户名文件夹没有中文字符，可以选择安装到Just Me，也可以按文中所说安装到All users  
记住**不要**勾选“Add Anaconda to the system PATH environment variable”，否则容易出现问题，文中有写到如何自己添加环境变量（environment variable）↓  
https://zhuanlan.zhihu.com/p/75717350  

## 3. 在Anaconda的基础上，加装Visual Studio Code编辑器
Visual Studio Code是功能非常强大的编辑器，界面美观，适用于多种语言的编写  
内置的编辑器和jupyter notebook插件可以取代2.中的编辑界面。  
运行代码也可以在内嵌的终端（terminal）里输出结果。  

【VS Code里的编辑器、jupyter notebook，内置终端（下方）和Windows Terminal（右侧）】  
<img width="1794" alt="Screenshot 2021-09-17 093848" src="https://user-images.githubusercontent.com/10933927/133710124-61478d54-5d52-44e2-aede-c9d9e906a231.png">

先装Anaconda，再装VS Code(建议自己安装，而不是在Navigator里安装VS Code)  
https://code.visualstudio.com/  
注意选好版本  
![image](https://user-images.githubusercontent.com/10933927/133658830-8f4ff80d-93e8-4bde-bae4-e486bac4955d.png)

建议四个都勾选  
![image](https://user-images.githubusercontent.com/10933927/133659274-09025ed7-400a-401b-8537-8571c5926383.png)

### VS Code 添加插件
在界面左侧有四个小方格的按钮，点击它并在弹出的搜索栏上搜索Python，安装第一个即可  
如果界面为英文，可以搜索Chinese，安装中文界面  
另外还可以安装一个CodeSnap，分享代码时比较美观  
在网上搜索VS Code插件推荐可以发掘VS Code的更多功能  
https://cloud.tencent.com/developer/article/1796162  

## 4. （IDE）只安装Pycharm
Pycharm提供了完整的开发环境，自带Python。相比于Ananconda，Pycharm提供了体验更好的图形化**环境**管理器和**包**管理器。  
运行和调试同样可以在内置的终端中运行，类似于3.  
**经测试，目前在M1 Mac上，部分包的安装过程会出现问题（scipy，Python3.9），需要额外配置一个本地Python环境并使用homebrew，较为麻烦，因此不建议在M1 Mac上使用Pycharm**  

【Pycharm界面：编辑器和终端】  
<img width="1431" alt="0a41c44876fa535c3bd4ee4044619ec" src="https://user-images.githubusercontent.com/10933927/133711166-213b87ee-8fa5-4a93-b3da-cf99bf505c44.png">

安装免费的Community版即可  
https://www.jetbrains.com/pycharm/
安装过程  
https://zhuanlan.zhihu.com/p/108439489

## Mac同学需要注意的
由于**M1**和**Intel**版本不同，因此会有些许不同  
**查看自己的系统信息**：点击左上角苹果菜单  >“关于本机”  
  
不论你安装了**Python**还是**Anaconda**，建议都加装一个**VS Code**  
**Python：**  
**M1**的同学建议选择左侧的**3.9.7，universal2 installer**。**Intel**选择Intel installer。  
Intel也可以选择其他版本，如3.7.12。  
https://www.python.org/downloads/macos/  

**Anaconda：**  
在网页最下方的中间选择**64-Bit Graphical Installer (440 MB)**  
https://www.anaconda.com/products/individual-d  

**VS Code：**  
选择macOS Universal （Stable：稳定版，Insiders：内测版），下载后会自动解压，在访达里查看下载，拖到左边“应用程序”里即可。  
https://code.visualstudio.com/  

别人的安装过程，如果下载速度太慢，取消后再重试几次  
https://blog.csdn.net/weixin_39845206/article/details/113452816?

## 其他需要做的
### 配置环境变量
这一步需要注意“用户变量”和“系统变量”两个名词，如果按教程里操作的运行不成功可以试试在“系统变量”的PATH里也添加一下  
参考2.中的链接  
或者这个简易版：  
https://blog.csdn.net/Quest_sec/article/details/104466280  

### 配置清华镜像源
使用pip或conda下载包时，因为服务器在国外，也许速度会很慢。需要设置从国内的镜像服务器来下载，例如清华大学的开源镜像站  
参见2.中链接文章的第六部分  

### 配置系统终端
如果你选用前三种方式，还可以配置你的系统终端来快速进行一些命令操作。  
Windows常用的系统终端有cmd和Powershell，都自带在系统中。当你完成了**配置环境变量**后，你就可以在系统的命令行里配置python环境。  
如果你想使用更美观的界面，可以在Microsoft Store里安装Windows Terminal，或者Windows Terminal Preview（前者的预览版）。  

### 一些不重要的链接存档
Mac OS安装Anaconda后无法在终端使用conda命令怎么办？  
https://zhuanlan.zhihu.com/p/144550389  
一招解决Conda安装卡在solving environment这一步！  
https://blog.csdn.net/qazplm12_3/article/details/108924561  
