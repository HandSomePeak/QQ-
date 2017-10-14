# QQ-
用于实现使用QQ来做第三方登录平台，登录APP

1、添加依赖库。TAGRETS -> Build Phases -> Link Binary With Libraries 添加框架（具体哪些框架见项目）

2、在工程配置中的“Build Settings”一栏中找到“Linking”配置区，给“Other Linker Flags”配置项添加属性值“-fobjc-arc”

3、URLScheme 配置： TAGRETS -> info -> URL Types (具体见项目)
    
4、在info.plist文件中加入 LSApplicationQueriesSchemes (具体见项目)
