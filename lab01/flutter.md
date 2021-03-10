# flutter
## **flutter是什么**
### flutter是谷歌的可移植UI工具包(SDK)，用于从单个代码库为移动、web和桌面制作漂亮的本地编译应用程序，它使用C、C++、Dart和Skia构建，免费且开源。
## **flutter的特点**
- ### flutter是跨平台的，一份代码可以同时支持IOS和Android系统。
- ### Flutter既不使用WebView，也不使用操作系统的原生控件,它使用自己的高性能渲染引擎来绘制widget。
- ### Flutter应用程序性能非常出色。Flutter旨在帮助开发人员轻松实现恒定的60fps。Flutter应用程序通过本机编译的代码运行 - 不涉及解释器，这意味着其可以快速启动并执行。
- ### Flutter实现了热重载开发循环，可以在设备或模拟器上实现亚秒级重载。同时，Flutter的热重载是有状态的，这意味着应用程序状态在重载后仍然会保留。所以可以在应用程序中各个页面快速迭代开发，而无需在每次重新加载后都要从主屏幕重新开始。
## **flutter的优势**
- ### 提高开发效率
    - ### 同一份代码开发iOS和Android
    - ### 用更少的代码做更多的事情
    - ### 轻松迭代
        - ### 在应用程序运行时更改代码并重新加载（通过热重载）
        - ### 修复崩溃并继续从应用程序停止的地方进行调试
- ### 创建美观，高度定制的用户体验
    - ### 受益于Flutter框架提供的丰富的Material Design和Cupertino（iOS风格）的widget,实现定制、美观、品牌驱动的设计，而不受原生控件的限制
## **flutter使用的编程范式**
- ### Composition 组合
- ### Functional programming 函数式编程
- ### Event-driven programming 事件驱动编程
- ### Class-based object-oriented programming 基于类的面向对象编程
- ### Prototype-based object-oriented programming 基于原型的面向对象编程
- ### Imperative programming 命令式编程
- ### Reactive programming 响应式编程
- ### Declarative programming 声明式编程
- ### Generic programming 泛型
- ### Concurrent programming 并发
- ### Constraint programming 约束
## **flutter的设计特性**
- ### flutter中一切皆为widget。
  ### 与其他将视图、控制器、布局和其他属性分离的框架不同，Flutter具有一致的统一对象模型：widget。Widget根据布局形成一个层次结构。每个widget嵌入其中，并继承其父项的属性。没有单独的“应用程序”对象，相反，根widget扮演着这个角色。
  ### widget本身通常由许多更小的、单一用途widget组成，这些widget结合起来产生强大的效果。
- ### flutter框架是一个可扩展的分层结构，它作为一系列独立的库而存在，每个层都建立在前一层之上,又都对前面的层没有访问权，框架层的每个部分都可选、可替换。
  ### ![](..\pictures\flutter_archdiagram.png)