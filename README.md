# 帆软-国际业务组-笔试测验(3大题，周末两天完成)

## 1. Bootstrap框架自定义

### Requirement:

1. 需要根据Bootstrap v5.1.3的文档描述，使用Sass文件自定义我们要想要的css文件
2. [Bootstrap文档链接](https://getbootstrap.com/docs/5.1/getting-started/introduction/),重点阅读:[Sass](https://getbootstrap.com/docs/5.1/customize/sass/),[buttons](https://getbootstrap.com/docs/5.1/components/buttons/)
3. 最后编译导出的CSS文件需要带上Bootstrap按钮组件
4. 除了自带的按钮，比如btn-primary,btn-secondary,这边需要能够**自己构建一个新按钮**，按钮名称：btn-fanruan,按钮是类似btn-primary的扁平样式，按钮初始的背景色：#faad14，字体颜色：#ffffff，按钮边框#faad14；鼠标移动上去(hover)背景色:transparent,字体颜色：#faad14，按钮边框#faad14

## 2. 普通页脚实现

### Requirement:

1. 用PS测量视觉图之间的图片间距，不用百分百精确，但是误差不能超过3px。
2. 网页需要能够识别Retina屏幕，根据Retina屏幕自动调用2倍图。
3. 自定义的JS和CSS需要独立文件，并且需要经过压缩编译，比如JS可以使用Webpack打包，CSS可以由Sass进行编译导出。
4. 视觉图只给出了电脑端的效果，即1200px屏幕尺寸以上的效果，这边要求能够根据自己的前端经验进行自适应调整，让实现的页脚在1200px以下不会出现显示bug。
5. 注意此页脚有三处悬浮点击的交互，必须全部实现。

## 3.表单前端+后端数据入库

### Requirement:

1. 实现左右的表单布局，要求写在了下面的[石墨文档](https://shimo.im/docs/Ddg8GkyyR8PctgDC/)里。
2. 前端效果可以借助bootstrap框架，Vue框架等等你熟悉的工具。这里对JS和CSS的打包要求是没有的，也不要对Retina屏幕进行识别，但是需要保证小屏幕显示无bug。
3. 后端本地需要建立一个接口，接口建立方式可以node，java或者php，并能够连接本地的mysql数据库；最终这边会检查你的接口建立情况。
4. 最后你全部实现完成，可以把自己的接口换成下面这个，我检查一下后端入库情况。请求方法post，接口链接：https://frg.fineres.com/kr/wp-content/themes/japan_index/api/contact_us.php,
   请求参数如下：
   * email
   * username
   * phone
   * company
   * content
   * consultContent

注：以上三条题目还是有点难度的，尽量都完成，如果没有就写下自己解决问题的过程。

