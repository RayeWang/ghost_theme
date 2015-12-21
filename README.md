### 总体介绍
[matery][1]是一个漂亮、简洁、响应式并采用`Material Design`设计的[Ghost][2]博客主题。`matery`基于[Materialize][3]的CSS框架开发而成，集成了[Font Awesome][4]字体图标，以绿色作为主色调，黄色和暗灰色为辅助色，对各种屏幕下的显示细节做了优化和处理，兼容主流的web浏览器。我的个人博客（[闪烁之狐的博客][5]）也在使用这个主题。

### 主要特性

#### 1. 响应式设计

主题采用了响应式设计，在各种设备和屏幕上都有很好的表现.如：在桌面浏览器的宽屏页面里采用了固定上导航栏，手机、平板等小屏幕上则收起和滑出侧导航栏。文字、图片等内容也能在页面中自适应显示。

#### 2. Material Design设计（材料设计）

`Material Design`是谷歌自Android5.0推出的全新的跨平台体验的一套设计语言。核心思想就是把物理世界的体验带进屏幕。去掉现实中的杂质和随机性，保留其最原始纯净的形态、空间关系、变化与过渡，配合虚拟世界的灵活特性，还原最贴近真实的体验，达到简洁与直观的效果。

主题内容均采用`卡片式`显示和交互，点击链接、按钮、图片等时使用波纹扩散动画，符合材料设计规范，体验起来简单、轻松和愉快。

#### 3. “黑客”风格的代码高亮

主题使用[prism.js][6]作为代码高亮引擎，这对于我们程序员来说算是最重要的特性了，matery主题默认采用黑客风格的prism的`okaidia`主题色，你也可以在prism.js官网下载自定制的主题色。下面是代码高亮的示例：

![代码高亮][7]

之所以采用prism.js，主要有以下原因吧：

> Prism 是一款轻量、可扩展的代码语法高亮库，使用现代化的 Web 标准构建。 代码压缩后只有 1.6KB。每添加一个语言平均增加0.3-0.5KB，主题在 1KB 左右。 语言的 CSS 类是可继承的，所以你只需定义一次就能应用到多个代码片段。

#### 4. 更适合国人使用

ghost博客中大多主题都是英文的，各种字体、图标、CDN环境等对中文和国内环境的支持并不是很好，且大多数主题都太“朴素”了，没有现代感。试用了很多都不太满意，于是自己才决定开发一套更适合自己和国人使用的ghost主题，本主题字体显示优良，CDN默认试用国内环境，页面加载更快。

### 安装使用

当你看到本文的时候，应该已经有一个自己的ghost博客了，如果还没有的话，不妨去试，ghost使用Markdown写作，能够让人更加专注写作的内容本身，同时又能方便简单的排版显示。

当你安装好ghost博客之后，只需将本主题[下载][8]下来，解压之后放在您博客的主题文件夹`content/themes/`里面，然后重启ghost博客，在博客后台全局设置页面选择本主题保存即可。

### 自定制修改

博客中的一些地方在博客后台管理界面里是无法设置的，但默认内容都是根据我自己的喜好设置的，您也可以修改成你自己喜欢的内容。

#### 1. 公告提醒栏

在博客的导航栏下有一公告提醒栏，响应式设计的，默认内容是:`推荐使用Chrome、Firefox等现代浏览器浏览本站。珍爱生命，请远离IE！`你可以在matery主题中打开文件`partials/notice.hbs`去修改。

#### 2. 头像和二维码设置

本主题中多了一个头像的概念，跟Logo有所差异，Logo是放在导航栏中的，而在宽屏浏览器中会显示博主信息，其中就有头像，默认是我自己喜欢的红色可爱的小狐狸头像，你可以去`assets/images`这个文件夹下替换成你自己喜欢的头像图片,注意图片名字和后缀不能修改，就是`avatar.jpg`。

点击头像时会弹出手机访问的二维码，修改方式跟头像一样，不再赘述。

#### 3. 联系方式修改

社交联系方式等都放在`partials/user_info.hbs`文件中，你可以修改或者新增你自己需要的联系方式、图标和提醒文字等。图标修改参考Font Awesome的使用方法即可。

#### 4. 友情链接修改

友情链接默认是放在`partials/friend_url.hbs`文件中，你可以修改或者新增你自己喜欢的网站链接。

### 祝你好运

祝你使用本主题写博客更舒心，佛祖保佑更好运。本主题也必然有些不足之处，生命不息，折腾不止，如果有更好的设计和建议，我也会尽量抽出时间来完善，如果您发现了什么bug,可以给我留言，发邮件，加QQ都行。如果您觉得这个主题还不错的话，欢迎在github里star下以示支持，再次感谢。


  [1]: https://github.com/chenjiayin1990/ghost-matery
  [2]: https://ghost.org/
  [3]: http://materializecss.com/
  [4]: http://fontawesome.io/
  [5]: http://blinkfox.com/
  [6]: http://prismjs.com/
  [7]: http://7xnrn5.com1.z0.glb.clouddn.com/code20151026.png
  [8]: https://github.com/chenjiayin1990/ghost-matery
