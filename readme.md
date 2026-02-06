## Made by Github：@Neptune_EX，重庆大学弘深学院2023级学生

### 一、版权与字体
本模板使用的字体为开源字体狮尾四季春，详见
https://github.com/max32002/swei-spring

### 二、致谢
本模板基于
1. 北师大中文CV模板：https://github.com/LeyuDame/BNUCV
2. 西北工业大学中文CV模板：https://www.overleaf.com/latex/templates/npu-cv/mncqzxhvfzrx
3. 武汉大学中文CV模板：https://www.overleaf.com/latex/templates/whuwu-han-da-xue-zhong-wen-jian-li-mo-ban/dbkvxrqjmzpd

此模板基本上在武汉大学的模板改动了包括：
1. 修改校标、配色，使其符合重庆大学vis标准（https://office.cqu.edu.cn/info/1021/1995.htm）；


### 三、使用方法
使用XeLaTeX编译。建议上传Overleaf云端或使用texstudio本地编译。

#### 四、其他注意事项
1. 所有以\fa开头的都是font awesome宏包里的logo。详细信息参考：
https://mirrors.ibiblio.org/CTAN/fonts/fontawesome5/doc/fontawesome5.pdf
2. 如何修改栏目名称？以个人信息为例。
本模板中使用下述命令定义栏目名（即章节名）
\section{\makebox[\widthof{\faAddressCard}][c]{\color{WHU_Blue}{\faAddressCard}}\quad 个人信息}
\faAddressCard为图标，前面有人提到。个人信息即章节名。其他如无必要可以不用管。
3. 我注释掉了一些我用不到的东西。如果你觉得有用，可以选中后按ctrl+/取消注释。