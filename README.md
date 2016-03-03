## PJSIP for iOS

> 当前版本：v2.45

### 静态包结构

<pre>
PJSIP
	├── libs
	└── includes
</pre>

### 如何手动使用

> 1.导入PJSIP

PJSIP加入到工程中.

> 2.引入头文件

<pre>
Header Search Path:
$(PROJECT_DIR)/YourProjectName/PJSIP/includes/pjlib
$(PROJECT_DIR)/YourProjectName/PJSIP/includes/pjlib-util
$(PROJECT_DIR)/YourProjectName/PJSIP/includes/pjmedia
$(PROJECT_DIR)/YourProjectName/PJSIP/includes/pjnath
$(PROJECT_DIR)/YourProjectName/PJSIP/includes/pjsip
</pre>

> 2.设置Build Settings

<pre>
Other Linker Flags: -ObjC
Preprocessor Macros: PJ_AUTOCONF=1
</pre>

> 3.添加Libraries

- AudioToolbox
- AVFoundation

### 如何使用Cocoapods导入

<pre>
pod 'PJSIP', :git => 'https://github.com/Guicai-Li/PJSIP-iOS.git'
</pre>

###TODO: 

- Add cocoapods
- shell脚本
- 编译Guide以及demo
- 文档


