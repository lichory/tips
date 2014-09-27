# iOS Dev Tips


* app工程里同时调试静态库，将静态库工程拖到app工程，在项目link binary里加lib静态库.a，app工程source里引入静态库.h，build setting里的Build Active Architecture Only = NO

* itunes connect invalid binary错误，添加新版本的时候需要勾选跟踪广告的id协议，兼容ios需要去掉编译选项里的arm64