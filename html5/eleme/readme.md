- stylus 模块化
  @import 引入

- vertical-align:top
  兄弟元素的对齐方式   有图片的时候
  inline-block + font-size 0 既不换行也不inline

- brand 图标 60 * 36
  30 * 18 手机大部分是 retina 屏 图标需要是原本图标大小的两倍大
  三倍retina 屏iPhone12 Max
  90 * 54
  前端别打包 ，图片要搞好
  css 像素是物理像素 30*18
  retina  60*36
  3倍     90*54
  媒体选择器
  @media (-webkit-min-device-pixel-ratio: 3)

- bg-image($url) 函数 mixin 混合
  函数运行后有一个返回值
  mixin 是所有的代码都混到调用它的位置去
  完成这部分代码的复用

- stylus 让 css 变成了编程语言
  1. 嵌套 tab let  {}代码块  方便管理
    集体下线，很方便 好管理 代码的组织能力有了
  2. 函数的能力 代码的复用
  3. 变量