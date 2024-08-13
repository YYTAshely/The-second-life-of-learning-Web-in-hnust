# 登入界面纯HTML编写
## 主要框架
- 主体分为header、footer和section
- header主要用来写标题
- footer写一些无关紧要的信息
- section主体采用table来写
## 一些主要功能的实现
- 用户名的输入采用input的text输入
- 密码则采用passward
- 在性别的选择上用了input的redio以及lable标签，lable标签的使用可以让用户点击文字也能选到对应的选项。
- 为了防止出现用户选择男女双重性别，应在input属性中加入相同的name
- section的最后一个内容也就是button，我在button的属性value中写上了立刻登入，这样按钮上也会出现立刻登入
## 一些小东西
为了使用src标签，我在末尾插入了一张图片，直接插入会导致图片过大，不好看，所以我用了css修改了一下src标签的大小