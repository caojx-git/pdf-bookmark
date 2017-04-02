# pdf-bookmark
## 本项目用来给pdf自动打上书签方便阅读
由于互联网上存在很多没有书签的pdf书籍，阅读起来十分不方便，手动添加书签又工作量太大，本项目用来给pdf自动打上书签方便阅读
<br />**软件界面**
<br />![](./img/main_gui.png)

## 使用方法
1. **选择pdf文件**，点击**选择文件**按钮选择要添加目录的pdf文件
2. **填写页面偏移量**，有的pdf为扫描版，所以书中的页码可能与pdf文件真实页码不同，书中页码与pdf文件页面之间的差值（真是页码-书中页码）即为页码偏移量。
<br />确定页码偏移量的方法：打开pdf文件将pdf翻到任意带页码的一页，如下图，通过阅读软件查看书籍中的页码与真实页码，将这两个数字相减即可得到页码偏移量，比如下图中的页码偏移量为134-120=14
![](./img/page_offset_m.png)
3. **填入目录内容或者目录url**，在pdf-bookmark目录编辑框填入目录内容或者包含此书目录内容的页面url（url方式目前只支持china-pub）
<br />我们可以通过互联网书店找到我们要处理的pdf书籍的目录内容，以[china-pub](http://www.china-pub.com/)为例，我们可以搜索到《快学scala》的详情页`http://product.china-pub.com/3684420`，以下为目录部分截图
![](./img/scala_exp_cp.png)
<br />以上为china-pub中书籍详情页目录部分，可以点击**↓展开全部内容**然后将完成目录复制到pdf-bookmark目录编辑框中，或者直接将此页面url填入目录编辑框
<br />**填入目录内容示例**
<br />![](./img/scala_exp_bm1.png)
<br />**填入url示例**
<br />![](./img/scala_exp_bm2.png)

4. **生成目录**，点击**生成目录**按钮会生成一个新的包含目录的pdf文件，如下图
<br />![](./img/scala_exp_bm3.png)
