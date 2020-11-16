[![Awesome libGDX Logo](logo.png 'Awesome libGDX Logo')](https://libgdx.badlogicgames.com/)

# Awesome libGDX [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/rafaskb/awesome-libgdx#contributing)

> <a href="https://libgdx.badlogicgames.com/"><img src="https://libgdx.badlogicgames.com/img/logo.png" alt="libGDX Logo" align="right" style="margin-right: 25px" height=40></a>
>
> [libGDX](https://libgdx.badlogicgames.com/) 是一个相对较低级别的，免费的，开源的，用Java编写的跨平台游戏开发框架.
>
> 这个列表是一个精选的资源，工具，教程， 以及使用 [libGDX](https://libgdx.badlogicgames.com/) 游戏框架的项目，帮助开发人员制作出符合 [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md) 的真棒游戏。
>
> 非常欢迎查看，但请先请参阅 [贡献](#contributing).


---


## 内容

- [资源](#resources)
  - [人工智能](#artificial-intelligence)
  - [控制器](#controllers)
  - [实体组件系统 (ECS)](#entity-component-system-ecs)
  - [物理](#physics)
  - [服务](#services)
  - [启动和部署](#setup-and-deployment)
  - [用户界面](#user-interface)
  - [视觉效果](#visual-effects)
  - [其他](#others)
- [教程](#tutorials)
  - [入门](#getting-started)
  - [高级](#advanced)
- [资产](#assets)
- [社区](#community)
- [其他清单](#other-lists)


---


## 资源

_可以在libGDX代码中使用的资源来增强框架的功能。_

### 算法与人工智能
- [gdx-ai](https://github.com/libgdx/gdx-ai) - 具有转向行为，编队运动，寻路，行为树和有限状态机的人工智能框架。
- [Simple Graphs](https://github.com/earlygrey/simple-graphs) - 用于图形数据结构和算法（包括快速路径查找）的Java库。

### 控制器
- [Controllers](https://github.com/libgdx/libgdx/wiki/Controllers) - 添加对游戏手柄和操纵杆的支持。
- [gdx-controllerutils](https://github.com/MrStahlfelge/gdx-controllerutils) - 添加了Scene2D按钮输入支持，用户可配置的按钮映射以及LWJGL2的热插拔功能。
- [sdl2gdx](https://github.com/electronstudio/sdl2gdx) - 使用SDL的强大游戏手柄实现。在相同的映射，隆隆声和热插拔下支持数百个控制器。

### 实体组件系统 (ECS)
- [Artemis-odb](https://github.com/junkdog/artemis-odb) - 基于Java的高性能实体组件系统框架。
- [Ashley](https://github.com/libgdx/ashley) - 受Ash＆Artemis启发的Java实体系统。

### 物理
- [Box2D](https://github.com/libgdx/libgdx/wiki/Box2d) - 最受欢迎的2D游戏物理库之一。
- [Bullet](https://github.com/libgdx/libgdx/wiki/Bullet-physics) - 3D碰撞检测和刚体动力学库。
- [jbump](https://github.com/tommyettinger/jbump) - 易于实现的AABB碰撞检测，对平台游戏和其他简单2D游戏很有用。

### 服务
- [gdx-facebook](https://github.com/TomGrill/gdx-facebook) - 为Facebook Graph API提供跨平台支持。
- [gdx-fireapp](https://github.com/mk-5/gdx-fireapp) - Firebase的跨平台API。
- [gdx-firebase](https://github.com/TomGrill/gdx-firebase) - 用于Firebase的跨平台（仅台式机/ Android）API。
- [gdx-gameanalytics](https://github.com/MrStahlfelge/gdx-gameanalytics) - libGDX的游戏分析 REST API客户端实现。适用于所有后端。
- [gdx-gamesvcs](https://github.com/MrStahlfelge/gdx-gamesvcs) - 轻松集成游戏服务，例如Google Play游戏，Apple Game Center等。
- [gdx-pay](https://github.com/libgdx/gdx-pay) - 为InApp购买提供跨平台API。
- [steamworks4j](https://github.com/code-disaster/steamworks4j) -精简包装，允许Java应用程序访问Steamworks C++ API。

### 启动和部署
- [gdx-liftoff](https://github.com/tommyettinger/gdx-liftoff) - libGDX的现代安装工具，使用当前的Gradle 5.x系列。
- [Packr](https://github.com/libGDX/packr) - 打包您的JAR，资产和JVM，以在Windows，Linux和macOS上分发。

### 用户界面
- [Freetype](https://github.com/libgdx/libgdx/wiki/Gdx-freetype) - 从轻量级的.ttf字体文件动态生成所需大小的BitmapFonts。
- [gdx-dialogs](https://github.com/TomGrill/gdx-dialogs) - 为本地对话框提供跨平台支持。
- [gdx-skins](https://github.com/czyzby/gdx-skins) - 免费的Scene2D GUI皮肤。
- [InGameConsole](https://github.com/StrongJoshua/libGDX-inGameConsole) - 允许开发人员在其游戏中添加控制台（类似于Source游戏中的功能）。
- [msdf-gdx](https://github.com/maltaisn/msdf-gdx) - 提供轻量级实用程序以在libGDX上绘制高质量的MSDF（多通道有符号距离字段）文本。
- [PieMenu](https://github.com/payne911/PieMenu) - Scene2D的径向菜单，高度灵活且易于自定义。
- [Ray3K Skins](https://ray3k.wordpress.com/artwork/) - 具有示例代码，自定义可绘制对象和实验功能的免费Scene2D.UI外观。
- [Skin Composer](https://github.com/raeleus/skin-composer) - 使用图形界面为libGDX scene2d.ui创建皮肤。
- [TenPatch](https://github.com/raeleus/TenPatch) - libGDX的9patch实现的替代方案，它实现了多个拉伸区域。
- [TypingLabel](https://github.com/rafaskb/typing-label) - 一个libGDX标签，看起来就像是实时键入的一样。
- [VisUI](https://github.com/kotcrab/vis-ui) -允许使用scene2d.ui在libGDX中创建漂亮的UI。请注意，这不是UI编辑器。

### 视觉效果
- [Box2DLights](https://github.com/libgdx/box2dlights) - 2D照明框架，该框架使用Box2D进行光线投射，并使用OpenGL ES 2.0进行渲染。
- [gdx-vfx](https://github.com/crashinvaders/gdx-vfx) - 基于libgdx-contribs-postprocessing的灵活的后期处理着色器视觉效果。
- [libgdx-screenmanager](https://github.com/crykn/libgdx-screenmanager) - libGDX的屏幕管理器，支持各种过渡效果。
- [Particle Park](https://github.com/raeleus/Particle-Park) - 带有实时预览的可下载粒子效果展示。
- [Shape Drawer](https://github.com/earlygrey/shapedrawer) - ShapeRenderer的一种高性能替代方案，可避免批量冲洗。
- [Spine](http://esotericsoftware.com/) - 基于骨骼的动画工具，专门针对游戏的2D动画。
- [gdx-gltf](https://github.com/mgsx-dev/gdx-gltf) - GLTF 3D文件格式支持（导入/导出），PBR着色器和其他高级渲染。

### 其他
- [gdx-dbgagent](https://github.com/PokeMMO/gdx-dbgagent) - 用于调试常见问题的Java代理，例如不处理对象以及修改诸如Color.WHITE的常量。
- [gdx-jnigen](https://github.com/libgdx/libgdx/tree/master/extensions/gdx-jnigen) - 小型库，允许C / C ++代码与Java源代码一起内联编写。
- [gdxGifRecorder](https://github.com/Anuken/GDXGifRecorder) - 记录GIF并自动保存的实用程序类。
- [KTX](https://github.com/libktx/ktx) - libGDX的Kotlin扩展和实用程序。
- [noise4j](https://github.com/czyzby/noise4j) - 基于各种过程内容生成教程的简单地图生成器。
- [Texture Packer GUI](https://github.com/crashinvaders/gdx-texture-packer-gui) - 为libGDX游戏框架打包和管理纹理图集的简单方法。


## 教程

_面向新手和经验丰富的开发人员的教程。_

### 入门

- [Official libGDX Wiki](https://github.com/libgdx/libgdx/wiki) - Wiki-包含大量信息的官方libGDX Wiki。
- [Tann's Hello libGDX](http://tann.space/HelloLibgdx/) - 为初学者提供了从头开始制作游戏的绝佳指南。
- [Splash Screens](https://youtu.be/Rnmq_Jv-pe4) - 有关创建启动画面以在游戏窗口加载之前显示的视频教程。
- [Creating a Launcher](https://youtu.be/3l5F7f7vfTU) - 有关使用libGDX制作游戏启动器的视频教程。
- [Deploying with JPackage](https://github.com/raeleus/skin-composer/wiki/libGDX-and-JPackage) - 通过Gradle命令使用JPackage部署libGDX游戏的教程。
- [JSON in Game Dev](http://mana-break.blogspot.com/2014/06/power-of-json-in-game-development-items.html) - 有关使用JSON存储数据的常规教程。
- [Progress Bar Design](https://github.com/raeleus/skin-composer/wiki/The-Man-Who-Killed-Hitler-and-then-The-Progress-Bar) - 通过示例讨论不同进度条设计技术的利弊。
- [libGDX External Tutorials](https://github.com/libgdx/libgdx/wiki/External-tutorials) - 官方非官方教程的大清单。

### 高级

- [Code Hotswapping](https://youtu.be/zKfh6WuaikQ) - 有关为libGDX项目启用代码热交换以提高生产力的视频教程。
- [Dynamic Textures with Pixmap](https://javadocmd.com/blog/libgdx-dynamic-textures-with-pixmap/) - 详细说明如何使用Pixmaps创建蒙版。
- [iOS Deployment Tutorial](https://link.medium.com/vgYo0mSi3W) - 使用RoboVM在2019年部署到iOS。
- [Sub-pixel Perfect Smooth Scrolling](http://code-disaster.com/2016/02/subpixel-perfect-smooth-scrolling.html) - 完美像素平滑滚动。

## 资产

_收集免费和高质量的资产，使您的游戏更上一层楼。_

- [Kenney Assets](https://kenney.nl/) - 高质量的游戏资产，从2D和3D艺术到音效。
- [OpenGameArt.org](https://opengameart.org/) - 提供各种开放内容资产的存储库。
- [Game-Icons.net](http://game-icons.net/) - 包含大量与游戏相关的炫酷图形的存储库。
- [bfxr.net](https://www.bfxr.net/) - 只需按几个按钮即可快速创建独特的音效，非常适合原型制作。
- [freesound.org](https://freesound.org/) - 巨大的音频片段，样本，录音，哔哔声协作数据库。


## 社区

_与其他libGDX开发人员联系以进行协作并获得帮助。_

- [Discord](https://discord.gg/4S8pQqc) - 每天与社区中的各种领导人进行活跃的聊天。 **推荐**
- [Reddit](https://www.reddit.com/r/libgdx/) - libGDX的非官方subreddit。活动不多。


## 其他清单

_其他可能对libGDX开发人员有用的列表。_

- [Game Networking](https://github.com/MFatihMAR/Awesome-Game-Networking) - 游戏网络编程资源的精选列表。
- [Game Talks](https://github.com/hzoo/awesome-gametalks) - 一份精心策划的游戏讲座（开发、设计等）清单。
- [Java](https://github.com/akullpp/awesome-java) - 一份精心策划的优秀Java框架、库和软件列表。
- [Kotlin](https://github.com/KotlinBy/awesome-kotlin) - 一份精心策划的与Kotlin有关的东西的清单。
- [Magic Tools](https://github.com/ellisonleao/magictools) - 一个游戏开发资源清单，使魔术发生。
- [Game Accessibility Guidelines](http://gameaccessibilityguidelines.com/) - 一个直接的参考包容性游戏设计，可确保尽可能多的人玩得开心。 **推荐**


---


## 贡献

欢迎捐款！首先阅读 [贡献准则](contributing.md) 。



## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)
