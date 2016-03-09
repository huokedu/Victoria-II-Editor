# Victoria-II-Editor
----------------------
维多利亚2的游戏编辑器
如果你对我们的项目有兴趣，欢迎加入我们的QQ群469684234

请放置到游戏根目录下运行！

控制台的语法为SQL风格

## 现在可以公开的情报 ##
- show governments;  显示政体
- show ideologies; 显示意识形态
- show ideologies_gruop; 显示意识形态组

- insert government 政体属性，用空格隔开 value 之前属性对应的值，用空格隔开;  新建政体

- quit;  退出

## 任务分配 ##
@Yakuky 先负责写工厂类，

@练习巡洋舰 鹿岛 负责写决议类,

@乙指 负责写兵种，将领类

包括与之相关的类！

在新建相关的类之前，请确认与其他人没有重复

每个类的load，show，insert方法，还有相应的文件流和储存对象的vector容器都声明在头文件里，定义在相应的cpp文件里。

请参照git上readme文件里的要求的代码规范！

在解析文件的过程中，大括号{}一律解析为对象，“属性 = 值”的语句一律解析为成员变量或对象，重复的相同类型对象或变量一律解析为vector数组

具体请参照git上的government类

## 关于代码规范 ##
- 每一个文件、每一个重要的变量、每一个函数都要注释表明其作用！
- 文件、变量和函数的命名要规范，单词间使用下划线连接，可以用游戏文件已有的内容命名的就以游戏文件内容命名
- 对于一些可能难于读懂的代码，尽量加注释
