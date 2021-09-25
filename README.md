# 自用工具

## 项目来历

提高在电脑上工作的效率。

## 安装和使用

项目本身为maven工程，使用方法和普通maven项目一样，导入ide后即可运行。目前并没有提供直接启动的方式， 比如通过`start.bat`或者`start.bat`启动。将来会在发行版中导出可执行jar包，并在项目根目录下添加
启动脚本`start.sh`，方便直接使用。

运行工程有两种方式，一种是运行`com.sheepfly.common`包下的类，另一种是在自己项目中创建
`com.sheepfly.common.services.interfaces.Service`的实例，具体使用方法请参考对应的javadoc以及
命令行初始化参数`com.sheepfly.common.utils.OptionUtil`。

## 添砖加瓦

提pr即可。

### 如何添加自己写的工具

请实现`com.sheepfly.common.services.interfaces.Service`并提供用来运行的主类。