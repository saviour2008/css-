# css-字体生成

1.根据svg生成iconfont
先下载svg，再import到https://icomoon.io/，然后把代码给download下来

2.随意使用别的字体
https://fonts.googleapis.com/css?family=Tangerine:bold
在这个网址把family后面的参数换成你想要的字体
页面会显示相应的css样式，copy放到你想要放的css文件里
同时把src: local('Tangerine Bold'), local('Tangerine-Bold'), url(https://fonts.gstatic.com/s/tangerine/v9/Iurd6Y5j_oScZZow4VO5srNZi5FN.woff2) format('woff2');
src里面的url对应的地址copy出来，下载相应的字体，并保存在本地。
这样你本地就有了相应的css文件和相应的字体文件，就可以使用你所下载的字体了
