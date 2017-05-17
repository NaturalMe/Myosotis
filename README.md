# Myosotis
以严谨的态度，为iOS开发者甄选天下好物。

特点:

- Swift语言为主的第三方库、框架。
- 开发工具、资源整理。
- 持续更新。
- 少而精。

目录:

- [库和框架(按英文字母顺序排序)](#库和框架)
	- [动画 Animation](#动画)
	- [图表 Charts](#图表)
	- [数据库 Database](#数据库)
	- [硬件 Hardware](#硬件)
		- [相机 Camera](#相机)
		- [定位 Location](#定位)
	- [媒体 Media](#媒体)
   		- [音频 Audio](#音频)
   		- [视频 Video](#视频)
	- [网络 Networking](#网络)
	- [解析 Parsing](#解析)
	- [资源 Resources](#资源)
	- [社交 Social](#社交)
   	- [用户界面 UI](#用户界面)
   		- [警告视图 Alert View](#警告视图)
   		- [按钮 Button](#按钮)
   		- [轮播 Carousel](#轮播)
   		- [集合视图 Collection View](#集合视图)
		- [配色 Color](#配色)
   		- [下拉菜单 Drop Down](#下拉菜单)
   		- [图片 Image](#图片)
    	- [键盘 Keyboard](#键盘)
    	- [文字标签 Label](#文字标签)
    	- [权限 Permission](#权限)
    	- [分段控制 Segmented Control](#分段控制)
    	- [侧边栏 Slide Menu](#侧边栏)
  		- [开关 Switch](#开关)
		- [表格视图 Table View](#表格视图)
		- [文本视图 Text View](#文本视图)
		- [转场 Transition](#转场)
- [依赖和包管理工具](#依赖和包管理工具)
- [UI测试](#UI测试)
- [语法教程](#语法教程)
- [设计模式](#设计模式)
- [算法和数据结构](#算法和数据结构)
- [gitignore](#gitignore)
- [部署](#部署)
- [密码管理](#密码管理)
- [对比工具](#对比工具)
- [科学上网](#科学上网)
- [网络抓包](#网络抓包)
- [文档查看](#文档查看)
- [文本编辑器](#文本编辑器)
- [图片编辑器](#图片编辑器)
- [HTTP调试工具](#HTTP调试工具)
- [终端](#终端)
- [邮件管理](#邮件管理)
- [输入法](#输入法)
- [解压缩](#解压缩)
- [压缩](#压缩)
- [文件传输](#文件传输)
- [管理苹果设备](#管理苹果设备)
- [其他精选清单](#其他精选清单)

---

## 库和框架

### 动画
* [Pop](https://github.com/facebook/pop) - 一个可扩展的iOS和OS X的动画库，基于物理学的相互作用, facebook出品。
* [Spring](https://github.com/MengTo/Spring) - 极少代码就能实现抖动，扭曲，弹簧进入等弹性动画。

### 图表
* [Charts](https://github.com/danielgindi/Charts) - 漂亮的图表！支持iOS/tvOS/OSX。

### 数据库
* [Realm](https://realm.io/) - 开发人员和超过十亿用户的喜爱，
更快，更容易使用，最重要的是免费，并支持Java、OC、RN、Swift、Xamarin。

### 硬件

#### 相机
* [ImagePicker](https://github.com/hyperoslo/ImagePicker) - 集所有摄像头功能于一身，拍照时能同时选择图像，占用较小内存。暂不建议使用该库做一张照片的选择。
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - 包含自定义图像选择器和图像裁剪功能。

#### 定位
* [SwiftLocation](https://github.com/malcommac/SwiftLocation) - 简单高效的位置管理器。

### 媒体

#### 音频
* [AudioKit](http://audiokit.io/) - 强大的音频合成，处理和分析，平滑的学习曲线。

#### 视频
* [ijkplayer](https://github.com/Bilibili/ijkplayer) - Bilibili出品的视频直播库。

### 网络
* [Alamofire](https://github.com/Alamofire/Alamofire) - 可链接的请求/响应方式；URL / JSON/ plist中参数编码；上传文件/数据/流/多部分表单数据；下载使用申请或恢复数据；与NSURL证书认证；HTTP响应验证TLS证书和公钥钢钉；关闭进度和NSProgress；卷曲调试输出；全面的单元测试覆盖率；完整的文档。
* [Just](https://github.com/JustHTTP/Just) - 网址查询；自定义页眉；表单/body；重定向控制；多文件，表单值一起上传；基本/摘要式身份验证；cookie；超时；同步/异步请求；上传/下载进度的异步请求跟踪；链接标题；友好访问的结果；
* [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - 用Swift语言的闭包特性重写苹果的Reachability，检查网络连接状态。
* [Kingfisher](https://github.com/onevcat/Kingfisher) - 网络图片异步加载，多层高速缓存，可取消，支持UIImageView\NSImage\UIButton\GIF。

### 解析
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - 更好的方式应对Swift中的JSON解析。
* [JSONExport](https://github.com/Ahmed-Ali/JSONExport) - Mac应用，把SwiftyJSON解析结果JSON对象的object转为NSDictory后，用JSONExport自动生成模型文件(Swift模型推荐使用Struct)。

### 资源
* [R.swift](https://github.com/mac-cain13/R.swift) - 自动生成 Images，Custom fonts，Resource files，Colors，Localized strings，Storyboards，Segues，Nibs，Reusable cells对应的 enum 或 struct 文件。

### 社交
* [MonkeyKing](https://github.com/nixzhu/MonkeyKing) - 帮助你完成中国社交应用的登陆、分享。

### 用户界面
* [Material](https://github.com/CosmicMind/Material) - 动画和图形框架，使开发人员能够轻松地创建漂亮的应用程序。
* [tispr-card-stack](https://github.com/tispr/tispr-card-stack) - 卡片堆控件。

#### 警告视图
* [PMAlertController](https://github.com/Codeido/PMAlertController) - 漂亮的警告视图，支持自定义标题，图片（可选），字体，颜色，尺寸等。

#### 按钮
* [DOFavoriteButton](https://github.com/okmr-d/DOFavoriteButton) - 可爱的动画效果按钮，收藏、喜欢、点赞、笑脸。
* [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton) - 浮动操作按钮。
* [ZFRippleButton](https://github.com/zoonooz/ZFRippleButton) - 遵循谷歌设计的特效按钮，触摸感十足。

#### 配色
* [Chameleon](https://github.com/ViccAlexander/Chameleon) - 轻松的修改RGB值，快速的找出正确的颜色组合，不用担心您的文本在各种背景颜色下是否可读。

#### 轮播
* [LLCycleScrollView](https://github.com/LvJianfeng/LLCycleScrollView) - 支持纯图片、文本图片结合、横向滚动、纵向滚动、手势滑动、点击回调、图片数据的延时加载、占位图占位、系统UIPageControl位置设置，唯一补足是依赖了 Kingfisher 库。

#### 集合视图
* [AppStoreStyleHorizontalScrollView](https://github.com/terenceLuffy/AppStoreStyleHorizontalScrollView) - App Store 风格的水平滚动视图。

#### 下拉菜单
* [DropDown](https://github.com/AssistoLab/DropDown) - 漂亮的下拉菜单。

#### 图片
* [ImageHelper](https://github.com/melvitax/ImageHelper) - 扩展了 image 和 imageView，可以通过颜色，文字，截图等进行创建，轻松获取填充，剪裁，调整大小，设置特效等功能。

#### 键盘
* [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - 无需代码，无需设置，解决UITextField、UITextView键盘覆盖界面的问题。

#### 文字标签
* [ActiveLabel.swift](https://github.com/optonaut/ActiveLabel.swift)支持标签(#),提到(@)和url(http://)的文字标签。
* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) - 一个变形的文字控件，有多重变形效果。
* [Splitflap](https://github.com/yannickl/Splitflap) - 像机场、火车站里翻转的时钟那样的文字。

#### 权限
* [RequestPermission](https://github.com/IvanVorobei/RequestPermission) - 可定制的权限管理的漂亮对话框。提高用户允许的几率。只需两行代码，容易定制。

#### 分段控制
* [BetterSegmentedControl](https://github.com/gmarm/BetterSegmentedControl) - 支持滑动，可自定义文字颜色，背景颜色，圆角等属性。

#### 侧边栏
* [SlideMenuControllerSwift](https://github.com/dekatotoro/SlideMenuControllerSwift) - 高度可定制的侧边栏。

#### 开关
* [paper-switch](https://github.com/Ramotion/paper-switch)
[AnimatedSwitch](https://github.com/alsedi/AnimatedSwitch) - 打开开关时绘制父视图。

#### 表格视图
* [FoldingCell](https://github.com/Ramotion/folding-cell) - 可以折叠、展开单元格的表格。

#### 文本视图
* [NextGrowingTextView](https://github.com/muukii/NextGrowingTextView) - 自动调整高度的文本视图。

#### 转场
* [Hero](https://github.com/lkzhao/Hero) - 优雅的视图控制器转场库。

## 依赖和包管理工具
* [Cocoapods](https://cocoapods.org/) - Objective-C的项目依赖管工具。它有成千上万的库，支持搜索。
* [Carthage](https://github.com/Carthage/Carthage) - 去中心化管理工具。
* [SwiftPackageManager](https://github.com/apple/swift-package-manager) - 苹果出品的Swift包管理工具。

## UI测试
* [UI-Testing-Cheat-Sheet](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet) - 包含很多 UI Testing 详细的例子。

## 语法教程
* [the-swift-programming-language-in-chinese](https://github.com/numbbbbb/the-swift-programming-language-in-chinese) - 中文版 Apple 官方 Swift 教程《The Swift Programming Language》。

## 设计模式
* [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift)
* [Observable-Swift](https://github.com/slazyk/Observable-Swift) - 由于非NSObject没有通过KVC实现，所以无法对属性进行KVO。这个库用观察属性，泛型，闭包实现了一套对Swift类型进行观察的机制。

## 算法和数据结构
* [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club)

## gitignore
* [https://www.gitignore.io/](https://www.gitignore.io/) - 用命令行的方式轻松创建 `.gitignore`, 你可以在Github上找到源码。
* [gitignore](https://github.com/github/gitignore) - 这是GitHub的`.gitignore`文件模板集合。 Github官方出品，在Github.com上创建新的仓库和文件时，界面中可选择的`.gitignore`模板就是这个列表。

## 部署
* [fastlane](https://github.com/fastlane/fastlane) - 最简单的方法来自动构建和发布你的iOS和Android应用程序。解放双手神器，打包、上架等的繁琐操作将被自动化代替。

## 密码管理
* [1Password](https://1password.com/) - 目前在 Mac 和 iOS 上享誉最棒的密码管理软件，Mac 和 iOS 均有中文，但 Windows 对不起，可能1Password 官网对 Windows 有仇（因为 Windows 版本旧且太丑，目前无中文语言界面）。目前已经改为订阅模式，一个月3 or 4美元。
* [LastPass](https://www.lastpass.com/) - 目前跨平台做的软件最棒，可惜它采取密码保管有两种方式：上传服务端和本地端保管。我认为理想的安全应该是本地的，不是服务端，因为 Web 端具有被攻破的可能（已有新闻报道 LastPass 服务端被攻破），而且服务端根本没有必要保管的需要。费用可能没有1Pssword 这么负担不起，但年费仍然不轻，6x12=72大概（每月1美元，听说现在春节有优惠），都有中文语言但翻译看起来有点机械。

## 对比工具
* [Beyond Compare](http://www.scootersoftware.com/download.php?zz=dl4) - 好用但是收费的对比工具。
* fileMerge - Xcode自带的对比工具
![](https://github.com/NaturalMe/Myosotis/blob/master/fileMerge.png)

## 科学上网
* [shadowsocks](https://shadowsocks.com/) - 支持OS X, Windows, Linux, iOS, Android, OpenWRT 路由器等, $15.95一年。
* [Lantern](https://getlantern.org/) - 无限高速流量。

## 网络抓包
* [Wireshark](https://www.wireshark.org/) - 老牌网络抓包利器，各种平台都可以玩耍。
* [Charles](https://www.charlesproxy.com/) - 网络抓包利器加上代理功能，并支持自签名证书，所以可以用来在手机上抓取https的包。使用非常方便。付费软件，值得购买。

## 文档查看
* [Dash](https://kapeli.com/dash) - 搜罗了这个世界上几乎所有的编程语言文档，而且更新速度快。

## 文本编辑器
* [MacDown](http://macdown.uranusjr.com/) - MarkDown 语法的编辑器，个人感觉比 Mou 更好用。
* [Sublime Text](https://www.sublimetext.com/) - 轻量级的编辑器，是频繁的非常规查看／编辑代码／文档时一个不错的选择。

## 图片编辑器
* [GIMP](http://www.gimp.org) - 跨平台的图像编辑器，可用于GNU / Linux，OS X，Windows和更多操作系统。它是免费软件，您可以更改其源代码并分发您的更改。还有很多自定义选项和第三方插件。

## HTTP 调试工具
* [curl](https://curl.haxx.se/) - 利用URL语法在命令行方式下工作的开源文件传输工具。
![在浏览器的开发者工具中拷贝出cURL命令](https://github.com/NaturalMe/Myosotis/blob/master/Copy%20as%20cURL.png)

在浏览器的开发者工具中拷贝出cURL命令，可以发送给别人或技术支持，运行命令即可快速重现问题。

* [Postman](https://www.getpostman.com/) - 构建API请求的图形化工具，可以收藏请求，批量测试，共享收藏列表，创建不同环境（如开发环境、生产环境），导出为cURL命令，导出为多种编程语言代码。

## 终端
* [iTerm](https://www.iterm2.com/) - 如果你在终端上花费大量的时间，那么你会欣赏这个软件所有的小细节。 它是免费的软件，你可以找到Github的源代码。

## 邮件管理
* [spark](https://sparkmailapp.com/) - 智能收件箱。帮你快速查看重要内容，可以用自然语言搜索邮件，仅在重要邮件时通知，邮件可以与日立交互，用户体验满分。

## 输入法
* [鼠鬚管](http://rime.im/) - 不止于拼音、注音、仓颉、速成、五笔、双拼、粤拼、吴语、中古汉语拼音、五笔画、Emoji、国际音标、宫保拼音…… 读《方案设计书》，亲手来创作，把输入法变成理想的模样。

## 解压缩
* [The Unarchiver](http://unarchiver.c3.cx/unarchiver) - 双击解压操作方便，免费，无广告，解压快，并且几乎不会出现乱码。

## 压缩
* [Keka](http://www.kekaosx.com/zh-cn/) - 该应用支持在创建压缩包时将 Mac OS X 在文件夹下自动生成的隐藏系统文件排除，且压缩包包含文件名编码信息，不会造成文件在 Windows 下解压缩时文件名乱码。

## 文件传输
* [Send Anywhere](https://send-anywhere.com/) - Send Anywhere 是一款极其强大的文件传输工具，无论是传输速度，还是支持的平台以及文件类型都达到了相当出色的水平。它的主界面只有两个按钮：「发送」和「接收」，点击发送之后选择需要发送的文件类型，然后选择相应的文件点击发送即会生成一组六位数字，在接收端点击「接收」输入这六位数字即可。操作起来简单直观。

## 管理苹果设备
* Apple Configurator - 管理苹果设备(iPad, iPhone, iMac, Mac etc.)配置文件的工具。请在 Mac App Store 搜索下载。

## 其他精选清单
* [awesomeios](https://github.com/vsouza/awesome-ios) - 非常好的iOS的框架，库，教程，Xcode的插件，组件以及更多的精选名单。如框架，组件测试和其他开源项目，免费和付费服务。
