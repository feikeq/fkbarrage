fkbarrage
=========
FK_html_JS弹幕效果jQuery插件

/*! FKbarrage v1.1 | FeikeWrold | www.fk68.net */


#初始化
    var barrage =$('#feikeq').fkbarrage({
        height:30, //行高
        spacing:4, //间隔 (主元素宽度的4/1) 
        style:'border:1px solid red;', //自定义样式
        speed:15000 //初始速度
    });

#使用
	barrage.pusshtxt('字幕文字','其它CSS样式[可选]');
