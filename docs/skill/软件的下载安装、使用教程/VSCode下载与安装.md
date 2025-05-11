!!! warning "个人版本的 VSCode 是完全免费的软件，如果软件提示收费，请勿缴费并将其删除，您下到了盗版软件"

## 0. 前提  
- 类似 `{xxx}` 大括号内不以叹号 `!` 开头的是每个人不同的，您需要根据您的情况进行修改  
- 类似 `{!xxx}` 大括号内以叹号 `!` 开头的是每个人不同的，但是无需修改，您只需要执行描述的操作即可  
- 前置知识  
    - [判断您的操作系统和系统架构](../计算机基础/判断您的操作系统和系统架构.md)  

## 1. 下载  
- 打开[VSCode下载页](https://code.visualstudio.com/Download)，选择您的 `操作系统` 下载对应包

## 2. 安装  
#### Windows  
1. 打开您下载的文件  
    - 该文件名称为 `VSCodeUserSetup-{!sys}-{!ver}.exe`，一般可以在 `下载` 文件夹中找到  
    - 如果您点击打开该文件，将会弹出安装窗口，如未能弹出请请教他人  
2. 阅读许可协议{--（如果您很闲）--}并点击 `我同意此协议`-`下一步`  
3. 选择您想要安装的 `目标文件夹`，并点击 `下一步`  
    - 请牢记您的安装目录，如果可以，建议安装在您指定的目录下，而非默认位置  
    - 如果您已经安装，软件的默认安装目录是 `C:\Users\{用户名}\AppData\Local\Programs\Microsoft VS Code`，其中 `AppData` 文件夹是隐藏的  
    - 如果您不知道要安装的目标文件夹是什么，问题不大，但最好请教他人，因为这是计算机的基础操作，但您也可以直接点击 `下一步`  
4. 选择开始菜单文件夹  
    - 建议直接点击 `下一步`  
    - 如果您清楚您在干什么，可以勾选 `不创建开始菜单文件夹`，或者更改此项  
5. 选择附加任务  
    - 建议全部勾选后点击 `下一步`  
    - 如果您清楚您在做什么，本页可以更改，但是强烈建议勾选 `添加到PATH（重启后生效）` 选项  
6. 点击 `安装` 后等待一会即可安装成功  
7. 安装后 `VSCode` 将自动打开，如果没有打开请通过 `搜索/Windows菜单栏/桌面图标` 找到并打开  
#### Mac  
1. 打开您下载的文件  
    - 该文件名称为 `VSCode-darwin-universal.zip`，一般可以在 `下载` 文件夹中找到  
2. 其中有一个文件，名称为 `Visual Studio Code`，请将其拖入 `访达`-`应用程序` 文件夹中  
3. 稍等片刻，在您的 `控制台` 中应该已经出现 `Visual Studio Code` 程序，请打开  

## 3. 基本配置  
#### 中文翻译包  
- 打开后的界面是英文的，首先自然是安装中文翻译包  
- 点击如下区域，此处被叫为 `扩展栏`  
    <center><img src="/resourses/技巧_软件的下载安装、使用教程_安装VSCode_001.png" alt="pic1"></center>  
- 在 `搜索框` 中输入 `简体`（或者 `中文`，随便什么，毕竟是搜索），然后点击 `Install`  
    <center><img src="/resourses/技巧_软件的下载安装、使用教程_安装VSCode_002.png" alt="pic2"></center>  
- 在右下角弹出的窗口中点击 `Change Language and Restart`，应用将重启，中文安装包已安装  
    <center><img src="/resourses/技巧_软件的下载安装、使用教程_安装VSCode_003.png" alt="pic3"></center>  
#### 额外扩展  
这里是一些推荐安装的额外的扩展，可能改善您的编程体验  

- `One Dark Pro` 颜色主题  
- `Material Icon Theme` 文件图标主题  
- `Better Comments` 注释着色
- 
#### 字体  
强烈建议使用 `Fira Code` 进行编程，其特有的连字系统将使您的代码更加易读美观  

1. [FiraCode下载与安装](FiraCode下载与安装.md)  
2. 在左下角 `设置`（齿轮）图标中点击 `设置`，搜索 `连字`  
3. 点击 `在 settings.json 中编辑`，修改 `"editor.fontLigatures": false` 为 `"editor.fontLigatures": true`  
4. 返回 `设置`，点击 `Editor: Font Ligatures` 左侧的 `设置`（齿轮）图标，点击 `将设置应用于所有配置文件`  

## 4. 特定语言配置  
#### Python  
1. [Python下载与安装](Python下载与安装.md)  
2. 安装 VSCode 关于 Python 的扩展  
    - `Python Extension Pack` 基础工具，包含了绝大多数需要使用的工具
3. 额外扩展
    - `LiveCode for python` 很厉害的同步 Python 实时演示插件


## 5. 额外事项
- [Windows执行代码时命令行乱码的修复](../计算机基础/Windows执行代码时命令行乱码的修复.md)