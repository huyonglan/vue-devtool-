第一步：找到vue-devtools的github项目，并将其clone到本地. vue-devtools
git clone https://github.com/vuejs/vue-devtools.git
第二步：安装项目所需要的npm包
npm install //如果太慢的话，可以安装一个cnpm, 然后命令换成 cnpm install
第三步：编译项目文件
npm run build
第四步：添加至chrome游览器
游览器输入地址“chrome://extensions/”进入扩展程序页面，点击“加载已解压的扩展程序...”按钮，选择vue-devtools>shells下的chrome文件夹。

/**
*如果看不见“加载已解压的扩展程序...”按钮，则需要勾选“开发者模式”。
*/

结语：vue-devtools如何使用
当我们添加完vue-devtools扩展程序之后，我们在调试vue应用的时候，chrome开发者工具中会看一个vue的一栏，点击之后就可以看见当前页面vue对象的一些信息。vue-devtools使用起来还是比较简单的，上手非常的容易，这里就细讲其使用说明了。

踩过的坑：
1.npm build总是报错   因为node版本问题  我从5.9.1升级到8.1版本  问题迎刃而解
2.要想知道扩展程序是否安装成功 可以npm run dev 然后在浏览器输入https://localhost:8080验证一下
3.应用到vue的项目时 ，重启浏览器 即可
