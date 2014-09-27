# iOS Dev Tips


* app工程里同时调试静态库，将静态库工程拖到app工程，在项目link binary里加lib静态库.a，app工程source里引入静态库.h，build setting里的Build Active Architecture Only = NO
