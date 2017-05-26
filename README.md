# 个人长期收集整理的IOS资源大全
###更新日期：2017年-5月-26日
### 个人的能力是有限的，大家的共同努力才是王道，如有好的建议，好的文章、资源推荐。请加QQ：1213423761,或者QQEmail我。
##目录
*   [优秀源码](#sourcecode)
*   [深入学习](#depthStudy)
*   [实践Project](#resources)
*   [动画](#animation)
*   [键盘处理](#keyboard)
*   [权限请求管理](#competence)
*   [布局](#layout)
*   [提示、加载中](#hud)
*   [安全](#safety)
*   [照片选择、相片预览](#photoViews)
*   [侧边栏](#slideMenu)
*   [弹出视图](#popupMenu)
*   [弹出菜单](#popupMenu)
*   [网络](#network)
*   [其它UI](#otherUI)
*   [效率、优化](#effectiveness)
*   [硬件](#hardware)
*   [模块化](#modules)
*   [工具](#tool)
*   [Xcode插件推荐](#xcodeplugs)
*   [其它](#otherItem)
*   [微信小程序](#xcx)

## <a name="sourcecode"></a>优秀源码（站在巨人的肩膀、借鉴巨人的经验）

*   PHPHub一个论坛软件 语言：Object-c ★★★[官网](https://github.com/Aufree/phphub-ios)
*   ESTMusicPlayer 是基于 DOUAudioStreamer 开发的一款优雅简洁的音乐播放器 语言：Object-c ★★★[官网](https://github.com/Aufree/ESTMusicPlayer)
*   Twitter出口，家居商店应用 语言：Swift2。★★★[官网](https://github.com/twitterdev/furni-ios?url_type=39&object_type=webpage&pos=1)
*   Coding ios客户端 语言：Object-c 精品推荐。★★★★★[官网](https://github.com/Coding/Coding-iOS)
*   Yep 是一款非常小巧而轻量化的社交 App 语言：Swift。★★★★★[官网](https://github.com/CatchChat/Yep)
*   firefox-ios 火狐浏览器ios客户端源码。★[官网](https://github.com/mozilla/firefox-ios)
*   swiftWeather 一款精致的天气应用。 [官网](https://github.com/JakeLin/SwiftWeather)


## <a name="depthStudy"></a>深入学习

*   动画深入学习([图层树](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/1-%E5%9B%BE%E5%B1%82%E6%A0%91/%E5%9B%BE%E5%B1%82%E6%A0%91.md)、[寄宿图](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/2-%E5%AF%84%E5%AE%BF%E5%9B%BE/%E5%AF%84%E5%AE%BF%E5%9B%BE.md)、[图层几何学](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/3-%E5%9B%BE%E5%B1%82%E5%87%A0%E4%BD%95%E5%AD%A6/%E5%9B%BE%E5%B1%82%E5%87%A0%E4%BD%95%E5%AD%A6.md)、[视觉效果](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/4-%E8%A7%86%E8%A7%89%E6%95%88%E6%9E%9C/4-%E8%A7%86%E8%A7%89%E6%95%88%E6%9E%9C.md)、[变换](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/5-%E5%8F%98%E6%8D%A2/%E5%8F%98%E6%8D%A2.md)、[专有图层](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/6-%E4%B8%93%E6%9C%89%E5%9B%BE%E5%B1%82/6-%E4%B8%93%E6%9C%89%E5%9B%BE%E5%B1%82.md)、[隐式动画](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/7-%E9%9A%90%E5%BC%8F%E5%8A%A8%E7%94%BB/%E9%9A%90%E5%BC%8F%E5%8A%A8%E7%94%BB.md)、[显示动画](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/8-%E6%98%BE%E5%BC%8F%E5%8A%A8%E7%94%BB/%E6%98%BE%E5%BC%8F%E5%8A%A8%E7%94%BB.md)、[图层时间](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/9-%E5%9B%BE%E5%B1%82%E6%97%B6%E9%97%B4/%E5%9B%BE%E5%B1%82%E6%97%B6%E9%97%B4.md)、[缓冲](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/10-%E7%BC%93%E5%86%B2/%E7%BC%93%E5%86%B2.md)、[基于定时器的动画](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/11-%E5%9F%BA%E4%BA%8E%E5%AE%9A%E6%97%B6%E5%99%A8%E7%9A%84%E5%8A%A8%E7%94%BB/%E5%9F%BA%E4%BA%8E%E5%AE%9A%E6%97%B6%E5%99%A8%E7%9A%84%E5%8A%A8%E7%94%BB.md)、[性能调优](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/12-%E6%80%A7%E8%83%BD%E8%B0%83%E4%BC%98/%E6%80%A7%E8%83%BD%E8%B0%83%E4%BC%98.md)、[高效绘图](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/13-%E9%AB%98%E6%95%88%E7%BB%98%E5%9B%BE/13-%E9%AB%98%E6%95%88%E7%BB%98%E5%9B%BE.md)、[图像IO](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/14-%E5%9B%BE%E5%83%8FIO/%E5%9B%BE%E5%83%8FIO.md)、[图层性能](https://github.com/AttackOnDobby/iOS-Core-Animation-Advanced-Techniques/blob/master/15-%E5%9B%BE%E5%B1%82%E6%80%A7%E8%83%BD/15-%E5%9B%BE%E5%B1%82%E6%80%A7%E8%83%BD.md))。[gitBook排版官网](https://zsisme.gitbooks.io/ios-/content/)
*   IOS动画总结。[官网](https://github.com/yixiangboy/IOSAnimationDemo)
*   IOS 设计模式相关资料整理。[官网](https://github.com/skyming/Trip-to-IOS-Design-Patterns)
*   Objcn Objc中国，一个高质量的开发社区，为中国 Apple 开发带来最佳实践和先进技术。[官网](https://objccn.io/issues/)
*   Onevcat王巍博客，ObjC 中国与 objc.io 合作最新作品《函数式 Swift》,《Core Data》及《Swift 进阶》。[官网](https://onevcat.com/)
*   猿题库大神唐巧博客。[官网](http://blog.devtang.com/)

###<a name="practice"></a>实践Project
*   [MobileProject](https://github.com/wujunyang/MobileProject):MobileProject项目是一个以MVC模式搭建的开源功能集合,包含地图、二维码、jspatch、照片等等功能。
*   [HZExtend](https://github.com/GeniusBrother/HZExtend):mvc、mvvm实践

### <a name="swift"></a>swift
*   SwiftyJSON: swift json高效简洁解析:[官网](https://github.com/SwiftyJSON/SwiftyJSON)
*   FileKit 是一个 Swift 框架，提供了简单和富有表现力的文件管理。[官网](https://github.com/nvzqz/FileKit)
*   SwiftyUserDefaults 让 user defaults 用起来很愉悦.[官网](https://github.com/radex/SwiftyUserDefaults)
*   Alamofire 是用 Swift 写的 HTTP 网络库。[官网](https://github.com/Alamofire/Alamofire)
*   Timepiece:Swift 里直观的日期处理。[官网](https://github.com/naoty/Timepiece)
*   FSCalendar:自定义的 iOS 日历库[官网](https://github.com/WenchaoD/FSCalendar)
*   Valet钥匙串帮手：[官网] (https://github.com/square/Valet)

###<a name="animation"></a> 动画
*   Pop：一个 iOS 和 OS X 动画库，可以方便地实现由物理效果的交互。★★★★[官网](https://github.com/facebook/pop) [pop案例](https://github.com/WilliamZang/FastAnimationWithPOP)
*   AnimationEngine：可以在 iOS 上方便地构建高级自定义动画。[官网](https://github.com/intuit/AnimationEngine)
*   Awesome-iOS-Animation：一个动画项目的集合。[官网](https://github.com/jackyzh/awesome-ios-animation)
*   RZTransitions：iOS View Controller 过场动画库。[官网](https://github.com/Raizlabs/RZTransitions)
*   Spring：一个简单的 Swift iOS 动画库。★★★★★[官网](https://github.com/MengTo/Spring)
*   Fluent：便捷的 Swift 动画框架。 ★[官网](https://github.com/matthewcheok/Fluent)
*   Cheetah：便捷的 iOS 动画库，由 Swift2 编写。 ★[官网](https://github.com/suguru/Cheetah)
*   RadialLayer：针对可点击元素的动画（类似于 Youtube Music）★[官网](https://github.com/soheil/RadialLayer)
*   TransitionTreasury:swift转场动画效果库，非常赞。★★★★[官网](http://transitiontreasury.com/) [github](https://github.com/DianQK/TransitionTreasury?url_type=39&object_type=webpage&pos=1)  

    ####皮筋动画
    *   [ElasticTransition](https://github.com/lkzhao/ElasticTransition):一个自定义模拟弹性的swift使用库 Oc版：[官网](https://github.com/taglia3/ElasticTransition-ObjC)。
  *   GooeyTabbar:非常棒的弹性菜单、弹出层效果。推荐指数：★★★★★[官网](https://github.com/KittenYang/GooeyTabbar)

    ####卡片切换
    *    MDCSwipeToChoose:社交、交友应用比较广泛的卡片切换效果。 [官网](https://github.com/modocache/MDCSwipeToChoose)
    *    ZLSwipeableViewSwift:swift语言实现的卡片切换。 [官网](https://github.com/zhxnlai/ZLSwipeableViewSwift)
    
    ####图片加载动画
    *   [RJImageLoader](https://github.com/rounak/RJImageLoader):下载图片、下载头像时比较适用，圆形进度下载，下载完有个圆形扩展的效果，非常棒。
    *   [PAAImageView](https://github.com/abiaad/PAAImageView):也是比较适合用在头像下载时的动效交互。

    ####icon过渡
    *   TBIconTransitionKit:图标与图标之间的切换交互效果，优化用户体验非常不错的选择。 [官网](https://github.com/AlexeyBelezeko/TBIconTransitionKit)
    *   BEMCheckBox:不错的复选框交互动效。 [官网](https://github.com/Boris-Em/BEMCheckBox#sample-app)
    
    ####视觉差
    *   JBParallaxCell:tableview实现的滚动视图视觉差特效。 [官网](https://github.com/jberlana/JBParallaxCell)
    *   MJParallaxCollectionView:CollectionView实现的滚动视图视觉差特效。 [官网](https://github.com/mayuur/MJParallaxCollectionView)

    ####转场动画
    *   BubbleTransition:模态圆形转场。 [官网](https://github.com/andreamazz/BubbleTransition)★★★★★
    *   SAInboxViewController:中间向两边展开过渡，灵感源于Inbox应用。 [官网](https://github.com/szk-atmosphere/SAInboxViewController)
    *   轻松自定义转场动画，精品推荐:[官网](https://github.com/lkzhao/Hero)★★★★★

    ####其它
    *   樱花飞舞:很有意思的动画效果，通过imageView和layer作用在一起就可以实现，非常不错的思路，值的借鉴。 [官网](http://code.cocoachina.com/view/130352)
    *   Shimmer:facebook开源的视图闪烁动效，主要用于文字荧光场景。 [官网](https://github.com/facebook/Shimmer)
    *   文字以打印机方式输入特效:挺有意思的一个动画。 [官网](http://code4app.com/ios/%E6%89%93%E5%8D%B0%E6%9C%BA%E8%BE%93%E5%87%BA%E7%89%B9%E6%95%88/53e1e4bd933bf030468b5362)
    *   LTMorphingLabel:多种文字变化，切换效果。不错，赞一个。 [官网](https://github.com/lexrus/LTMorphingLabel)
    *   label文字动画：[官网](https://github.com/overboming/ZCAnimatedLabel)

### <a name="keyboard"></a>键盘处理
*   [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager)：IQKeyboardManager是iOS中解决键盘弹起遮挡UITextField/UITextView的一种很实用的工具。无需输入任何代码,不需要额外的设置，精品推荐。★★★★★[官网](https://github.com/rsattar/Voucher)
*   TPKeyboardAvoiding:另一个不错的键盘遮挡解决方案。 [官网](https://github.com/michaeltyson/TPKeyboardAvoiding)

### <a name="competence"></a>权限请求管理
*   PermissionScope:智能的 iOS 授权 UI 和 统一的 API（支持位置、通知、照片、联系人、日历、照片、麦克风、BT、进度指示、HealthKit 和 CloudKit）。 [官网](https://github.com/nickoneill/PermissionScope)
*   Permission:便捷地请求用户权限（支持相机、照片、麦克风、联系人、位置）。 [官网](https://github.com/delba/permission)

### <a name="layout"></a>布局
*   Masonry：利用简单的，链式的语法发挥出自动布局 NSLayoutConstraints 的强大功能。 [官网](https://github.com/Masonry/Masonry)★★★★★
*   UIView-AutoLayout:简单的frame配合layout布局。 [官网](https://github.com/smileyborg/UIView-AutoLayout)
*   SnapKit:一个 iOS 和 OS X 的 Swift Autolayout 领域专用语言（DSL）。 [官网](https://github.com/SnapKit/SnapKit)
### <a name="hud"></a>提示、加载中
*   MBProgressHUD:强大的Hud显示、提供了多种hud状态、自定义简单灵活。 [官网](https://github.com/jdg/MBProgressHUD)
*   SVProgressHUD:简洁美观，轻量级的进度指示HUD。 [官网](https://github.com/TransitApp/SVProgressHUD)
*   NVActivityIndicatorView:非常全面的loading hud集合，总有适合你心意的。 [官网](https://github.com/ninjaprox/NVActivityIndicatorView)
*   RKNotificationHub:按钮边缘小红点的封装，有不错的动效。 [官网](https://github.com/cwRichardKim/RKNotificationHub)
*   JDStatusBarNotification:电池栏hud状态提示。 [官网](https://github.com/jaydee3/JDStatusBarNotification)
*   M13ProgressSuite:包含了很多 iOS 上用于显示进度信息工具的封装。 [官网](https://github.com/Marxon13/M13ProgressSuite)
*   NJKWebViewProgress:webview进度条封装。 [官网](https://github.com/ninjinkun/NJKWebViewProgress)

### <a name="safety"></a>安全
*   UICKeyChainStore:UICKeyChainStore 是一个对 Keychain 的简洁封装。 [官网](https://github.com/kishikawakatsumi/UICKeyChainStore)
*   SAMKeychain:SSKeyChain的作者是大名鼎鼎的SSToolkit的作者samsoffes。  [官网](https://github.com/soffes/SAMKeychain)

### <a name="photoViews"></a>照片选择，相片预览
*   ZLPhotoBrowser:方便易用的相册照片多选框架，支持拍照、预览快速多选；相册混合选择；原图功能等。 [官网](https://github.com/longitachi/ZLPhotoBrowser)
*   CorePhotoBroswerVC:本地图片和网络图片的预览库。 [官网](https://github.com/CharlinFeng/CorePhotoBroswerVC)
*   MISImagePicker:带裁剪功能的照片选择库。 [官网](https://github.com/maokebing/MISImagePicker)
*   IDMPhotoBrowser抽屉式展示图片浏览库。[官网](https://github.com/ideaismobile/IDMPhotoBrowser)
*   JTSImageViewController:具有深层次的图片浏览器。[官网](https://github.com/jaredsinclair/JTSImageViewController)
*   YLGIFImage:高性能的gif图片处理库。[官网](https://github.com/liyong03/YLGIFImage)

### <a name="slideMenu"></a>侧边栏
*   MMDrawerController:包含左右侧边栏、弹性动效，实现简单。精品。 [官网](https://github.com/mutualmobile/MMDrawerController)
*   AMSlideMenu:左右景深侧边栏，类之前QQ的景深侧边展示。 [官网](https://github.com/SocialObjects-Software/AMSlideMenu)
*   PKRevealController:视图靠着侧边栏，有些效果需要这种实现。 [官网](https://github.com/pkluz/PKRevealController)

### <a name="popupMenu"></a>弹出菜单
*   REMenu:弹性自定义弹出菜单，自定义灵活。 [官网](https://github.com/romaonthego/REMenu)
*   LiquidFloatingActionButton:流体状态的 Material Design 的浮动按钮。 [官网](https://github.com/yoavlt/LiquidFloatingActionButton)
*   circle-menu:圆形展开收起菜单。 [官网](https://github.com/Ramotion/circle-menu)

### <a name="network"></a>网络
*   YTKNetwork:猿题库基于AFNetworking封装。 [官网](https://github.com/yuantiku/YTKNetwork)
*   AFNetworking:你懂的，AFNetworking是一个非常方便的网络请求库,可以轻松实现各种网络请求。 [官网](https://github.com/AFNetworking/AFNetworking)
*   WHCNetWorkKit:简单的可后台下载文件的下载库。 [官网](https://github.com/netyouli/WHCNetWorkKit)
*   SGWiFiUpload:局域网wifi传文件实现封装。 [官网](https://github.com/Soulghost/SGWiFiUpload)

### <a name="pushView"></a>弹出视图
*   CNPPopupController底部弹出视图 [官网](https://github.com/carsonperrotti/CNPPopupController)
*   ZFDragableModalTransition底部弹出景深层，类似淘宝的购物弹出选择层一样[官网](https://github.com/zoonooz/ZFDragableModalTransition)
*   BubbleTransition圆润的圆形model视图：[官网](https://github.com/andreamazz/BubbleTransition)

### <a name="otherUI"></a>其它UI
*   QRCatcher:一个简洁美观的二维码扫描应用。 [官网](https://github.com/100mango/QRCatcher)
*   LBXScan:类QQ的二维码扫描封装。 [官网](https://github.com/MxABC/LBXScan)
*   CocoaLumberjack:一个快捷强大灵活的日志框架，可用于 iOS & Mac。 [官网](https://github.com/CocoaLumberjack/CocoaLumberjack)
*   NSLogger:一个高性能的日志工具，它可以显示运行在 OS X、iOS 和 Android 上客户端应用的踪迹。 [官网](https://github.com/fpillet/NSLogger)
*   SECoreTextView:可复制视图。 [官网](https://github.com/kishikawakatsumi/SECoreTextView)
*   BeautyAddressBook：通讯录封装。 [官网](https://github.com/hackxhj/BeautyAddressBook)
*   VideoBeautify:视频美化，功能酷似美拍,秒拍等应用的源码：对视频进行各种美化处理，采用主题形式进行分类，内含各种滤镜，动画特效和音效等。 [官网](https://github.com/xujingzhou/VideoBeautify)
*   charts:强大的图表库。 [官网](https://github.com/danielgindi/ios-charts)
*   KeychainAccess:指纹解锁库。 [官网](https://github.com/kishikawakatsumi/KeychainAccess)
*   PDTSimpleCalendar:一款简洁高大上的日历UI控件。 [官网](https://github.com/jivesoftware/PDTSimpleCalendar)
*   PINRemoteImage:渐进式过渡图片下载。 [官网](https://github.com/pinterest/PINRemoteImage)
*   TTTAttributedLabel:uilabel的替代品。 [官网](https://github.com/TTTAttributedLabel/TTTAttributedLabel)
*   HXEasyCustomShareView:封装精致的分享界面。 [官网](https://github.com/huangxuan518/HXEasyCustomShareView)
*   LTNavigationBar:导航栏动态伸展收缩着色。 [官网](https://github.com/ltebean/LTNavigationBar)
*   UICustomActionSheet:背景毛玻璃模糊ActionSheelt。 [官网](https://github.com/pchernovolenko/UICustomActionSheet)
*   RDVTabBarController：tabbar工具栏封装。 [官网](https://github.com/robbdimitrov/RDVTabBarController)
*   MZTimerLabel：实用的计时器控件，简单灵活。 ★★★[官网](https://github.com/mineschan/MZTimerLabel)
*   JVFloatLabeledTextField: 注重用户体验的”浮动标签模式”(Float Label Patter)的第一个实现,可以有效解决移动设备上进行表单输入时,无法边看表单提示边进行输入的困境,用户体验非常好。★★★★★[官网](https://github.com/jverdi/JVFloatLabeledTextField)
*   DSRoundedImageArticle :圆角渲染卡顿处理库。 [官网](https://github.com/walkdianzi/DSRoundedImageArticle)
*   TouchID：touchId的快速接入封装。 [官网](https://github.com/bringbird/TouchID)
*   FLAnimatedImage: iOS 的高性能 GIF 动画引擎库。 [官网](https://github.com/Flipboard/FLAnimatedImage)
*   ios-fontawesome:是一个形象字体库。通过扩展 NSString 来轻松使用 FontAwesome 字体。 [官网](https://github.com/alexdrone/ios-fontawesome)
*   AutocompleteField:友好的自动输入。 [官网](https://github.com/filipstefansson/AutocompleteField)
*   UzysAnimatedGifPullToRefresh:gif下拉刷新。 [官网](https://github.com/uzysjung/UzysAnimatedGifPullToRefresh)
*   MJRefresh:简单、灵活，一句话即可实现上拉下拉刷新 。 [官网](https://github.com/CoderMJLee/MJRefresh)
*   HTPullToRefresh:上拉下拉的另一种展现形式，左右滑动刷新，类似微信读书。 [官网](https://github.com/hoang-tran/HTPullToRefresh)
*   PhoneNumberKit:电话号码格式化处理插件。 [官网](https://github.com/marmelroy/PhoneNumberKit)
*   reel-search:快捷输入并选择。 [官网](https://github.com/Ramotion/reel-search)
*   MLEmojiLabel:label显示表情。  [官网](https://github.com/molon/MLEmojiLabel)
*   PageMenu ViewPager切换库：[官网](https://github.com/uacaps/PageMenu)
*   YPTabBarController:自定义TabBarController[官网](https://github.com/yuping1989/YPTabBarController)
*   APParallaxHeader头部拉伸或收起控件[官网](https://github.com/apping/APParallaxHeader)
*   JHUD一个不错的空视图管理[官网](https://github.com/jinxiansen/JHUD)
*   DZNEmptyDataSet 优秀的TableView出错页、空白视图封装[官网](https://github.com/dzenbot/DZNEmptyDataSet)
*   LGSublimationView渐变过渡展示页：[官网](https://github.com/lukegeiger/LGSublimationView)
*   RMPZoomTransitionAnimator图片放大转场：[官网](https://github.com/recruit-mp/RMPZoomTransitionAnimator)
*   电影选座库：[官网](https://github.com/ZFbaby/ZFSeatsSelection)

### <a name="effectiveness"></a>效率、优化
*   Aspects:面向切面编程简易实现库。精品。 [官网](https://github.com/steipete/Aspects)★★★★★
*   PINCache: 是 Pinterest 公司开发的一个快速，无死锁的并行对象缓存，支持 iOS 和 OS X 系统， 是 TMCache 的改进版本。 [官网](https://github.com/pinterest/PINCache)
*   YYKit:是一组庞大、功能丰富的 iOS 组件。 [官网](https://github.com/ibireme/YYKit)
*   AsyncDisplayKit：Facebook开源的能够提高UI流畅性并缩短响应时间的UI框架。 [官网](https://github.com/facebook/AsyncDisplayKit)
*   JsPatch:可以实时修复线上bug,快速安全、使用简单的强大热更新、热修复库。 [官网](http://jspatch.com/) 
*   GYDataCenter： 是一个高性能的SQLite数据库框架，提供了一套简单易用的面向对象的数据操作接口。[官网](https://github.com/Zepo/GYDataCenter)
*   GYHttpMock：用于iOS App网络层开发，可以截获指定的 HTTP request，并根据规则，完全替换或部分修改真实的网络返回数据。[官网](https://github.com/hypoyao/GYHttpMock)
*   AAMockData:有意义的测试数据模拟，方便生成测试数据。[官网](https://github.com/shiyuan17/AAMockData)
*   MLeaksFinder：只需要引入 MLeaksFinder，就可以自动在 App 运行过程检测到内存泄露的对象并立即提醒，无需打开额外的工具。[官网](https://github.com/Zepo/MLeaksFinder)
*   Object-c转JsPatch代码。 [官网](https://github.com/bang590/JSPatchConvertor)
*   LKDBHelper-SQLite-ORM：sqlite封装，ORM实现。 [官网](https://github.com/li6185377/LKDBHelper-SQLite-ORM)
*   apiary.io :创建文档API，可以快速让APP先调用，并行开发。 [官网](https://apiary.io/)
*   FBRetainCycleDetector:facebook开发的一款检查循环引用的类库。[官网](https://github.com/facebook/FBRetainCycleDetector)
*   AsyncDisplayKit:facebook开源的又一款精品，能够提高UI的流畅性并缩短响应时间。[官网](https://github.com/facebook/AsyncDisplayKit)★★★★★
*   TransitionKit：ios状态机，[官网](https://github.com/blakewatters/TransitionKit)
*   FDFullscreenPopGesture：全屏滑动返回[官网](https://github.com/forkingdog/FDFullscreenPopGesture)

**约束处理：**
*   UIView-FDCollapsibleConstraints:优雅的方式解决自动布局中子View的动态显示和隐藏的问题。 [官网](https://github.com/forkingdog/UIView-FDCollapsibleConstraints)
*   UITableView-FDTemplateLayoutCell:AutoLayout自动算高，高性能带缓存，百度出口。[官网](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell)

### <a name="hardware"></a>硬件
*   MotionKit:快捷从加速度传感器、陀螺仪和磁力传感器获取数据。 [官网](https://github.com/MHaroonBaig/MotionKit)
*   BabyBluetooth:蓝牙库封装。 [官网](https://github.com/coolnameismy/BabyBluetooth)
*   BluetoothKit：蓝牙通讯封装库。[官网](https://github.com/rhummelmose/BluetoothKit)
*   LocationManager:地理位置封装库。[官网](https://github.com/intuit/LocationManager)

### <a name="modules"></a>模块化
*   JLRoutes:可简单地处理复杂的URL schemes，无需进行任何类型的URL或者字符串解析。 [官网](https://github.com/joeldev/JLRoutes)
*   DeepLinkKit: 是多样的线路匹配，基于块的方式来处理深度链接。 [官网](https://github.com/button/DeepLinkKit)
*   objection： 一个轻量级的Objective-C依赖注入框架，使用灵活简单。 [官网](https://github.com/atomicobject/objection )
*   Typhoon: 另一个强大的 DI演注入框架，与objection相比来说，实现比较规范。两者都维护超过2年以上。
    
    ####模块化文章
    *    关于IOS依赖注入(DI)那些事。 [官网](https://runningyoung.github.io/2015/06/30/2015-08-04-dependency-injection/)
    *    依赖注入——让iOS代码更简洁。 [官网](http://blog.csdn.net/linshaolie/article/details/47037941#report)
    *   模块化开发iosApp。 [官网](http://xiongzenghuidegithub.github.io/blog/2016/02/26/mo-kuai-hua-kai-fa-iosapp%5B%3F%5D/)
    *   重构代码四、抽象接口的设计原则记录。 [官网](http://xiongzenghuidegithub.github.io/blog/2016/01/26/zhong-gou-dai-ma-si-,-chou-xiang-jie-kou-de-she-ji-yuan-ze-ji-lu/)
    *   Objection, 一个轻量级的Objective-C依赖注入框架。(简介及使用教程) [官网](http://www.tuicool.com/articles/AjmmQj3)
    *    围观神仙打架，反革命工程师《iOS应用架构谈 组件化方案》和蘑菇街Limboy的《蘑菇街 App 的组件化之路》的阅读指导。   [官网](http://reviewcode.cn/article.html?reviewId=20)
    *    蘑菇街 App 的组件化之路。 [官网](http://limboy.me/tech/2016/03/10/mgj-components.html)
    *   蘑菇街 App 的组件化之路·续。[官网](http://limboy.me/tech/2016/03/14/mgj-components-continued.html)
    *   iOS组件化思路－大神博客研读和思考。 [官网](http://www.jianshu.com/p/afb9b52143d4)    

### <a name="tool"></a>工具推荐
*   Dash: 文档管理工具,可以浏览API文档,以及管理代码片段工具的强大辅助工具。 [官网](https://kapeli.com/dash)★★★★★
*   Postman: 网络请求测试工具,有mac版及chrome插件版。 [官网](https://www.getpostman.com/) 
*   FarBox:Markdown一见倾心，写作工具。 [官网](https://www.farbox.com/service/app/desktop_editor)
*   SourceTree:一款不错的git客户端。 [官网](https://www.sourcetreeapp.com/)
*   Colorsnapper：一款实用的取色软件。 [官网](http://colorsnapper.com/)
*   ImageOptim: 一款基于Mac的图像“瘦身”软件,无损压缩图片。 [官网](https://imageoptim.com/mac) 

### <a name="xcodeplugs"></a>Xcode插件推荐 
*   Xcode8后插件已经被禁用，使得很多优秀的插件被墙死，在此提供两个方式让Xcode可以继续使用插件。**MakeXcodeGr8Again**是一个在不改变原有Xcode基本上，重新生成一个新的可以使用插件的Xcode。[官网](https://github.com/fpg1503/MakeXcodeGr8Again)。  
  **使用方法：**   
  1.使用MakeXcodeGr8Again生成一个新的Xcode需要等待一段时间，生成后名为：XcodeGr8。   
  2.随后我们可以安装插件管理器[Alcatraz](https://github.com/alcatraz/Alcatraz)。   
  3.使用插件管理器安装我们需要的插件，重新打开Xcode后，如果插件不存在，则用终端运行以下命令：
  
           find ~/Library/Application\ Support/Developer/Shared/Xcode/Plug-ins -name Info.plist -maxdepth 3 | xargs -I{} defaults write {} DVTPlugInCompatibilityUUIDs -array-add `defaults read /Applications/XcodeGr8.app/Contents/Info DVTPlugInCompatibilityUUID`
      
   **update_xcode_plugins**：第二个是使用脚本去掉签名，让Xcode可以继续使用插件，不推荐使用，如果提交应用的时候请删除，再进行提交。[官网](https://github.com/inket/update_xcode_plugins)
*   ESJsonFormat-Xcode:XCode神级插件，可以方便的通过json串生成实体属性，及MJextent映射。 [官网](https://github.com/EnjoySR/ESJsonFormat-Xcode)
*   injectionforxcode:ios 实时预览,Xcode插件。 [官网](https://github.com/johnno1962/injectionforxcode)
*   KSHObjcUML:ios 类图结构预览Xcode插件。 [官网](https://github.com/kimsungwhee/KSHObjcUML)
*   VVDocumenter：注释神器。大家懂的[官网](https://github.com/onevcat/VVDocumenter-Xcode)


### <a name="otherItem"></a>其它
*   收集的AppStore被拒理由大全。 [官网](https://github.com/jcccn/Why-Reject)
*   iOS资源大全中文版。 [官网](https://github.com/jobbole/awesome-ios-cn)
*   ibireme收集整理的iOS开发相关第三方库和使用工具。[官网](http://github.ibireme.com/github/list/ios/)
*   zhouhuanqiang收集整理的博客及开源项目:[官网](http://github.com/zhouhuanqiang/LearningIOS)
*   Analyze:关于iOS开源框架源代码解析的文章：[官网](https://github.com/Draveness/iOS-Source-Code-Analyze)
*   open-source-ios-apps:国外整理收集源码大全：[官网](https://github.com/dkhamsing/open-source-ios-apps)
*   android资源大全。  [官网](https://github.com/Rano1/Interactive-animation/blob/master/README.md)

### <a name="xcx"></a>微信小程序
*   **coolsite360:**小程序UI设计工具,在线进行小程序UI可视化设计，支持Flex布局， 
可导出符合小程序标准的代码供后续开发。 [官网](http://www.coolsite360.com/wxapps/)
*   **wafer：**快速构建具备弹性伸缩能力的微信小程序,是腾讯云面向广大开发者提供的小程序开发全栈资源套件，套件提供小程序会话管理服务和 WebSocket 信道服务，部署方式具备良好的弹性伸缩能力，可以快速应对业务的爆发增长，同时具备较低的开发门槛。 [官网](https://github.com/tencentyun/wafer)
*   **微信小程序客户端腾讯云增强SDK:** [官网](https://github.com/tencentyun/wafer-client-sdk)
*   **小程序flex布局1:**[官网](http://blog.csdn.net/sundayaaron/article/details/53487637)
*   **小程序flex布局2**[官网](https://github.com/icindy/wxflex)
*   **微信web端实时运行工具：**[官网](https://github.com/chemzqm/wept)

### <a name="othAll"></a>其它资源大全
**java资源大全**：[官网](https://github.com/jobbole/awesome-java-cn)
**Python资源大全**：[官网](https://github.com/jobbole/awesome-python-cn)
**JavaScript资源大全**：[官网](https://github.com/jobbole/awesome-javascript-cn)
**Css资源大全**：[官网](https://github.com/jobbole/awesome-css-cn)
**Ios资源大全**：[官网](https://github.com/jobbole/awesome-ios-cn)
**android资源大全**：[官网](https://github.com/jobbole/awesome-android-cn)
**C资源大全**：[官网](https://github.com/jobbole/awesome-c-cn)
**C++资源大全**：[官网](https://github.com/jobbole/awesome-cpp-cn)
**.Net资源大全**：[官网](https://github.com/jobbole/awesome-dotnet-cn)
**PHP资源大全**：[官网](https://github.com/jobbole/awesome-php-cn)
**MySql资源大全**：[官网](https://github.com/jobbole/awesome-mysql-cn)
**机器学习资源大全**：[官网](https://github.com/jobbole/awesome-sysadmin-cn)



