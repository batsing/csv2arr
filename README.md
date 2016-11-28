# csv2arr
Introduction: A simple javascript lib to import csv file and translate it to 2D array.It can automatic detect the file encoding,such as UTF8,GBK(GB2312),BIG-5 and so on.

介绍：简单实用的Javascript库，用于导入**CSV文件转换成二维数组**。可以**自动识别文件编码**，如UTF8、GBK(GB2312)、BIG-5等等。

Compatibility: IE10+,Chrome,Safari,firefox,and fast mode in Chinese browers.IE9 and less is not supported.

兼容性：IE10及以上，Chrome，Safari，firefox，国内浏览器的极速模式。**不支持IE9及以下**版本。

Dependence: To use this lib,you should import some other js lib,include jquery, papaparse.js and jschardet.js,which is include in the ./lib directory.If you customer use IE9 or less,you should import base64.js and it's in the ./lib too.

库依赖：**jquery**.js、**PapaParse**.js、**jschardet**.js，这三个库都在./lib目录下有备份，方便使用。

Download the packege and open the demo.html to see how to use,wish you like it.

打包下载，打开demo.html看看使用示范，希望你喜欢^_^

###simple demo 简单示例
```
$("input[name=csvfile]").change(function(){
	$(this).csv2arr(function( arr ){
		console.log( arr );
	}
});
```
