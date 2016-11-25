# csv2arr
An simple js lib to import csv file and translate it to 2D array by javascript.It can automatic detect the file encoding,such as UTF8,GBK(GB2312),BIG-5 and so on.

简单实用的Javascript库，用于导入CSV文件转换成二维数组。可以自动识别文件编码，如UTF8、GBK(GB2312)、BIG-5等等。

To use this lib,you should import some other js lib,include jquery, papaparse.js and jschardet.js,which is include in the ./lib directory.If you customer use IE9 or less,you should import base64.js too.

库依赖：jquery.js、papaparse.js、jschardet.js，这三个库都在./lib目录下有备份，方便使用。如果你需要兼容IE9及以下浏览器，还需要base64.js

Download the packege and open the demo.html to see how to use,wish you would like it.

打包下载，打开demo.html看看使用示范，希望你喜欢^_^

###simple demo 简单示例
$("input[name=csvfile]").csv2arr(function( arr ){
    console.log( arr );
});
