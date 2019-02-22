vue调试工具vue-devtools安装及使用
# 1. 到github下载：
	git clone https://github.com/vuejs/vue-devtools
# 2.在vue-devtools目录下安装依赖包
	cd vue-devtools
	cnpm install
# 3.修改shells/chrome/manifest.json文件
	把"persistent":false改成true
#　4.编译代码
	npm run build
＃ 5.扩展Chrome插件
	Chrome浏览器 >  更多程序 > 拓展程序 
	点击加载已解压程序按钮, 选择 vue-devtools > shells > chrome 放入, 安装成功如下图
# 6. vue-devtools使用
	vue项目, 打开f12, 选择vue就可以使用了.
	vue是数据驱动的, 这样就能看到对应数据了, 方便我们进行调试
